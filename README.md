# TensorflowOnAndroid
TensorFlow (1.2.0) Image Classifier Gradle Standalone Port
This project is a way to get started with TensorFlow Image Classifier quickly.

Native compiled libraries are embedded in the 1.2.0 tag, so you won't need to install the NDK.
However, this means that you cannot change the org.tensorflow.demo.env.ImageUtils class.
Here's what you need to do if you want, for example, to use a different package name:

* Install the NDK and build tools
* Checkout the 1.2.0-cmake tag
* Modify line 7 of the app/src/main/cpp/imageutils_jni.cpp file to specify your new package name
