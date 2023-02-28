# ***SmartAutoGear***

Smart 451 Automatic Gear Control

An esp32 to control  the Gearbox on the smart 451... all on obd2 port

Version 0.1.0 beta

Starting point:

- 2 maps Eco and sport;

- dynamic use of accelerator pedal;

- different type of gear down: pedal0 , brake, gearbox signal for up down gear.

- Visualization of data on TTGO TFT Screen

- Bluetooth app to control .

- Direct use in obd2 port

Working:

- map Eco

- map Sport

- control of palette to enable a suspend mode

- bluetooth app

- all the gearbox down system

- visualization on TTGO TFT panel

- dynamic use of accelerator pedal

Todo:

- Box

This is the schematics, you can use it with Savvycan to do a very smart sniffer for every obd2 port working on  ISO15765-4 (CAN-BUS) but maybe can work on other protocol.

You must have my modified version of esp32ret to compile and upload on esp32

<img title="Scheme" src="https://github.com/jpnos26/SmartAutoGear/blob/main/Image/Schematics.png" alt="" width="674">

and off course is the schematcs of our peoject.... double use.

This is the pcb

<img title="Explain" src="https://github.com/jpnos26/SmartAutoGear/blob/main/Image/explain.png" alt="" width="674">

This is data on TTGO TFT

<img title="" src="file:///home/athos/snap/marktext/9/.config/marktext/images/2023-02-27-08-34-28-explain.png" alt="" width="674">

I hacked a lot of data on smart canbus..... not only used in this project.
