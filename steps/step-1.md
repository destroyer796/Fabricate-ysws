# Step 1: Feature Selection
### Choose your motion system, build size, and features.

In this program, we are going to walk you through the process of designing and building an FDM(Fused Deposition Manufacturing) 3D printer. FDM printers are amazing machines, and they may seem very intimidating at first, but they can quite easily be broken down into a few simple parts. You have:
- Some way of extruding melted plastic (Extruder + Hotend)
- Some way of moving around either that melted string of plastic, or the surface it's printing on (Gantry + Buildplate)
- And some way to control the parts above (Mainboard + Stepper Motors)

Not so intimdating now, right? The main problem we face is this; it's quite easy to make a machine that can do these things, but its quite hard to design one that can do them *well*. This guide will help you make sense of how to best go about designing a 3D printer, so you end up with a machine that you'll actually *want* to use.


## Brainstorming:
The first thing you should do is lay out your goals for the project. Ask yourself,
- What build size do you want?
- What kind of speeds do you want to reach?
- Do you want an enclosure?
- What extra features do you want?

The answers to these questions will help you make the right choices later by starting with a plan in mind.

## Motion System:
There's many different ways to get your printer moving, here's some examples:
- Cartesian (Bed-slinger)
- Core-xy
- Delta
- Cross Gantry
- Belt Printers
- Polar Bed
- Core-xyz
- Multi-axis bedslinger
- 4/5 Axis Machines
- And many more!

The most common motion systems are cartesian and core-xy, with bed slingers being the simplist. I encourage you to look further into whatever motion systems interest you, and to challenge yourself! After all, where's the fun in making yet another Ender 3 clone?

## Build Size:
This is one of those variables that might be changed a bit as you design, it's good to start out with a target build size in mind but don't be afraid to let this change with time! Build sizes are usually described in the xyz format in milimeters. 200-300mm^3 is usually the sweet spot, but if you have unique needs, go for it!

## Features:
What's a 3D printer without features? This is where you can make your printer truly unique, try to make you printer extra portable, make it print a new material, make it easier to use, or just make it cool! Here's a few ideas for features:
- Extra axis
- Conveyer belt
- Bed probe for easy first layers
- Bed tilt
- Enclosure
- Chocolate Extruder
- Toolchanger!
- Make it fit inside a filament box
- Run off USB power
- Printer the loooooooong way

You can even get some extra rewards for including cool features, check out the rewards section!