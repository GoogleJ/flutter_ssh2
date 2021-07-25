## 2.1.0

* Nullsafe support
* Dependency and compatibility updates
* isConnected functionality added
* Add doc comments to all public APIs
* Fix issues to increase pub points
* Change package name to ssh2

## 0.0.7

* Moved getInputStream before channel connect on Android.
* Set minimum SDK version to 2.1.0. 

## 0.0.6

* Set compileSdkVersion to 28, fixing build error "Execution failed for task ':ssh:verifyReleaseResources'"
* Set uuid plugin version to ^2.0.0.

## 0.0.5

* Fixed download exception on Android due to [this issue](https://github.com/flutter/flutter/issues/34993).

## 0.0.4

* Changed disconnect() method to sync. 
* Fixed Android crash issue "Methods marked with @UiThread must be executed on the main thread.".

## 0.0.3

* Fixed invokeMethod missing indirection.
* Add note about OpenSSH keys, add passphrase to key example.

## 0.0.2

* Check if client is null before getting session in Android.

## 0.0.1

* Initial release.

