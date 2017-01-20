---

layout: blank
title: Software Installation
permalink: /installation/
---

# Requirements

CrartBeerPi is running on every Raspberry Pi Model from RaspberryPi Zero to RaspberryPi 3.
> Its recommened to use a Raspberry Pi 3 if you like to run the user interface on the Raspberry Pi browser.

# Raspberry OS Installation (Noobs)

Here you will find the guide to install Raspberry Pi Operating System.

<a href="https://www.raspberrypi.org/help/noobs-setup/" class="btn btn-3d btn-lg wow fadeInUp btn-red animated" data-wow-delay="0.9" style="visibility: visible; animation-name: fadeInUp;">Installation of Raspberry OS <i class="fa fa-angle-right"></i></a>

<a href="https://github.com/manuel83/craftbeerpi" class="btn btn-3d btn-lg wow fadeInUp btn-red animated" data-wow-delay="0.9" style="visibility: visible; animation-name: fadeInUp;">CBPi on GitHub <i class="fa fa-github"></i></a>

# Installation Video

Watch the installation video or read the installation steps below

<a href="https://asciinema.org/a/du84msz9t56yqqg6j6qfjmvjd"><img src="https://asciinema.org/a/du84msz9t56yqqg6j6qfjmvjd.png" alt="asciicast" width="60%"></a>

# <a name="pookie"></a>Commandline Installation Step by Step

## 1. Clone the Git Respository

Clone CraftBeerPI from GitHub. Open the shell on your Raspberry PI and type the following command.

```
git clone https://github.com/Manuel83/craftbeerpi.git
```

## 2. Run the Installation Script

After cloning the program to your Raspberry PI you just have to run the install.sh script. The script will guide you through the installation process.

```
cd craftbeerpi
sudo ./install.sh
```

## 3. Access the User Interface

Restart the Raspberry Pi

```
sudo reboot
```

After reboot you can access the User Interface via the following URL

```
http://<RASPBERRY-PI-IP-ADDRESSE:5000
```

> You can get the Raspberry Pi IP Address by type `ifconfig` into the command shell of your Raspberry Pi

## Optional – Automatic Start after boot

As part of the installation you will ask if you like to start CraftBeerPI after boot automatically. If you have selected this at the first installation just run the installation again and select ‘y’ when you are ask if CraftBeerPI should start after boot.

# Update CraftBeerPi

Open a command shell on your Raspberry Pi, navigate to the CraftBeerPi installation folder and pull the lastest changes

```
cd /home/pi/craftbeerpi
sudo git pull
```

# Source Code on GitHub

The source code of CraftBeerPi can be found on GitHub
