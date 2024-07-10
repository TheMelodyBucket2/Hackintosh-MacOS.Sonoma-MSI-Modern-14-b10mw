Brief guide for Hackintoshing MSI Modern 14 b10mw (Intel® Core™ i3/i5/i7 10th Generation/ comet lake) Models. (Forked from my original repo)

## WARNING
Testing out something experimental may cause your device lagging/ battery draining problems/ excessive heating/ dead devices or other hardware issues. Test at your own risk.

Use Opencore Configurator (OCC) to add ROM, MLB and Serial to config.plist.
See [mackie100Projects](https://mackie100projects.altervista.org/download-opencore-configurator) to download OCC and [Dortania guides](https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html) for help.

- *~A Backlit issue have been addressed and using an external monitor is advised.~* a fix has been released but still there's a chance that display might not work as expected.
## Support/ Feedback

For support and feedback, [send an email](sithumkottearachchi@outlook.com)


## Features (Working)

- Sound
- keyboard with keyboard brightness adjustment.
- Webcam and Mic (no spatial audio support or animated reactions on calls)
- Display (Found issues with backlit, strict attention advised until a fix is being released)
- Brightness/ Sound shortcut keys in function key row.
- Wifi (99% Working, try a restart if doesn't work)
- Bluetooth (Might misbehave)
- All USB 2 ports (right hand side)
- 3.5mm headphone/mic combo jack.
- USB 3.2 Thunderbolt port.
- Card reader.
- HDMI out.
- Sleep/ Wake up (might restart automatically after putting into sleep)
- Charging and all other basic functionalities.

## Features (Not working)/ Issues
Working on fixes for all issues. But don't keep high hopes.
- ~Backlight may be delayed to hit on. Use an external monitor until a fix is released.~ A fix has been released but still buggy.
- Airdrop.
- iMessages and Facetime (Working on a fix, do not try to log in as your apple ID could be flagged as a bot)
- Fans (are working but working on higher demand applications may cause overheating as fans cannot exceed their speed more than around 1500rpm. Working on a fix)
- Lossless playback on Apple Music.
- Some hardware accelerated decoding (it's a hardware limitation so no fixes)
## Documentation

[Check out the Dortania's guide for using Opencore config](https://dortania.github.io/OpenCore-Install-Guide/) 

For additional support, check out [tonymacx86](https://www.tonymacx86.com/)
## Installation
According to your need, use the whole EFI file with all it's content after extracting compressed zip files. ( for upgrading from a lower MacOS version to MacOS Sonoma or installing a fresh MacOS Sonoma copy ). Do some research before testing.

## Credits
[Apple](https://www.apple.com/) for MacOS.

[Dortania](https://github.com/dortania) for guides and help.

[OpenIntelWireless](https://openintelwireless.github.io/) for WiFi and Bluetooth kexts.

[Acidenthera](https://github.com/acidanthera) for Lilu, VirtualSMC, OpencorePKG, AppleALC, and WhateverGreen kexts. 
