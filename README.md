flurry-phonegap-plugin
======================

Forked from [CarsonF](https://github.com/CarsonF/flurry-phonegap-plugin)

Updated to be installable via plugman/cordova-cli and compatible with cordova 2.9.0 and 3.x.  If you want to use 2.9, use the cordova2_9 branch.  Otherwise, use the master branch.

Included latest Flurry libraries (Android: 3.3.2, iOS: 4.3.0)


=====

Phonegap plugin for Flurry mobile analytics

You really need to be careful that you pass the correct values to the methods. In particular, all event parameters must be
in an NSDictionary that only contains strings, and remember that in Objective C booleans are Yes and No.

Here's how to install the plugin:

1. Register with [Flurry](http://www.flurry.com/) and get an App key. 
2. Install plugin with plugman or cordova-cli: `cordova plugin add https://github.com/8zrealestate/flurry-phonegap-plugin/`
3. Call `Flurry.startSession()` method, with your app key, after the device is ready (Flurry is injected into the `window` object).
4. Call the other Flurry methods as appropriate.

=====
Licensed under the Apache 2.0 license, just like the original fork from [jfpsf](https://github.com/jfpsf/flurry-phonegap-plugin)

http://www.apache.org/licenses/LICENSE-2.0
