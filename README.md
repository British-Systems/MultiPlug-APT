Debian Package Repository for the [MultiPlug .Net Edge Computing Platform](https://www.multiplug.app)

# MultiPlug Debian Linux Installation
## Option 1 - Install with Repository Updates
A Linux package repository is available for Debian-based Linux versions, this includes Raspberry Pi OS.

1. To add MultiPlug Debian Repository to your instance of Linux, Add the following line to /etc/apt/sources.list (Only need to do this once):
2. `deb [trusted=yes] https://apt.multiplug.app ./`
3. Run the following command to fetch the latest package list:
4. `sudo apt update`
5. To install MultiPlug run the following command:
6. `sudo apt-get install multiplug`

Multiplug will start and also on each system startup, to access it use a web browser and IP address of the device. There are Windows and Andriod network discovery apps available.
More information on the [Wiki.](https://github.com/British-Systems/MultiPlug/wiki)

## Option 2 - One Time Install
Manually download the .deb file and install once.

1. Download the debian package by running the following command:
2. `curl –O https://apt.multiplug.app/multiplug.deb`
3. Install the pack by running the following command:
4. `sudo apt install ./multiplug.deb`

Multiplug will start and also on each system startup, to access it use a web browser and IP address of the device. There are Windows and Andriod network discovery apps available.
More information on the [Wiki.](https://github.com/British-Systems/MultiPlug/wiki)
