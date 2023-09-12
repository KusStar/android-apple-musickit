# android-apple-musickit

Publish Apple MusicKit for Android to jitpack.io

https://developer.apple.com/download/all/?q=Android%20MusicKit
https://developer.apple.com/musickit/android/

Add it to your build.gradle with:
```gradle
allprojects {
    repositories {
        maven { url "https://jitpack.io" }
    }
}
```

and:

```gradle
dependencies {
    implementation "com.github.kusstar.android-apple-musickit:apple_musickitauth:893b2c98ab"
    implementation "com.github.kusstar.android-apple-musickit:apple_mediaplayback:893b2c98ab"
}
```