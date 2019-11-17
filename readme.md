# React Native >0.60 AWS Hosted UI

## Setup  

```react-native init rnhui
react-native init rnhui
cd rnhui
npm install aws-amplify
npm install aws-amplify-react-native
# copy contents of App.js from (1)
# copy aws-exports.js from (1)
# modify AndroidManifest.xml to add the intent-filter
react-native run-android
```

## Known Issue

User login is not persisted after swipe-killing and reopening the app (only android has been tested). This issue does not exist in link 1 repo running RN 0.58.4.  

## Links  

1. [https://github.com/manueliglesias/hosted-ui-react-native-cli](https://github.com/manueliglesias/hosted-ui-react-native-cli)  
