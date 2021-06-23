**English** | [中文](READMD_CN.md)
# Taps
This plugin is not self-made, but modified from [PerimeterMaker](https://github.com/Ivan-1F/MCDReforged-Plugins/tree/master/PerimeterMaker)  
I've fixed the bug of water flowing while manufacturing perimeter  

---

Create perimeters in creative/mirror servers, operate layer by layer to avoid lags.

## Attention

Requires [Carpet Mod](https://github.com/gnembon/fabric-carpet) to override fill limit.

## Install

Drag `PerimeterMaker.py` to `/plugins` folder

## Useage

 - `!!perimeter help` show help messgae
 - `!!perimeter make <length> <width>` make a perimeter here
 - `!!perimeter commit` use after make, commit the operation
 - `!!perimeter abort` abort the operation at any time

## Constants can Modify

### DELAY

Defult value：`DELAY = 1`

The delay after the layer operation, change it by the performance of the server

---
