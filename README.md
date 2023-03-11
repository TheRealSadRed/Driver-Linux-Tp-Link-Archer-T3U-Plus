
**WE INSTALL tTHE DRIVER**

First we log in to our GNU/Linux distribution, 
make sure we have NOT plugged in our tp-link device, and give the following commands:

sudo apt install gcc bc -y

git clone https://github.com/RinCat/RTL88x2BU-Linux-Driver.git

cd RTL88x2BU-Linux-Driver

make clean

make

sudo make install
