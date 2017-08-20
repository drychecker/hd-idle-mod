# hd-idle-mod
hd-idle v1.05 modification (runs script before spindown with -r key)

Note: search $MOD$ in hd-idle.c to locate changes

Build:
cd hd-idle
dpkg-buildpackage -rfakeroot
sudo dpkg -i ../hd-idle_*.deb

Setup:
sudo nano /etc/default/hd-idle

Launch:
sudo service hd-idle restart
