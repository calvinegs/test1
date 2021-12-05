---
title: "My First Post"
date: 2021-11-17T22:14:19+08:00
draft: true
---

# Install Linux Mint 20.2 and Applications

# Install snap on Linux Mint

```bash
$ sudo rm /etc/apt/preferences.d/nosnap.pref
$ sudo apt update

$ sudo apt update
$ sudo apt install snapd
```

# Install hugo on Linux Mint

https://snapcraft.io/install/hugo/mint

```bash
$ sudo snap install hugo
```

# Install and Use Visual Studio code on Linux Mint 20

https://linuxhint.com/install-visual-studio-code-linux-mint

# Install Chrome on Linux Mint 20

https://linuxhint.com/install_google_chrome_linux_mint-2

# Install 注音輸入法

https://foxbrush.pixnet.net/blog/post/60608917

# Install 倉頡輸入法

```bash
$ sudo apt-get install fcitx-table-cangjie5
```

# Install notepad-plus-plus

```bash
sudo snap install notepad-plus-plus
```

# Install git

```bash
$ sudo apt install git
```

> # update git to new version

```bash
$ sudo add-apt-repository -y ppa:git-core/ppa
$ sudo apt-get update
$ sudo apt-get install git -y
```

# Install docker

https://www.linuxshelltips.com/install-docker-in-linux-mint/

- Install Docker Using Installation Script

```bash
$ curl -fsSL https://get.docker.com -o get-docker.sh
$ sudo sh get-docker.sh
```

- Add current user to docker group

```bash
$ sudo groupadd docker
$ sudo usermod -aG docker $USER
```
