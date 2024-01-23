# Debian DWM Bootsrap
Simple script to install suckless [DWM](https://dwm.suckless.org/) on bare minimal Debain 12.

# Prerequisite
Make sure the user has **sudo** previlidge and the machine has access to the internet.

## Sudo

On minimal Debian, sudo is not pre-installed.

```
$ apt install sudo
$ usermod -aG sudo username
```
Swap username with your actual username, reboot the machine and loging as user.

# Clone the repo

```
$ sudo apt install git
$ git clone https://github.com/Kouei-Lin/debian-dwm-bootstrap ~/debian-dwm-bootstrap
```

# Run the script

```
$ cd ~/debian-dwm-bootstrap
$ chmod +x dwm.sh
$ ./dwm.sh
```

# Start DWM

Once the script is done, type in `startx` in the terminal to start DWM.
