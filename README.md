# cordova-ios-plugin-contact
## DESCRIPTION
* cordova project add plugin with ios contact. 
* This plugin is built for Cordova with ARC.
* This plugin supports iOS9.0 and above.
![](/IMG1.PNG)
![](/IMG2.PNG)
![](/IMG3.PNG)

## Installation
`sudo cordova plugin add https://github.com/wencun/cordova-ios-plugin-contact.git`
## Usage
* JS Page
`openContact(){`
   `cordova.plugins.YHContact.getContact("", (results) => {`
      `alert(JSON.stringify(results));`
    `}, (errMsg) => {`
      `alert(errMsg);`
    `});`
`}`
* Html Page
<button ion-button full  (click)="openContact()" color="dark">contact show!</button>
