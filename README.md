# rpi_runs_op



![](https://github.com/smiletoeveryone/rpi_runs_op/blob/master/rpi_op.jpg)

## 1st section to build the environment for op 

1.~# sudo apt install pip

2.~# sudo apt install autoconf automake clang clang-3.8 libtool pkg-config build-essential

3.~# sudo apt install libarchive-dev

4.~# sudo apt install python-qt4

5.~# sudo apt install libzmq3-dev

## 2nd section

1.download openpilot, recommend 0.5.4 or 0.5.8

2.~/openpilot$ ./install_capnp.sh  #  you could get in this web

3.~/openpilot$ pip install pipenv

4.~/openpilot$ pipenv install  #  for creating a virtual environment for op

5.~/openpilot$ pipenv shell  #  run the virtual env

6.~# git clone https://github.com/commaai/openpilot-tools.git tools  # if you like to manage your car by a joystick later.

7.~/openpilot$ cd tools

8.~/openpilot/tools$ pip install -r requirements.txt  #  should be ran in the vitual env

9 ~/openpilot/tools$ export PYTHONPATH=/path-to-openpilot
