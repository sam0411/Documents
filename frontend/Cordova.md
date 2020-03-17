## Cordova
npm install cordova -g  
npm install ionic -g  

### Cordova Initialization
cordova create cordova com.example.hello HelloWorld   
cordova platform add ios  
cordova platform add android  
cordova platform ls  

cordova requirements  

cordova build  
cordova build ios  
cordova build android  

### Ionic Initialization
ionic start Cordova_Ionic blank
```text
    start will tell the CLI create a new app.
    Cordova_Ionic will be the directory name and the app name from your project.
    blank will be the starter template for your project.
        tabs : a simple 3 tab layout
        sidemenu: a layout with a swipable menu on the side
        blank: a bare starter with a single page
        super: starter project with over 14 ready to use page designs
        tutorial: a guided starter project
```
ionic serve