# i3wm with gaps
# Works great with Debian Stable
# I used Debian-11.5 version

I wanted to use i3 as my window manager but also using gaps conf as 
default and running on debian stable.

My setup is install debian minimal without GUI and used expert method.

```
sudo apt install git

git clone https://github.com/rendiwijiatmoko/i3wm-debian-setup

cd i3wm-debian-setup

./install.sh (includes nerdfonts.sh and copyconf.sh unless commented)
```
after that install other shell thare are 

```
./nerdfonts.sh
```
to install font 

```
./copyconf.sh
```
for customized configuration


finish the setup
```
sudo reboot
```
