# openCV

install openCV
  
  import cv2
  >>> cv2.__version__ 
  '3.2.0'
  sudo pip uninstall opencv-python
  
  2.4.13
  http://docs.opencv.org/2.4/doc/tutorials/introduction/linux_install/linux_install.html  
[compiler] sudo apt-get install build-essential
[required] sudo apt-get install cmake git libgtk2.0-dev pkg-config libavcodec-dev libavformat-dev libswscale-dev
[optional] sudo apt-get install python-dev python-numpy libtbb2 libtbb-dev libjpeg-dev libpng-dev libtiff-dev libjasper-dev libdc1394-22-dev

extract http://opencv.org/releases.html
cd ~/opencv
mkdir release
cd release
cmake -D CMAKE_BUILD_TYPE=RELEASE -D CMAKE_INSTALL_PREFIX=/usr/local ..
make
sudo make install
