## SSH access on volumio

user: volumio

password: volumio

For security reasons, SSH is disabled by default on all versions after 2.199 (except first boot). It can be however enabled very easily.

### First method: DEV UI (easy)

Navigate to the DEV ui by pointing your browser to VOLUMIOIP/DEV or volumio.local/DEV . Find the SSH section, and click enable. From now on your SSH will be permanently enabled.

<img src="./img/ssh_enable.png">


__Note__ : You'll see no change when clicking on the button, but it will be ok.


### Second method: file (more advanced)

Mount your SD card on your computer.

Create or copy a file called ssh in /boot . You can do it right after flashing Volumio, by creating it in the "Boot" partition of your SD Card.
