# ROS Kinetic 安装 pocketsphinx #

## 安装支持库:
sudo apt-get install ros-kinetic-audio-common

sudo apt-get install libasound2

sudo apt-get install gstreamer0.10-*

sudo apt-get install python-gst0.10

## 安装pocketsphinx:
sudo apt-get install pocketsphinx*

## 安装pocketsphinx声学模型:
sudo apt-get install pocketsphinx-en-us

cd catkin_ws/src

git clone https://github.com/sunmaxwll/pocketsphinx.git

cd pocketsphinx/

## 安装支持库:
dpkg -i libsphinxbase1_0.8-6_amd64.deb

dpkg -i libpocketsphinx1_0.8-5_amd64.deb

dpkg -i gstreamer0.10-pocketsphinx_0.8-5_amd64.deb

cd ..

catkin_make

### 阳光明媚 备 2018.02.27

### 相关参考:
www.cnblogs.com/TooyLee/p/7739783.html
blog.csdn.net/ppp2006/article/details/22151825
blog.csdn.net/qiaocuiyu/article/details/52093509

hmm表示隐马尔可夫声学模型，lm表示language model语言模型

