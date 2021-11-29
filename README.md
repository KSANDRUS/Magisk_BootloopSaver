# Magisk BootloopSaver


**This repo has migrated to [Magisk Alternative Repo](https://github.com/Magisk-Modules-Alt-Repo/HuskyDG_BootloopSaver)**   

## About
Protect your system from bootloop caused by Magisk modules. In case the data partition is encrypted and you cannot access `/data/adb/modules`, or you don't want to turn off **force encription** because when your phone with **force encryption** disabled is stolen, thief can copy your `/data` and your private data will be exposed!!! 

## Requirements
- Magisk 20.4+ is installed

## Installation
It's Magisk module, flash it in **Magisk** app

## Usage

After flashing this module, you don't need to do anything manually. This module will do their jobs: detect if you got bootloop (zygote keeps restarting many time) or not

If yes, disable all modules and restart the system.

Without this module, there is another way to disable all modules is to boot into Safe mode and then reboot back!

## License

```
This module is free-license.
You can use and modify it as your own!
```
