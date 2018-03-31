# OpenCVonARMv7
RaspberryPi3へのOpenCV導入用debパッケージ保管庫

Build Parameter
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
