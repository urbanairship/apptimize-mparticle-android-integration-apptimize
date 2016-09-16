## Apptimize Kit Integration

This repository contains the [Apptimize](https://www.apptimize.com/) integration for the [mParticle Android SDK](https://github.com/mParticle/mparticle-android-sdk).

### Adding the integration

1. Add the kit dependency to your app's build.gradle:

    ```groovy
    dependencies {
        compile 'com.mparticle:android-apptimize-kit:4+'
    }
    ```
2. Follow the mParticle Android SDK [quick-start](https://github.com/mParticle/mparticle-android-sdk), then rebuild and launch your app, and verify that you see `"Apptimize detected"` in the output of `adb logcat`.
3. Reference mParticle's integration docs below to enable the integration.

### Documentation

[Apptimize integration](http://docs.mparticle.com/?java#apptimize)

### License

[Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0)