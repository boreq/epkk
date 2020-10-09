# epkk

An open source Microsoft Flight Simulator scenery for John Paul II International Airport Kraków-Balice.

## Installation

1. Download the [latest release](https://github.com/boreq/epkk/releases).
2. Unpack the downloaded `.zip` file and place the resulting directory (containing files such as `manifest.json`) in your `Community` directory.

### For the Microsoft Store edition AND/OR Gamepass edition

    C:\Users\[YOUR USERNAME]\AppData\Local\Packages\Microsoft.FlightSimulator_<RANDOMLETTERS>\LocalCache\Packages\Community

### For the Steam edition

    C:\Users\[YOUR USERNAME]\AppData\Roaming\Microsoft Flight Simulator\Packages\Community

### For the Boxed edition

    C:\Users\[YOUR USERNAME]\AppData\Local\MSFSPackages\Community

### If the above methods do not work

You can find your community folder by going into FS2020 general options and enabling developer mode. You will see a menu appear on top. Go to tools and virtual file system. Click on watch bases and your community folder will be listed in one of the folders.

Please make sure you're copying the unpacked directory which contains the file `manifest.json` into your `Community` directory and the directory is not nested in another directory.

If your simulator was running during installation then a new package will only be available after restarting it.

## Updating the package

In order to update the package it is first recommended to close your simulator as it may stop you from removing some of the package files. After doing so remove the previous version of the package and then follow the installation instructions to install the latest version. If the simulator was running during this processes it has to be restarted for the new version of the package to be available.
