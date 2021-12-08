# React Native Firebase Social App

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
![onboarding-ui](https://user-images.githubusercontent.com/53654225/145168112-ff22733d-e6a5-4371-9f7f-3007c839dd45.png)


### Sign In UI
![social-login](https://user-images.githubusercontent.com/53654225/145168156-8a52da5a-b2d1-4997-a12c-f17e14547322.png)

### Home/Feed Screen UI
![social-app-ui](https://user-images.githubusercontent.com/53654225/145168190-9c8684d5-cdb9-45bf-9c7f-f1e65fbc0d86.png)


