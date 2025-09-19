# Outline SDK Mobileproxy

This repository provides pre-compiled binaries of the Outline SDK Mobileproxy for Android and iOS. See the [Outline SDK](https://github.com/Jigsaw-Code/outline-sdk/tree/main/x/mobileproxy) for the library's source code.

## Integration

### Android

We use JitPack to distribute the Android library. To integrate it into your app, follow these steps:

1.  Add the JitPack repository to your root `build.gradle` file:
    ```groovy
    allprojects {
        repositories {
            ...
            maven { url 'https://jitpack.io' }
        }
    }
    ```
2.  Add the dependency to your app's `build.gradle` file:
    ```groovy
    dependencies {
        implementation 'com.github.jigsaw-code:outline-sdk-mobileproxy:<version>'
    }
    ```

### iOS

You can add the Mobileproxy to your Xcode project using Swift Package Manager.

1.  In Xcode, go to **File > Add Package Dependencies...**
2.  Enter the package repository URL: `https://github.com/jigsaw-code/outline-sdk-mobileproxy`
3.  Select the desired version.

## Releasing

For release instructions, see the [./RELEASING.md](./RELEASING.md) file.

## License

This repository is licensed under the Apache License 2.0.

**Note:** The Psiphon extension is not supported as its code is under the GPL license.
