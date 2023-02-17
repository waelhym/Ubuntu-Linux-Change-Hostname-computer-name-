# Ubuntu-Linux-Change-Hostname-computer-name-
Ubuntu Linux Change Hostname (computer name)
Ubuntu change hostname command
The procedure to change the computer name on Ubuntu Linux:

Type the following command to edit /etc/hostname using nano or vi text editor:
sudo nano /etc/hostname
Delete the old name and setup new name.
Next Edit the /etc/hosts file:
sudo nano /etc/hosts
Replace any occurrence of the existing computer name with your new one.
Reboot the system to changes take effect:
sudo reboot
