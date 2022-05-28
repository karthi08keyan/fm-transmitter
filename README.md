# fm-transmitter
Use the Raspberry Pi as an FM transmitter. Works on every Raspberry Pi board.

Just get an FM receiver, connect a 20 - 40 cm plain wire to the Raspberry Pi's GPIO4 (PIN 7 on GPIO header) to act as an antenna, and you are ready for broadcasting.

This project uses the general clock output to produce frequency modulated radio communication. It is based on an idea originally presented by Oliver Mattos and Oskar Weigl at PiFM project.
# Installation and usage
To use this software you will have to build the executable. First, install required dependencies:

# sudo apt-get update
# sudo apt-get install make build-essential
Depending on OS (eg. Ubuntu Server 20.10) installing Broadcom libraries may be also required:

sudo apt-get install libraspberrypi-dev
After installing dependencies clone this repository and use make command in order to build executable:

git clone https://github.com/markondej/fm_transmitter
cd fm_transmitter

