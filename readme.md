# Retro road 2: The Physical Racer

*Can you beat the track?*

## What is it?

RR2TPR is a unity game remade to work with a custom-built physical controller. I originally made this game in college (see sources for original release)
with a team of 4 others - When I found out that I would be creating a physical
controller in University for my COMP140 module I decided to make a sequel of sorts
and this is what I came up with. There are various improvements to the codebase, engine work, and performance throughout the entire project.``

## How to play

To play the game, you don't *need* to have the custom controller, as keyboard and mouse support have been added. Although the controller is a bespoke item, modeled, printed and wired by me the section below will expand on how you can go about creating your own, and what you will need to do so. **You can download the build of RR2TPR [HERE](https://mattrobertscgd.itch.io/)**


## Creating your own controller

In order to create your own RR2 controller, you will need to be able to 3D print the parts, or source them somewhere else. There are multiple websites available for this and [this](https://all3dp.com/1/best-online-3d-printing-service-3d-print-services/) would be a good place to start looking.

As a general guide to the print settings here's what I would recommend:
- 20-30% infill for all parts
- Supports enabled. **NOTE: The wheel was modeled to be hollow. I wasn't the author of it, and I found it on [Thingiverse](https://www.thingiverse.com/), please check the sources section for a direct link**
- 0.2 Layer height. This is more down to personal preference but most of the parts are modeled with a friction fit level of tolerance and at higher layer height you may struggle even more than what I did. Anywhere between .1 and .4 is what I tested.

If you know your printer though, this part shouldn't be a problem.

After printing the models provided in the repo next comes wiring and hardware. Here's a list of materials, some things like wires are approximated:

1x Arduino Uno

3x 10k Potentiometers

4x Momentary buttons

1x Solderless breadboard

4x Springs

Some 2-part epoxy

Some Hot glue

A bundle of wires, I used ones designed for 

breadboard use.

Some suction cups

And lots of time...

## How to assemble:

**(COMING SOON)**

## Sources, Resources & References

- Elegoo, lightly referenced their MEGA2560 documentation and tutorials at the start of the project, which can be found [here](https://www.manualslib.com/manual/1353374/Elegoo-Mega2560.html#manual)

- Steering wheel model, made by Isapozhnik [here](https://www.thingiverse.com/thing:13534)

- The [Uduino unity package](https://marcteyssier.com/uduino/) and [documentation](https://marcteyssier.com/uduino/docs)

- The bright minds of the lecturers and techs at the Games Academy. Without their help, the codebase would still have a few issues and my sanity would be much worse.

## License (where applicable)
[MIT](https://choosealicense.com/licenses/mit/)