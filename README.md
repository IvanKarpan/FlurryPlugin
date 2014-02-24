FlurryPlugin
============

Forked from https://github.com/jfpsf/flurry-phonegap-plugin and made a proper Cordova 3 plugin.

## Usage

    cordova plugin add https://github.com/PatrickHeneise/FlurryPlugin.git


Verify that `libFlurry.a` is in the Build Phases/Link Binary with Libraries and the Frameworks `CFNetwork`, `Security` and `SystemConfiguration` frameworks are added.

1. Call the startSession() method, with your app key, after the device is ready
2. Call the other Flurry methods as appropriate.


## Contributors

- [jfpsf](https://github.com/jfpsf)
- [Koray Balcı](https://github.com/Koraybalci)

## License
Apache 2.0