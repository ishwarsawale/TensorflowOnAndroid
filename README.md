# TensorflowOnAndroid
TensorFlow (1.2.0) Image Classifier Gradle Standalone Port
This project is a way to get started with TensorFlow Image Classifier quickly.

Native compiled libraries are embedded in the 1.2.0 tag, so you won't need to install the NDK.
However, this means that you cannot change the org.tensorflow.demo.env.ImageUtils class.
Here's what you need to do if you want, for example, to use a different package name:

* Install the NDK and build tools
* Checkout the 1.2.0-cmake tag
* Modify line 7 of the app/src/main/cpp/imageutils_jni.cpp file to specify your new package name
## Demo

![screenshot_2017-07-12-14-57-45](https://user-images.githubusercontent.com/15515106/28111840-88108546-6714-11e7-8137-f41833b3944c.png)
![screenshot_2017-07-12-14-57-58](https://user-images.githubusercontent.com/15515106/28111845-88528b26-6714-11e7-82c8-1387d9d61aa3.png)
![screenshot_2017-07-12-14-59-59](https://user-images.githubusercontent.com/15515106/28111844-8851c63c-6714-11e7-8dfa-ff7210d7bd71.png)
