# i3wm with gaps
# Works great with Debian Stable
Install [debian os](https://www.debian.org/download)
I used debian 11 version (code name "bullseye")

I wanted to use i3 as my window manager but also using gaps configuration 
as 
default.

----

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
