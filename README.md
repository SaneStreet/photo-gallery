# Photo Gallery - A Hybrid application made with Vue.js and Ionic framework
Runs on Web and Android, so far.

## What you need, to try the app:

Node package installs:
 - @ionic/vue
 - @capacitor/core
 - @capacitor/android

### Run it on Web:
Navigate to your project folder with terminal (I used Command Prompt) and type in 'ionic serve'. Then go to 'localhost:8100' and it will automatically open the tabs. Navigate to 'Photos' and click on the Camera icon, there might be a popup asking for permission to use the Camera in the browser, you need to click yes.
After that it's just to play with it. Delete pictures by clicking on one, and select delete.

### Run it on an Android device:
You need to have Android Studio installed on to open the project and launch it.

Navigate to your project folder with terminal, and type in 'ionic build' to build the project at first and make sure it's running as it should. After the build has completed, type in 'ionic cap open android', this will open the project in Android Studio.

A Gradle build will begin and a lot of other processes need to be done before going further. When it is done with loading all the assets and resources, attach an Android device to your PC or use a virtual device (I suggest a real device, unless you have the firepower to use VD's). Then you can click 'Run' (the green arrow), Gradle builds the app, Android Studio installs the app to your device. Now you can use Photo Gallery.

## Functionality:
There's 2 dummy Tabs and 1 Photos tab. Navigate to Photos, there you will find a Camera icon, which you can click to access the devices or PCs' camera. You might get a popup asking for permission to use the camera, you need to click yes. Take a picture, click OK, and watch the picture appear on the list. You can take multiple just to have a little fun. When you are ready to delete some pictures, click on one picture, and select 'Delete'.