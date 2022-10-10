# telpo_flutter_sdk

A Flutter plugin for handling connection and communication with Telpo thermal printer devices.

<img  src="https://raw.githubusercontent.com/AL-ventures/telpo-flutter-sdk/master/_external/cover.png"  alt="cover" />


## 💡 Motivation

[While we were working on our MASHINPAY solution we purchased Telpo thermal printers (M1s specifically) for our purpose, where after the user makes payment there was a need to print an invoice file. The Telpo devices come with a native SDK and documentation for it. Since there was not an official and customizable implementation of Telpo SDK for Flutter...]

## ⚙️ Android setup
1. Add the ```maven { url "https://jitpack.io" }``` to project level `build.gradle` (`android/build.gradle`).

```gradle
allprojects {
    repositories {
        maven { url "https://jitpack.io" }
    }
}
```

2. Set the `minSdkVersion` as 19 in application level `build.gradle` file (`android/app/build.gradle`).

```gradle
android {
    defaultConfig {
        ...
        minSdkVersion 19
        ...
    }
}
```
 
## 🕹️ Usage

To get started, create an instance of `TelpoFlutterChannel`:

```dart
final _telpoFlutterChannel =  TelpoFlutterChannel();
```

## 📝 Roadmap

✅ Well-written documentation 🤓
✅ Document the platform-specific configurations.
✅ Document the platform-specific configurations.
⏳ Print image file. 
⏳ Toggle printing event via NFC. 🤩

## 🤓 Contributors

<a  href="https://github.com/al-ventures/telpo-flutter-sdk/graphs/contributors"> <img  src="https://github.com/kamranbekirovyz.png" height="75"> </a><a  href="https://github.com/al-ventures/telpo-flutter-sdk/graphs/contributors"> <img  src="https://github.com/mrjnlcn.png" height="75"> </a>


## 🙏 Credits

[Efikas](https://github.com/efikas/flutter_telpo) qardaşdan bəzi kodlar

## 🐞 Bugs/Requests

If you encounter any problems please open an issue. If you feel the library is missing a feature, please raise a ticket on GitHub and we'll look into it. Pull requests are welcome.

## 📃 License

[MIT License](https://github.com/AL-ventures/telpo-flutter-sdk/blob/master/LICENSE)