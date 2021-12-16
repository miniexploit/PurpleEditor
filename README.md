<br />
<p align="center">
  <a href="https://github.com/j4nf4b3l/MagicClock">
    <img src="image/purple.png" alt="Logo" width="120" height="120">
  </a>

  <h3 align="center">PurpleEditor</h3>
  <h3 align="center">Syscfg editing utility</h3>


## About PurpleEditor
![](image/image.png)

PurpleEditor is a utility to read/write Syscfg of  devices.
Features:
* Read/write device's serial number.
* Read/write device's Wifi Mac.
* Read/write device's Bluetooth Mac.
* Permanent iCloud unlocking on older  devices (excluding iPhone).
## Download
* PurpleEditor can be downloaded from [here](https://github.com/Mini-Exploit/PurpleEditor/releases/)
## Getting started
1. Enter Diags mode.
2. Connect your iDevice to your computer using a DCSD cable.
3. In PurpleEditor, click Refresh.
4. Now click on the popup button, choose your port there (usually it's usbmodem-xxx or usbmodemxxx).
5. Click Connect.
6. Click Read Syscfg. Now, Syscfg including serial number, Wifi Mac, Bluetooth Mac will appear in the text field. If you want to edit them, just click on the text field and change those information, then click Apply.
7. After you have done with those stuffs, click Reboot. Your device will reboot now.

NOTE: A restore is neccessary for those changes to take effect.
## Advantages/Disadvantages
* Advantage: PurpleEditor's size is only ~1.4MB, so don't worry it will take much space on your computer :)
* Disadvantage: Limited reading/writing syscfg
- PurpleEditor only reads/writes neccessary syscfg information for iCloud Unlocking. If you wish to edit more syscfg information, please consider using [MagicCFG](https://github.com/j4nf4b3l/magicCFG) instead.
## Bug Report
Report bug by opening an issue [here](https://github.com/Mini-Exploit/PurpleEditor/issues)
.Please make sure you have checked [opened issues](https://github.com/Mini-Exploit/PurpleEditor/issues) before opening your own issue as those opend issues may have already included your problems
## Donation
Currently this software does not ask for donations. If you enjoy this software, please give this repository a star, that's the biggest donation you can give me :)
## Credits
* [Jan Fabel](http://github.com/j4nf4b3l) for [MagicCFG](http://github.com/j4nf4b3l)
* [Andrew Madsen](https://github.com/armadsen) for [ORSSerialPort](https://github.com/armadsen/ORSSerialPort)
