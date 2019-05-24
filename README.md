1. thêm vào file androidManifest. xml
    
    <uses-permission android:name="android.permission.INTERNET" />
    <uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" />
    <uses-permission android:name="android.permission.RECORD_AUDIO" />
    <uses-permission android:name="android.permission.CAMERA" />
    <uses-permission android:name="android.permission.READ_PHONE_STATE" /> 
    
  2. thêm vào build.gradle (app)  trong dependencies
  
           implementation files('libs/sinch-android-rtc-3.8.0-VIDEO-SNAPSHOT.jar')
           androidTestImplementation('com.android.support.test.espresso:espresso-core:3.0.2', {
        exclude group: 'com.android.support', module: 'support-annotations'})
        
        
   3. copy file jniLibs  trong  ....\MinTalk2\app\src\main   vào ....\app\src\main của project
   
   4. copy 2 file trong ....\MinTalk2\app\libs   vào .....\MinTalk2\app\libs của project
  

   
