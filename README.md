# hd-idle-mod
hd-idle v1.05 modification (runs script before spindown with -r key)

Note: search $MOD$ in hd-idle.c to locate changes

Build: <br>
cd hd-idle <br>
dpkg-buildpackage -rfakeroot <br>
sudo dpkg -i ../hd-idle_*.deb

Setup: <br>
sudo nano /etc/default/hd-idle

Launch: <br>
sudo service hd-idle restart <br>

