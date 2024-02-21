# Overview

This is a physical button box in the rough shape and functionality of the CDU of the Citation CJ4.
It is primarily intended for use with Microsoft Flight Simulator 2020, but could be adapted to other simulators (or planes) as well.

For more indepth information head over to: https://jwolff.it/cj4-cdu/

## Hardware 

It's constructed with a 3D printed front plate, 3D printed keys, a custom PCB and an Arduino Mega.

The CAD for the front plate, and the 3 different kinds of keys are in CAD/ folder.
The is only one key for each type. For the whole keyboard you would have to copy and modify them with the labeling.

The schematics and design files for the PCB are in the kicad/ folder.

> [!CAUTION]
> If you plan on using the PCB: __triple check the footprints__ of the buttons!
>
> The buttons I ordered had different footprints. I had manually rework all the ground wires to make it work.
> I did __not__ update the PCB.


## Software

This uses [Mobiflight](https://www.mobiflight.com) for sending the correct key events to the sim.
Make sure you have the WASM module installed and downloaded the CJ4 Preset from HubHop.

The configs file mobiflight are in the mobiflight/ folder.
