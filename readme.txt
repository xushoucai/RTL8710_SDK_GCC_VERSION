###########################################################################################
###########################################################################################
####################RTL8710_GCC_VERSION_V1.0.0#############################################
###########################################################################################
GCC SDK RTL8710 basic version (including the window platform cygwin installation and Ubuntu platform Linux Installation routines), 
including cross compilation of the installation, compile, link, run, debug, and so on.
SDK implementation of the function:
1, WiFi connection settings (including AP mode and STA mode).
2, peripheral resource control (including GPIO, SPI, UART, IIC, etc.).
3, the user uses the sample method.

SDK directory is as follows, please first read the document:
UM0096 Realtek Ameba-1 build environment setup - gcc.pdf
├── component 
│   ├── common
│   │   ├── api
│   │   ├── application
│   │   ├── drivers
│   │   ├── example
│   │   ├── file_system
│   │   ├── mbed
│   │   ├── network
│   │   ├── test
│   │   └── utilities
│   ├── os
│   │   ├── freertos
│   │   └── os_dep
│   └── soc
│       └── realtek
├── doc
│   ├── AN0004 Realtek low power wi-fi mp user guide.pdf
│   ├── AN0011 Realtek wlan simple configuration.pdf
│   ├── AN0012 Realtek secure socket layer(ssl).pdf
│   ├── AN0025 Realtek at command.pdf
│   ├── AN0033 Realtek Ameba-1 over the air firmware update.pdf
│   ├── AN0038 Realtek googlenest user guide.pdf
│   ├── AN0043 Realtek mdns user guide.pdf
│   ├── AN0045 Realtek Ameba-1 power modes.pdf
│   ├── AN0046 Realtek Ameba uart adapter.pdf
│   ├── AN0049 Realtek Ameba WiGadget iot demo kit application note.pdf
│   ├── AN0075 Realtek Ameba-1 at command v2.0.pdf
│   ├── UM0006 Realtek wificonf application programming interface.pdf
│   ├── UM0014 Realtek web server user guide.pdf
│   ├── UM0023 Realtek Ameba-1 build environment setup - iar.pdf
│   ├── UM0027 Realtek Ameba-1 crypto engine.pdf
│   ├── UM0034 Realtek Ameba-1 memory layout.pdf
│   ├── UM0039 Realtek Ameba-1 SDK quick start.pdf
│   └── UM0096 Realtek Ameba-1 build environment setup - gcc.pdf
├── project
│   └── realtek_ameba1_va0_example
│       ├── example_sources
│       ├── GCC-RELEASE
│       ├── inc
│       └── src
├── release_note.txt
└── tools
    ├── arm-none-eabi-gcc
    │   ├── 4.8.3-2014q1
    │   ├── 4.8.3-2014q1.tar.gz
    │   └── gcc-arm-none-eabi-4_8-2014q1-20140314-linux.tar.bz2
    ├── autopatch
    │   └── auto_patch.bat
    ├── DownloadServer
    │   ├── DownloadServer.exe
    │   ├── readme.txt
    │   └── start.bat
    ├── file_check_sum
    │   └── file_checksum.c
    ├── iperf.exe
    ├── serial_to_usb
    │   └── mbedWinSerial_16466.zip
    ├── simple_config_wizard
    │   ├── Android
    │   └── iOS
    ├── simple_config_wizard_3.4b
    │   ├── Android
    │   └── iOS
    ├── uart_adapter
    │   └── app
    └── wigadget
        ├── Android
        └── iOS
