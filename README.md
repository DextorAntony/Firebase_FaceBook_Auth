# Firebase_FaceBook_Auth

   ![Alt](https://www.gstatic.com/devrel-devsite/v595dc2b5326ecd7de309fb4a71a7facdb2414a46fa087cc37cc0f175714dd5bb/images/firebase/touchicon-180.png)
 
 
 You can let your users authenticate with Firebase using their Facebook accounts by integrating Facebook Login into your app.
 
 # Before you begin :
           
   Read the official [Docs](https://firebase.google.com/docs/auth/android/facebook-login?authuser=0). 
   
  # Enable Facebook Login:

   1.In the [Firebase console](https://console.firebase.google.com/), open the Auth section.
   
   2.On the Sign in method tab, enable the Facebook sign-in method and specify the App ID and App Secret you got from Facebook.
   
   3.Then, make sure your OAuth redirect URI (e.g. my-app-12345.firebaseapp.com/__/auth/handler) is listed as one of your OAuth redirect URIs in your Facebook app's settings page on the [Facebook for Developers site](https://developers.facebook.com/) in the Product Settings > Facebook Login config.

    Don't Forget to replace your App Id in Strings
