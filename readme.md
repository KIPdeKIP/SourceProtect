# AdBlock & Protection for TF2

## Message from CasualX

*September 11th, 2012*

Hello, since recently an exploit was discovered to execute arbitrary commands on clients (fixed in yesterday's update) I decided to see what could be done about this with purely cfg scripts to protect against this.

## Features

*	Blocks Pinion MOTD adverts and other advertisements.
*	Prevents servers from playing sounds and showing overlays on the client.
*	Server are no longer allowed to execute commands on the client they don't need access to.

## Download

Download from the Github repository [here](https://github.com/KIPdeKIP/SourceProtect/archive/master.zip) or from the [releases tab](https://github.com/KIPdeKIP/SourceProtect/releases).

## Installation

Extract the cfg files to

    C:\Program Files (x86)\Steam\steamapps\common\Team Fortress 2\tf\cfg

or a similar folder in your configuration.

Ensure you have a file with the name `autoexec.cfg` in this directory. If you have no such file, create it and make sure it has the `.cfg` file extension. Add a new line at the bottom of your `autoexec.cfg` file with the text

    exec protect.cfg

or use one of the other more lightweight cfgs. Save the file when you are done.

# Use

Make sure to read the contents of [`protect.cfg`](https://github.com/KIPdeKIP/SourceProtect/blob/master/protect.cfg) and change any settings to fit your needs.
