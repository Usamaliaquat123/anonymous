
#  :warning: This app is under construction 	:warning: :warning: :warning: :warning: :warning:
# anonymous is now your personal assistant! :smiley:

anonymous is an assistant app to managing different tasks. like you can talk and app respond like a human. It's based on nltk python library and we deploy nltk services in the cloud. So we can use it weather an api and sdk's.
## Some Screenshot's
<div style="float: inline;">
<img src="https://image.ibb.co/hEvnK8/main.png" width="208">
<img  src="https://image.ibb.co/m59phT/Artboard_1.png" width="200">
<img src="https://image.ibb.co/iXDt98/2_slide.png" width="200">
<img src="https://preview.ibb.co/nCHaNT/3_slide.png" width="200">
</div>

## Getting Started [![Build Status](https://travis-ci.org/dwyl/esta.svg?branch=master)](https://travis-ci.org/dwyl/esta)
To get the project. All you have to do is to download the zip file in github OR you can clone this 
project in github using git clone .This project have including firebase and WPapi (Wordpress API to get realtime posts as JSON response).

### Prerequisites
Firstly you will need to install NodeJs , Ionic and cordova as well. Second make sure you created your firebase account. Lastly download this project in your system to get up and running app.  


```
// Getting files
git clone https://github.com/Usamaliaquat123/DigitEMB-Android-App-.git
```

### Installing

First go to 
```
src/app/app.module.ts
```
and add firebase web initialization 
```
firebase.initializeApp({
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  databaseURL: "YOUR_DATABASE_URL",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "MESSAGING SENDER ID"
});
```

and also install dependencies 
```
npm i OR npm install
```
Now firebase initialization setup successfully. You are ready to start your app running in the browser OR in android emulator.


## Running the test

Open up your command prompt navigate to the project folder and type 
```
ionic serve
```
Want to run in the emulator OR device
```
ionic cordova run android  --prod -l
```


## Run on native devices
want to run in android native device. Type this command
```
ionic cordova run android --prod
``` 


## Built With

* [ionic3](https://ionicframework.com/) - The mobile framework used
* [Angular2/4](https://angular.io/) - Language used in frontend
* [wpApi](http://v2.wp-api.org/) - Getting wordpress posts JSON response
* [Firebase](https://firebase.google.com/) - Backend getting users data | and response back to android app.
## Contributing

Please read [CONTRIBUTING.md](https://github.com/Usamaliaquat123/DigitEMB-Android-App-/blob/master/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning
Versions
https://play.google.com/store/apps/details?id=com.usamaliaquat.service.com&hl=en
```
0.0.1 // Updated on android store
0.0.2 // Updated on android store
0.0.3 // Updated on android store
0.0.4 // Not Updated
```

## Authors

* **Usama Liaquat** - *Developer* - [Ulcreative Softwares](https://ulcreativeweb.wordpress.com/)

See also the list of [contributors](https://github.com/Usamaliaquat123/DigitEMB-Android-App-/graphs/contributors) who participated in this project.

## License

This project is licensed under the MIT License . See [License](https://github.com/Usamaliaquat123/DigitEMB-Android-App-/blob/master/LICENSE) for details.

## Acknowledgments

* You can use code for inspirational purpose only
* Inspiration
* etc


### Special Thanks To

<div style="display:inline;">

<img src="https://angular.io/assets/images/logos/angular/angular.png" width="200">
<img src="https://camo.githubusercontent.com/1c4cc9d7e61489e179f5c70a3f493b1f8a0b6e70/68747470733a2f2f63646e2e61757468302e636f6d2f626c6f672f616c7465726e6174697665732d746f2d6e61746976652d6d6f62696c652d646576656c6f706d656e742f696f6e69632d6c6f676f2e706e67" width="200">

<img src="https://cdn.dribbble.com/users/528264/screenshots/3140440/firebase_logo.png" width="200">

<img src="https://s.w.org/about/images/logos/wordpress-logo-stacked-rgb.png" width="200">
</div>
