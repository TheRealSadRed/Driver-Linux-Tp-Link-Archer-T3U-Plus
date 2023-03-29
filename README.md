
**WE INSTALL THE DRIVER**

First we log in to our GNU/Linux distribution, 
make sure we have NOT plugged in our tp-link device, and give the following commands:

------------------------------------------------------------------------------------------------------------

sudo apt install gcc bc -y

git clone https://github.com/TheRealSadRed/Driver-Linux-Tp-Link-Archer-T3U-Plus.git

cd Driver-Linux-Tp-Link-Archer-T3U-Plus

make clean

make

sudo make install

------------------------------------------------------------------------------------------------------------

Now we can attach the device, and it will be automatically recognized. (Sometimes it requires a reboot).

If we do a kernel change we will probably have to do the above procedure again.
