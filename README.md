
<p align="center">My Channel</br><b>
| <a href="https://discord.gg/GCehyym">Discord</a> | <a href="https://youtube.com/channel/UC3sLb7eZCu72iv3G1yUhUHQ">YouTube</a> |</b></p>

---
## Kali-Linux on Termux Android

---
• Install Apps on Android
- [x] [Termux](https://apkcombo.com/id/termux/com.termux)
- [x] [Vnc Viewer](https://play.google.com/store/apps/details?id=com.realvnc.viewer.android)

---
Tutorial Official | [Click Here >](https://www.kali.org/docs/nethunter/nethunter-rootless)

---
### Installation (Rootless)</br>
Copy and paste this commands to Termux

> pkg update

<details><summary><b><code>Install Kali-Linux With Online</code></b></summary>
on Termux, run this command

#### Install Kali-linux
Rootfs : Armhf, Arm64, i386, Amd64
```
pkg install wget -y ; wget -O install-nethunter-termux https://offs.ec/2MceZWr ; chmod +x install-nethunter-termux ; ./install-nethunter-termux
```

</br>
Note :</br>

* Kali Nano (Cli)
* Kali Minimal (Cli + Pkg Kali)
* Kali Full (Cli + Pkg Kali + Desktop)

Kali Full file size is < 2Gb, the extract time is 10-15 minutes and when it is finished it will be taken to the Kali-Nethunter menu.

---
</details>

<details></br><summary><b><code>Install kali-Linux With Sdcard</code></b></summary>

Before downloading, run this command to termux :

> uname -m

* kalifs-armhf (Arm-v7)
* kalifs-arm64 (Aarch64)
* kalifs-i386  (X86)
* kalifs-amd64 (X86_64)

- [x] [Link Download](http://kali.download/nethunter-images/current/rootfs/?C=S&O=D)

</br>
Note :</br>

* Kali Nano (Cli)
* Kali Minimal (Cli + Pkg Kali)
* Kali Full (Cli + Pkg Kali + Desktop)

---
on Termux, run this commands

> termux-setup-storage

> cd /sdcard/Download

> cp (Name file).tar.xz ~/

> cd

#### Install Kali-linux
```
pkg install wget -y ; wget -O install-nethunter-termux https://offs.ec/2MceZWr ; chmod +x install-nethunter-termux ; ./install-nethunter-termux
```

* Select number, enter.

Note :</br>
If there are options (Y/N), select (N) all. the extract time is 10-15 minutes and when it is finished it will be taken to the Kali-Nethunter menu.

---
</details>

</br>
Note :</br>

Problem update and upgrade | [Click Here >](https://github.com/wahasa/Kali-Nethunter/issues/7#issuecomment-1905351583)

* Start Kali-Linux
> nethunter

* Stop Kali-Linux
> exit

* Delete Kali-Linux
> rm -rf kali-*

</br>
Note :</br>
[sudo] password for kali:kali
</br>

---
Basic commands Kali-Linux
> apt update : Update list package.</br>
> apt upgrade : Upgrade package.</br>
> apt search (pkg) : Search package.</br>
> apt install (pkg) : Install package.</br>
> apt autoremove (pkg) : Delete pkg.</br>
> apt -h : Help all commands.

---
## Desktop Environments
on Kali, run this commands

> apt update

<details></br><summary><b><code>Install Desktop (Nano/Minimal)</code></b></summary>

* Xfce Desktop
```
sudo apt install wget -y ; wget https://raw.githubusercontent.com/wahasa/Kali-Nethunter/main/Desktop/de-xfce.sh ; chmod +x de-xfce.sh ; ./de-xfce.sh
```

* Lxde Desktop
```
sudo apt install wget -y ; wget https://raw.githubusercontent.com/wahasa/Kali-Nethunter/main/Desktop/de-lxde.sh ; chmod +x de-lxde.sh ; ./de-lxde.sh
```

* Lxqt Desktop
```
sudo apt install wget -y ; wget https://raw.githubusercontent.com/wahasa/Kali-Nethunter/main/Desktop/de-lxqt.sh ; chmod +x de-lxqt.sh ; ./de-lxqt.sh
```

* Kde Desktop
```
sudo apt install wget -y ; wget https://raw.githubusercontent.com/wahasa/Kali-Nethunter/main/Desktop/de-kde.sh ; chmod +x de-kde.sh ; ./de-kde.sh
```

* Gnome Desktop

[> Click Here <](https://github.com/wahasa/Kali-Nethunter/blob/main/Kali/gnome.md)

---
</details>

###
<details></br><summary><b><code>Swith Desktop (Full Version)</code></b></summary>

* Swith to Lxde
```
sudo apt install wget -y ; wget https://raw.githubusercontent.com/wahasa/Kali-Nethunter/main/Switch/xfce-lxde.sh ; chmod +x xfce-lxde.sh ; ./xfce-lxde.sh
```

* Swith to Lxqt
```
sudo apt install wget -y ; wget https://raw.githubusercontent.com/wahasa/Kali-Nethunter/main/Switch/xfce-lxqt.sh ; chmod +x xfce-lxqt.sh ; ./xfce-lxqt.sh
```

* Swith to Kde
```
sudo apt install wget -y ; wget https://raw.githubusercontent.com/wahasa/Kali-Nethunter/main/Switch/xfce-kde.sh ; chmod +x xfce-kde.sh ; ./xfce-kde.sh
```

* Swith to Gnome

[> Click Here <](https://github.com/wahasa/Kali-Nethunter/blob/main/xfce-gnome.md)

---
After switching run the command :
```
nano .vnc/xstartup
```

Put a sign (#) on the previous desktop and unmark (#) on the selected desktop.
</details>

</br>
Note :</br>
[sudo] password for kali:kali

---
Feature
- [x] Fixed Sound          | [Click Here >](https://github.com/wahasa/Kali-Nethunter/tree/main/Note)
- [x] Access to Sdcard     | [Click Here >](https://github.com/wahasa/Kali-Nethunter/tree/main/Note)
- [x] Access to Termux-x11 | [Click Here >](https://github.com/wahasa/Kali-Nethunter/tree/main/Note)
- [x] Fixed Browser Crash  | [Click Here >](https://github.com/wahasa/Kali-Nethunter/tree/main/Note)
- [x] Install Applications | [Click Here >](https://github.com/wahasa/Kali-Nethunter/tree/main/Apps)

Visit problem now in : 
[Issues](https://github.com/wahasa/nethunter/issues)

---
## VNC Viewer
<details></br><summary><b><code>Kali Desktop (Nano/Minimal)</code></b></summary>

* Start VNC Server

on Kali, run this command to start
```
vnc-start
```

* Open Vnc Viewer

Add (+) VNC Client to connect, fill with :

Address
```
localhost:1
```

Name
```
Kali Desktop
```

To disconnect VNC Client, click (X) on the right.

* Stop VNC Server

on kali, run this command to stop
```
vnc-stop
```

---
</details>

####
<details></br><summary><b><code>Kali Desktop (Full Version)</code></b></summary>

* Start VNC Server

on Kali, run this command to start
```
kex
```

* Open Vnc Viewer

Add (+) VNC Client to connect, fill with :

Address
```
localhost:1
```

Name
```
Kali-Nethunter
```

To disconnect VNC Client, click (X) on the right.

* Stop VNC Server

on kali, run this command to stop
```
kex stop
```
</details>

---
## Termux-x11
<details></br><summary><b><code>Termux-x11 Android</code></b></summary>

[> Click Here <](https://github.com/wahasa/Kali-Nethunter/blob/main/Note/Termux-x11fix.md)
</details>
</br>

---
<p align="center">Good Luck</p>

---
