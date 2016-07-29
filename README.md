# MegaWiFi
WiFi enabled cartridge for the 16-bit SEGA Genesis/MegaDrive console.

# What's in this repo?
This repository consists of a compilation of subprojects related to the MegaWiFi cartridge, along with some additional documentation. The subprojects are added as submodules, so make sure you clone the repository with `-r` switch if you want them all.

## Sources
You will find several source submodules under the `src` directory:
- Programmer bootloader: https://github.com/doragasu/mw-mdma-bl
- Programmer command-line interface: https://github.com/doragasu/mw-mdma-cli
- Programmer firmware: https://github.com/doragasu/mw-mdma-fw
- WiFi module firmware: https://github.com/doragasu/mw-fw-rtos
- MegaWiFi API for game/application development: https://github.com/doragasu/mw-api

## Documentation
Documentation is located at the `doc` directory.

# Status
Please have in mind this is work in progress. Right now you can send/receive data using TCP sockets, but most of the additional planned functions are still unimplemented.

# Authors
Most of the code and docs you will find here are written by doragasu, with some help from Migue/Manveru. Please check each submodule for additional documentation.

# Contributions
Contributions are welcome. Right now I need help specially with two topics:
- Games: If you are a Megadrive game developer, please consider adding online functions using MegaWiFi.
- Emulator support: To ease creating games, it would be desirable to add MegaWiFi support to emulators. If you are brave enough to give it a try, I'll help you as much as I can.

Also if you want to report bugs or add features, please open the issue or send the pull request to the corresponding submodule.
