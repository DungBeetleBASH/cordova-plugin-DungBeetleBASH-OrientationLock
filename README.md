# cordova-plugin-DungBeetleBASH-OrientationLock
A lightweight cordova orientation lock plugin for Android

##Usage
setOrientation accepts "portrait" or "landscape".

```javascript
function onDeviceReady() {
    if (device && device.setOrientation) {
        device.setOrientation("portrait");
    }

    document.removeEventListener('deviceready', onDeviceReady);
}

document.addEventListener("deviceready", onDeviceReady, false);
````
