# Note

99% based on https://github.com/ehmcruz/SDL2-Android-Test

# SDL2-Android-Example

SDL2 Example for Android, C/C++ template build tree.

Requires Android NDK and android SDK Tools.
Setup PATH to your SDK and NDK in "local.properties" file, sample:  
<pre>
sdk.dir=/home/user/ANDROID/ASDK
ndk.dir=/home/user/ANDROID/NDK	
</pre>
Prepare SDL2 projects libraries or download ready - see link:  
[https://github.com/AlexanderAgd/SDL2-Android](https://github.com/AlexanderAgd/SDL2-Android)  
and copy "lib" with your SDL2 compiled libraries to folder "app/cpp/lib".  
Fix path to SDL2 and SDL2_image headers in the "app/cpp/Android.mk" file, option "LOCAL_C_INCLUDES"    
Connect your Android device with "Developer mode" ON and run command:
<pre>
./gradlew build
</pre>
to build apk file. Check apk file in "app/build/output/apk/" directory. Or run:   
<pre>
./gradlew installDebug
</pre>
to build APK and install it on your Android device.

# My ehmcruz README

## Install SDL

Google drive: ~/tutoriais/sdl android


![](screenshot.png)
