# Robotcrafts

[![license](https://img.shields.io/github/license/mashape/apistatus.svg?maxAge=2592000)](https://github.com/joshuagruenstein/Robotcrafts/blob/master/LICENSE)

Robotcrafts (working title) is a low cost "arts &amp; crafts" style kit for remote control robots.  The first prototype was created in the summer of 2015 for a robotics elective at [Camp Good Grief](https://www.eeh.org/bereavement/camp-good-grief/) at [East End Hospice](https://www.eeh.org/) in Southold, NY.  This repository covers all future versions of this concept, from 2016 onwards.

## Concept

The kit is comprised of a controller, motors, wheels, and standard arts &amp; crafts materials such as foamcore, double sided tape, and popsicle sticks.  The controller is a dual layer PCB with four pushbuttons, three AA batteries, and copper pads to attach the motor wires via alligator clips.   The motors are given to the children with 5ft of twisted leads attached to them, terminated with alligator clips.  All the kids have to do is clip the alligator clips onto the controller, allowing them to use the buttons to move the motors forwards and backwards.  

This design gives kids the freedom to experiment with different robot designs using existing arts and crafts skills, as it removes the challenge of wiring up a robot.  However, the electronics are still both simple enough to understand and cheap enough to give a robot per child: the goal is to price each kit at ~$10.  While this may not be economically feasible for every application, it's obviously still ideal to get kits such as these in the hands of as many kids as possible.

## Implementation

The current implementation uses a Toshiba TB6612FNG dual brushed motor controller and Dagu gearmotors and wheels.  The controller PCB is in EagleCAD, which while not being free software seems to be the standard over KiCAD for hobbyists, making it more "open" to the community.  These parts were chosen for their low price at the required scale.

An issue with the current implementation is ease of manufacturing: the process of soldering leads to the motors, applying hot glue for strain relief, attaching alligator clips, and soldering DIP and SMD parts to the PCB is quite laborious, especially in large quantities.  Last summer I spent a full day assembling ~25 kits of lesser complexity.  I'm not quite sure what to do about this at the moment except to allot more time for assembly, so if you have an idea please submit an issue or pull request.

## Photos

Below are some fun pictures of some of the robots kids at Camp Good Grief made last summer:

![Robot Picture with Controller](http://i.imgur.com/I715E4O.jpg)

![Heart Robot Picture](http://i.imgur.com/2AM3DuO.jpg)

![Kitty Robot Picture](http://i.imgur.com/Op72Ixa.jpg)

![Popsicle Robot Picture](http://i.imgur.com/rjnE0jM.jpg)

## Contributing

Please feel free to contribute, whether it be to suggest a feature or design change, update a schematic, or add pictures of a robot you've made!  Just submit either an issue or a pull request.

[![Author](http://wsbadge.herokuapp.com/badge/Author-Joshua_Gruenstein-red.svg)](https://github.com/joshuagruenstein)
