# OpenCVonARMv7
Deb package for introducing OpenCV to RaspberryPi3

## Build Parameter
```
cmake -D CMAKE_BUILD_TYPE=Release \
      -D CMAKE_INSTALL_PREFIX=/usr/local \
      -D OPENCV_EXTRA_MODULES_PATH=/home/pi/opencv_contrib-3.4.1/modules \
      -D ENABLE_VFPV3=ON \
      -D ENABLE_NEON=ON \
      -D BUILD_TESTS=OFF \
      -D WITH_TBB=OFF \
      -D INSTALL_PYTHON_EXAMPLES=ON \
      -D BUILD_EXAMPLES=ON ..
```

## Install
```
$ cd ~
$ sudo apt autoremove libopencv3
$ wget https://github.com/PINTO0309/files/raw/master/opencv-rpi/libopencv3_3.4.2-20180709.1_armhf.deb
$ sudo apt install -y ./libopencv3_3.4.2-20180709.1_armhf.deb
$ sudo ldconfig
```
