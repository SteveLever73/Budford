# Budford
Budford: Budford: Cemu configuration, settings and auto update tool. 

Automates updating, installation and configuratiion of Cemu and allows all options to be configured on a per game basis.

![usage](https://raw.githubusercontent.com/SteveLeafo/Budford/master/docs/ready_to_go.png)


## Why?

[Cemu](http://cemu.info/) is a great emulator.  But it currently only has limited support for per game settings. How many times have you turned on multi-core support for Breath of the Wild then forgotten to set it back to single core before playing Mario Kart with your friends. And we all know how frustring it can be when a new release arrives and your favorite game no longer works.

Budford is a configuration management tool for [Cemu](http://cemu.info/) with a familiar interface for those who have used the Dophin emulator.  

Budford is not a game launcher, it is designed to work with your favorite game launcher.

## Features?

- Simple user interface for configuring per game settings.
- Budford can support multiple users each with their own save file for each game.
- Supports multiple concurrent versions of [Cemu](http://cemu.info/).  Budford will create a symbolic link to your mlc01\usr\title folder.
- Can download the latest version of [Cemu](http://cemu.info/) , [Cemu hook](https://sshnuke.net/cemuhook/) and performs all the required setup for you.
- Can automatically download the latest graphic packs.
- Budford can integrate with your favorite game launcher such as launch box or emulation station, it can even launch straight into the game pad view so you'll never need your keyboard again.
- Global settings for audio volume and your preferred graphic pack resolution. (You can override these in your per game settings)
- Game ratings and view filters to help you find your favorite games.
- Track statistics such as the number of times you have played each game or how long since you last played it.
- Easy access short cuts to important Cemu folders such as Shader Cache, Save Folders and Game files.  No more searching through log files to find folder names.

## How to use it?

Download and install the latest version of Budford [here](https://github.com/SteveLeafo/Budford/tree/master/Install).

Open the configuration form and set the folder that contains the games you ripped from your Wii U

From the menu select Cemu | Manage Installed Versions. In installed versions form set your default install folder and hit the scan button.  Budford will find Cemu.  Click the Repair all button and your a ready to play.

Alternatively, if you haven't used Cemu before, select Cemu | Download Latest Cemu

Once you have Cemu setup and running, double click a game to play it.

To change a games Cemu settings, right click on the game and select Properties.

## Tip

Budford also comes with an automatic shader cache updator.  New version of Cemu?  New graphics drivers?  Tired of watching progress bars when you want to be playing your favorite game?
Run the automatic shader cache updator and come back later and all you precompiled shaders will be up to date.

## Credit

Thanks to "ling wing" for your help with testing and feature requests and for introducing me to [Cemu](http://cemu.info/).

## License

Mozilla Public License Version 2.0