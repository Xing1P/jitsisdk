Change Note
===============================
1. JitsiMeetView: remove dispose() from onDetachedFromWindow()
2. remove from build.gradle android/sdk `lintOptions {
        abortOnError false
    }`
3. commect run react package in build.gradle android/app
4. comment ScreenSharingButton,MuteEveryonesVideoButton in OverflowMenu.js
5. add mavenLocal() to buildscript repo

Build Note
===============================
1.  ./gradlew cleanBuildCache
2.  ./gradlew assembleRelease
3.  ./gradlew publish

