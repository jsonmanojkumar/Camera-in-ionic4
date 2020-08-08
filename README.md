# Camera-in-ionic4


# Install the camera plugin using the below command.
1.  ionic cordova plugin add cordova-plugin-camera
2.  npm install @ionic-native/camera

# Import the plugin to the app.module.ts file and include the plugin in the providers.
import { Camera, CameraOptions } from '@ionic-native/camera/ngx';

#  Import the camera plugin to home.ts file and create an object reference using the constructor.
import { Camera, CameraOptions } from '@ionic-native/camera/ngx';
constructor(private camera: Camera){}

# Deploy the app to your phone and test it. 
ionic cordova platform add android
ionic cordova run android --aot
