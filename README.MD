# Capsimg (IPF) Android
This is the Capsimg (IPF) library for Android

Original sources retrieved from https://github.com/lubomyr/uae4arm/tree/master/plugins/capsimage on 09/02/2019

# Build instructions
- install latest Android NDK version
```
cd jni
ndk-build -j12
```
- resulting libraries for all the Android platforms are then found in libs folder of repo
- the libraries are all named `libcapsimg.so` instead of `capsimg.so`, but can be easily renamed to `capsimg.so` so they work with Retroarch PUAE.

# Installation instructions for use with Retroarch PUAE 
- download the latest release zip from the releases page: https://www.github.com/rsn8887/capsimg/releases/latest
- unzip the archive
- find the .so file for your Android platform in one of the subfolders
- make sure the .so file is named `capsimg.so`, not `libcapsimg.so`, otherwise rename manually
- copy the `capsimg.so` file to your Retroarch system folder on your Android device
- you should now be able to load .ipf files inside Retroarch PUAE
