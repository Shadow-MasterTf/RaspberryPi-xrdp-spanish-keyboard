# Keyboard Map file to set the XRDP server into Spanish working with all keys!!!

How to install on RASPBIAN JESSIE

Download the **[km-040a.ini](km-040a.ini)** file to your desktop and then copy it to /etc/xrdp folder with this command:

```sh
sudo cp /home/pi/Desktop/km-040a.ini /etc/xrdp/
```

Then replace the owner and the group of the file through the next commands:

```sh
cd /etc/xrdp
sudo chown xrdp.xrdp km-040a.ini
```

After that, you have to restart the XRDP service with this command:

```sh
sudo service xrdp restart
```

Thats all your keyboard layout should be working as expected
