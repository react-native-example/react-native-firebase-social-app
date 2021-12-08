# React Native Firebase Social App

This repository is based on my YouTube tutorial series where I'm creating a react native social app with Firebase.

# Running on the local system 
```
- clone the project using `git clone git@github.com:react-native-example/react-native-firebase-social-app.git`
- add `local.properties` in `android` folder using the `local.properties.sample` file and adjust the sdk location
- generate the `google-services.json`  and put in the `android/app/` folder

```
 - now you can run  the project using the  `yarn start` and `yarn android` 
 - you can generate the apk using `yarn release` command
# generating the google-services.json

```
- go to the from `https://console.firebase.google.com/u/0/` 
- create a project 
- Go to the `android/app/build.gradle` and check the applicationId


defaultConfig {
        applicationId "com.socialapp"
        minSdkVersion rootProject.ext.minSdkVersion
        targetSdkVersion rootProject.ext.targetSdkVersion
        versionCode 1
        versionName "1.0"
        multiDexEnabled true
        vectorDrawables.useSupportLibrary = true
    }
 
- create app using the `applicationId` used found in the above step. 
- download the `google-services.json` file
```
## Watch it on YouTube
- [Onboarding UI in React Native](https://www.youtube.com/watch?v=SMkR-iIGvwQ)
- [Login & Signup UI in React Native](https://www.youtube.com/watch?v=ZxP-0xbz5sg)
- [Firebase Authentication in React Native](https://youtu.be/J7pkSP18Oko)
- [Google Login in React Native with Firebase](https://youtu.be/SdYp5JdMvs0)
- [Facebook Login in React Native with Firebase](https://youtu.be/pDLo7Pfcvfk)
- [Home/Feed Screen UI of Social App using Styled-Components](https://youtu.be/iyNmGXt4vNA)
- [React Native Firebase Storage Tutorial for Storing Photos](https://youtu.be/1GpOS5mrGHI)
- [React Native Firebase Firestore Tutorial | Create/Fetch/Delete Posts](https://youtu.be/ncxmNxNk2yc)
- [Image Loader & Shimmer Effect for Posts on Home Screen](https://youtu.be/bHWoW_aNmnY)
- [Messages & Chat Screen UI](https://youtu.be/bGGeD5RkdzQ)
- [User Profile with Firebase](https://youtu.be/aFtYsghw-1k)

## Packages Used
- [React Native Onboarding Swiper](https://github.com/jfilter/react-native-onboarding-swiper)
- [React Navigation v5](https://reactnavigation.org/)
- [React Native Firebase v6](https://rnfirebase.io/)
- [React Native Vector Icons](https://github.com/oblador/react-native-vector-icons)
- [Styled Components](https://styled-components.com/)
- [React Native Action Button](https://github.com/mastermoo/react-native-action-button)
- [React Native Image Crop Picker](https://github.com/ivpusic/react-native-image-crop-picker)
- [React Native Skeleton Placeholder](https://github.com/chramos/react-native-skeleton-placeholder)
- [React Native Gifted Chat](https://github.com/FaridSafi/react-native-gifted-chat)

### Onboarding UI
![Onboarding UI](https://raw.githubusercontent.com/itzpradip/react-native-firebase-social-app/master/assets/screenshots/onboarding-ui.png)

### Sign In UI
![Sign in UI](https://raw.githubusercontent.com/itzpradip/react-native-firebase-social-app/master/assets/screenshots/social-login.png)

### Home/Feed Screen UI
![Home/Feed Screen UI](https://raw.githubusercontent.com/itzpradip/react-native-firebase-social-app/master/assets/screenshots/social-app-ui.png)