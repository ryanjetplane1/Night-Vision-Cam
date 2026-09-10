# Night Vision Cam

A drone camera converted into a night vision goggle setup, built around a Meteor85 Pro drone core.

## Overview

This project turns an FPV drone camera into a night vision module that connects to drone goggles. The IR-cut filter is removed from the camera to let it see in IR light, and the board is rehoused in a custom 3D printed case with active cooling to keep it from overheating.

**Features**

- IR filter removed for night vision
- Camera based on the Meteor85 Pro drone board
- Heat sink and fan cooling
- Custom case with holes for airflow
- Screw holes and a quick mounting systems

## How To Build

Take a meteor 85 drone and disassemble removing all parts besides the transmitter board and camera. Then get a new camera such as the one linked in the BOM. After remove the IR filter and swap it with the old one. Once your done strip some wire off the battery cables, solder your positive to blue and negative to gnd, and screw in your fan.


## Bill of Materials

| Component | Description | Qty | Link |
| --- | --- | --- | --- |
| Caddx Ant 1200TVL FPV Camera | 1.8mm lens, NTSC/PAL, WDR | 1 | [Buy](https://www.amazon.com/dp/B0DZJTMPHS) |
| 3007 30x30x7mm Fan | 3.3V/5V DC cooling fan | 1 | [Buy](https://www.amazon.com/dp/B07G97L9TL) |
| 850nm IR Torch | 3W infrared illuminator | 1 | [Buy](https://www.amazon.com/dp/B016ZPH470) |

## Files

| File | Description |
| --- | --- |
| `casetop.stl` | STL for the top half of the case |
| `casebottom.stl` | STL for the bottom half of the case |
| `nvgcase.f3d` | Source file for the case |

## Demo

[Build demo video](https://www.youtube.com/watch?v=HGBvn858_r4)
