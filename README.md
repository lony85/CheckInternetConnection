# Check Internet Connection
CheckInternetConnection helps to find out if user`s Android device is connected to Internet or not. 
<br>
This Library wrote with Kotlin Language.
</br>
# Download
1. In setting.gradle of your project in repositories add:
```
    maven { url 'https://jitpack.io' }
```
2. In build.gradle of your app add library:
```
    implementation 'com.github.lony85:CheckInternetConnection:1.0.0'

```

# How it works:
```
NetworkChecker(context).isInternetConnected
```
This will return a Boolean.


# Licence
Licensed under the MIT License.
