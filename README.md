# Caffe DNN Demo
## Requirement Libraries

1. OPENCV 3.3.1
2. OPENCV DNN Module
3. GoogleNet trained model

Cross compiling using Yocto or Buildroot SDK:

    $ $CXX demo.cpp -o demo -I sysroots/aarch64-poky-linux/usr/include/ -L sysroots/aarch64-poky-linux/usr/lib -lopencv_core -lopencv_imgproc -lopencv_highgui -lopencv_dnn -lopencv_imgcodecs

