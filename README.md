# WARNING: THIS PROJECT HAS MOVED

You can find the most recent version at the [mw GitLab project page](https://gitlab.com/doragasu/mw). This repository will be kept as is, and will not be updated anymore.

# MegaWiFi
WiFi enabled cartridge for the 16-bit SEGA Genesis/MegaDrive console.

# What's in this repo?
This repository consists of a compilation of subprojects related to the MegaWiFi cartridge, along with some additional documentation. The subprojects are added as submodules, so make sure you clone the repository with `-r` switch if you want them all.

## Sources
You will find several source submodules under the `src` and `sch` directories:

* MegaWiFi API for game/application development: https://github.com/doragasu/mw-api
* Wireless loader ROM for Megadrive: https://github.com/doragasu/mw-wflash
* Wireless loader client for PC: https://github.com/doragasu/mw-wf-cli
* Simple Telegram bot API implementation and example: https://gitlab.com/doragasu/mw-tgbot
* Cartridge schematics: https://github.com/doragasu/mw-cart
* Programmer schematics: https://github.com/doragasu/mw-prog
* Programmer bootloader: https://github.com/doragasu/mw-mdma-bl
* Programmer command-line interface: https://github.com/doragasu/mw-mdma-cli
* Programmer firmware: https://github.com/doragasu/mw-mdma-fw
* WiFi module firmware: https://github.com/doragasu/mw-fw-rtos

As you can see, there are a lot of submodules here, and it can happen I forget to update their references, so you can pull from the submodule repositories themselves, to make sure you have up to date code.

## Documentation
Documentation about the complete project is located at the `doc` directory. The latest API documentation for Megadrive developers [is located here](https://doragasu.github.io/mw-api/doc/html/index.html).

I take documentation seriously, and you will find thorough documentation about almost every aspect of the project, specially about the API for Megadrive developers.

# Status
Megadrive firmware and API have reached version 1.0 and API is considered stable and most of the initially planned features are supported.

# Authors
Most of the code and docs you will find here are written by doragasu, with some help from Migue/Manveru for the programmer client USB API. Please check each submodule for additional documentation.

# Contributions
Contributions are welcome. Right now I need help specially with two topics:

* Games: If you are a Megadrive game developer, please consider adding online functions using MegaWiFi.
* Emulator support: To ease creating games, it would be desirable to add MegaWiFi support to emulators. Currently BlastEm! has supports some API calls, but it still not mature enough to be useful.

Also if you want to report bugs or add features, please open the issue or send the pull request to the corresponding submodule.
