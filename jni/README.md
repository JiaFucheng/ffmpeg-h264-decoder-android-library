# Set FFMpeg Library Path
In Android.mk, you should set your own ffmpeg android library path, which should contain **include** and **lib** directory.
# NDK Build
```shell
cd ffmpeg-h264-decoder-android-library/jni/
ndk-build
```
After ndk-build, you will see .so files in ../libs/ directory, copy them to your android project.