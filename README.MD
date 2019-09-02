# capsimg
Capsimg library for Android

Original sources retrieved from https://github.com/lubomyr/uae4arm/tree/master/plugins/capsimage on 09/02/2019

# Build instructions
- install latest Android NDK version
```
cd jni
ndk-build -j12
```
- resulting libraries for all the Android platforms are then found in libs folder of repo
- the libraries are all names `libcapsimg.so` instead of `capsimg.so`, but can be easily renamed manually (see below)

# Installation instructions for use with Retroarch PUAE 
- find the .so file for your Android platform
- make sure the .so file is named `capsimg.so`, not `libcapsimg.so`, otherwise rename manually
- copy the `capsimg.so` file to your Retroarch system folder on your Android device
- you should now be able to load .ipf files inside PUAE
