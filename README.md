# rpi_runs_op

## 1st section to build the environment for op 

![](https://github.com/smiletoeveryone/rpi_runs_op/blob/master/rpi_op.jpg)

1.~# sudo apt install git curl python-pip

2.~# sudo pip install --upgrade pip>=18.0 pipenv

3.~# sudo apt install ffmpeg libavformat-dev libavcodec-dev libavdevice-dev libavutil-dev libswscale-dev libavresample-dev libavfilter-dev

4.~# sudo apt install autoconf automake clang clang-3.8 libtool pkg-config build-essential

5.~# sudo apt install libarchive-dev

6.~# sudo apt install python-qt4

7.~# sudo apt install libzmq3-dev

## 2nd section

1.download openpilot, recommend 0.5.4 or earlier

2.download "openpilot-tools" and paste into /openpilot, if you like to manage your car by a joystick later.

3.

3.~/openpilot$ pipenv install # for creating a virtual environment for op

4.~/openpilot$ pipenv shell # run the virtual env

5.~/openpilot/openpilot-tools$ 
