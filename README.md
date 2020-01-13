# rak_common_for_gateway

##	Introduction 

The aim of this project is to help users set up a LoRa network easily.

##	Supported platforms

This project currently provides support for the below platforms.
* RAK7246

##	Changelog
2019-12-17 V4.1.1
* Init.

##	Installation procedure

step1 : Download and install [Raspbian Stretch or Buster LITE](https://www.raspberrypi.org/downloads/raspbian/) 

step2 : Use "sudo raspi-config" command, enable spi interface.

step3 : Clone the installer and start the installation.

      $ sudo apt update; sudo apt install git -y
      $ git clone https://github.com/RAKWireless/rak7246_for_rpi.git ~/rak7246_for_rpi
      $ cd ~/rak7246_for_rpi
      $ sudo ./install.sh

step4: Wait a moment and the installation is complete

step5 : For more other features, please use "sudo gateway-config".
