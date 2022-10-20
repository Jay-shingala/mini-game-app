# mini-game-app (node version :- 16.17.0)

ImageBackground : - set bg image

useFonts :- it use for require("font path " )  for whole app (expo-font)

KeyboardAvoidingView :- ir use for tap and close keyboard for ios devices

AppLoading :- it create splsh screen (expo-app-loading)

Alert :- show alert box

> dimation api

Dimation api :- it use for get screen width and height

```
 const dimationWidthh = Dimation.get("window").width
```

useWindowDimensions :- we can use this hook inside component

```
const {height , width} = useWindowDimensions()
```

> Platform Api

Platform :- it use for find platform like ios ,android etc. we can access platform using Platform.OS

we also add file extention like test.android.js or test.ios.js means that android component run on android device and ios component run on ios device. (both contain diffrent styles for each device)

> Screen Orientation

in app.json set default value for auto screen rotation ther are two types of Orientation first is landscape second one portrait mode

portrait means view visible on vartical device

landscap means view visible on horizontal device
