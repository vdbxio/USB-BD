[![piss](https://img.shields.io/badge/US000128-OSHWA-blue?style=for-the-badge)](https://certification.oshwa.org/us000128.html)


# USB-BD
A handy Micro-USB power and data breakout for breadboards and project boxes.

## Summary
The USB-BD is a small PCB and some associated parts intended to make it easier to add 5v USB power to electronics projects. Its form factor is its main feature as it is designed to fit in the power rails of a common solderless breadboard. It will even gang or bridge the two inline sets of rails on larger breadboards. Its power rail is switched by default, but can be bypassed with the solder jumper on the top. A JST 2.0 connector provides access to the data pins D+ & D-, while a solder jumper on the bottom allows for easily grounding the ID pin for OTG connections.

We provide the source here for your perusal. Feel free to ask us any questions in the issues tab above and check out the wiki for more info as we continue to work on this project. We'd love to hear your feedback on how we can make it better.

We currently sell them in 5-packs on Amazon. The Micro-USB port is soldered by us in California from imported components using a lead-free process. Included in the pack is 5x of 5.8mm Micro Latching Switch, 5x JST 2.0 Header, 5x JST 2.0 Lead, and 10x 1x2 pin headers for you to solder yourself.

## Background

By: Chloe Madison (@clomads)

I've always found myself doing electronics projects that require 5v... and specifically 5v from USB. It's always been a pain to get 5v from a USB port... the 5 pin breakouts from AliExpress and other sources are usually junk and you still have to wire back up to your power rails. The power supplies I've seen on Amazon and AliExpress are usually some large monstrosity that bridges the two paralell sides of the breadboard (why?) and require a barrel jack connector at some weird voltage.... again... why? If you're like me, you have a million Micro-USB cables laying around and the power bricks to go with them. Let's use them for making stuff. I feel like this is a product I will be using day in and day out... a new tool to make even cooler things and I hope you find it as useful as I have. 


## Files

The USB-BD is currently being developed in EasyEDA. The link below will take you to the public project where you can inspect the schematic and board layout.

[https://easyeda.com/clomads/volt_5](https://easyeda.com/clomads/volt_5)


## Version history

2023.2 (v1.4) - Working on design

v2.0 Prototype - Jan 2020 - Major redesign - Two position Micro-USB footprint, Nix JST for aligned 2.54mm pins for data, Simpler switch

v1.0a/v1.1 - Changed footprint to LCSC USB port and made slight modifications to the silk layer.

v1.0 - Initial release - First batch with short horn USB port from AliExpress


## Changelog

Jan 2023 
- Posted final v1.1 stock to Tindie and updated resources.
- Started research on v1.4 changes and JLCPCB assembly pricing
- Pushing off v2.0 version with dual position port
  - Keep switch replacement and new data alignment

