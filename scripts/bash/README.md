# Bash scripts for Ubuntu and Debian

This is a compilation of my scripts in Ubuntu or Debian that I consider useful.

| Script                            | Description                                                    |
|----------------------------------|----------------------------------------------------------------|
| [Install additional software](install-additional-software.sh) | Installs additional CLI and GUI software for Ubuntu or Debian. |
| [Install OpenCV](install-opencv.sh)              | Installs OpenCV on Ubuntu or Debian.                           |
| MILQ theme for Debian with Xfce| Set up my [personal theme](http://milq.github.io/things-to-do-just-after-installing-ubuntu-debian/milq-screenshot.png) on Debian with XFCE. |
| Set up Ubuntu/Debian for secondary school | Set up Ubuntu/Debian with Xfce with secondary school educational software |


Opencv for python cmd:
```
cmake -D BUILD_opencv_python3=yes -D BUILD_opencv_python2=no -D PYTHON3_EXECUTABLE=/home/zzz/anaconda3/envs/mask/bin/python3.6m -D PYTHON3_INCLUDE_DIR=/home/zzz/anaconda3/envs/mask/include/python3.6m -D PYTHON3_LIBRARY=/home/zzz/anaconda3/envs/mask/lib/libpython3.6m.so -D PYTHON3_NUMPY_INCLUDE_DIRS=/home/zzz/anaconda3/envs/mask/lib/python3.6/site-packages/numpy/core/include -D PYTHON3_PACKAGES_PATH=/home/zzz/anaconda3/envs/mask/lib/python3.6/site-packages/numpy -D PYTHON_DEFAULT_EXECUTABLE=/home/zzz/anaconda3/envs/mask/bin/python3.6m ..
```
