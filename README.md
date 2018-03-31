# OpenCVonARMv7
RaspberryPi3へのOpenCV導入用debパッケージ保管庫

Build Parameter
```
cmake -DCMAKE_BUILD_TYPE=Release \
    -D CMAKE_INSTALL_PREFIX=/usr/local \
    -D OPENCV_EXTRA_MODULES_PATH=/home/pi/opencv_contrib-3.4.1/modules \
    -DENABLE_VFPV3=ON \
    -DENABLE_NEON=ON \
    -DBUILD_TESTS=OFF \
    -DWITH_TBB=OFF \
    -D INSTALL_PYTHON_EXAMPLES=ON \
    -D BUILD_EXAMPLES=ON ..
```
