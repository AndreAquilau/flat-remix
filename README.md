## Instalação thema Flat-Remix

#### install git 
```bash
:~$ sudo apt install git
```
#### clone repository flat-remix
```bash
:~$ sudo clone https://github.com/daniruiz/flat-remix
```

#### clone the other repository (GTK theme)
```bash
:~$ git clone https://github.com/daniruiz/flat-remix-gtk
```
```bash
:~$ mkdir -p ~/.icons && mkdir -p ~/.themes
```
```bash
:~$ cp -r flat-remix/Flat-Remix* ~/.icons/ && cp -r flat-remix-gtk/Flat-Remix-GTK* ~/.themes/
```
```bash
:~$ sudo apt install gnome-tweak-tool fonts-hack-ttf -y
```

#### References
* [The DEFINITIVE UBUNTU Guide for Beginning Devs - Fabio Akita](https://www.youtube.com/watch?v=epiyExCyb2s)
* [How to install Flat-Remix Theme on Any Linux Distribution?](https://www.osradar.com/install-flat-remix-theme-ubuntu/)
