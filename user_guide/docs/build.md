---
title: Kit build guide
---

# Micronova kit build guide

[TOC]


## Before you build

Welcome to the build guide for Micronova's DIY kit. We hope you have a great time putting your Micronova together and a wonderful time using it.

Please **read all instructions** thoroughly before starting. If you have questions or run into trouble please reach out to us on [discord] or drop us an email at support@winterbloom.com.

Some soldering experience is helpful but not required. If it's your first time soldering we recommend reading through [Adafruit's guide to excellent soldering](https://learn.adafruit.com/adafruit-guide-excellent-soldering).

This build takes around **one hour** to complete.

[discord]: https://discord.gg/UpfqghQ

## Tools and materials required

Before jumping in, make sure you have:

* Safety glasses. Yes, really.
* Proper ventilation- at least open a window or two.
* A soldering iron, like [this one](https://www.adafruit.com/product/180).
* Solder, we can recommend [Adafruit's 60/40 **no-clean** rosin core solder](https://www.adafruit.com/product/145). We suggest using soldering with "no clean" flux. If you do use a different kind of flux, be sure to carefully clean the flux residue off based on the guidelines provided by the manufacturer of your solder.


## Kit contents

Your kit should contain the following items. If any are missing please email us at support@winterbloom.com.

<object
    alt="Kit contents"
    data-is-svg-map
    data-list="kit-contents-img-datalist"
    data-stylesheet="/styles/kit-contents-svgmap.css"
    data-info-text-template="kit-contents-img-info-text"
    data="../images/kit.svg"
    height="100%"
    id="kit-contents-img"
    type="image/svg+xml"
    width="100%">
</object>
<template id="kit-contents-img-info-text">
    <g id="info-text-container">
        <rect data-size-to="info-text"></rect>
        <text id="info-text"></text>
    </g>
</template>
<datalist id="kit-contents-img-datalist">
    <option value="mainboard">Mainboard</option>
    <option value="panel">Front panel</option>
    <option value="jacks">1/8" jacks (16)</option>
    <option value="nuts">Hex nuts for the 1/8" jacks (16)</option>
    <option value="power-header">Eurorack power header (1)</option>
    <option value="power-cable">Eurorack power cable (1)</option>
    <option value="screws">M3x6 screws (2)</option>
    <option value="rubber-bands">Rubber bands (2)</option>
</datalist>
<script type="module" src="/scripts/svgmap.js"></script>
<link rel="stylesheet" href="/styles/svgmap.css"/>

- (1) Mainboard
- (2) DC barrel jacks
- (5) 2-pin screw terminal blocks
- (2) 2x8 pin shielded IDC headers
- (2) 12V DC-DC converters
- (1) 5V DC-DC converter

## Soldering the screw terminals

The first step is placing and soldering the five 2-pin screw terminal blocks.

While it's faster to solder them all the blocks at the same time, it's much easier to do one at a time. Place a terminal block on the front side of the board, taking care to place it so that the terminal openings face *outward* and match up with the triangles on the board.

Hold the terminal block in place and flip the board over. It's okay if the terminal block isn't completely flush against the board, as long as the legs are through the holes.

Solder one leg of the terminal block to hold it in place.

Lift the board and use your iron to reflow the solder and push the terminal block flush against the board. Wait a few seconds for the joint to solidify before releasing the board.

With the terminal block now flush against the board, solder the second leg into place.

Repeat this process for the four remaining terminal blocks, taking care to align the terminal openings.


## Soldering the IDC headers

Your next task is placing and soldering the two 2x8 pin shielded IDC headers.

Place them on the front side of the board, being careful to align the notch in the header's shield with the drawing on the board. The board is designed to hold on to these headers tightly, so you might have to give a little pressure to push them all the way in.

Once you have both placed, flip the board over. Make sure the headers are still completely flush against the board and solder all 16 pins on both headers. You should be able to do them both at the same time, but if you're having trouble feel free to do them one at a time like you did with the terminal blocks.


## Soldering the DC barrel jacks

Next up is placing and soldering the two DC barrel jacks.

Similar to the terminal blocks, it's easiest to place these one at a time. Place one on the front side.

Then carefully flip the board over and solder one leg to hold the barrel jack in place.

Lift the board and use your iron to reflow the solder and push the barrel jack flush against the board. Wait a few seconds for the joint to solidify before releasing the board.

With the barrel jack flush and held in place, solder the remaining two legs.

Repeat this process for the second barrel jack.


## Placing the DC-DC converters

The last step is to solder the three DC-DC converters.

There are two 12V converters and one 5V converter. You'll need to identify them before placing them.

The two 12V converters are slightly larger and has `K7812M-100R3` marked on it.

The single 5V converter is slightly smaller and has `VX7805-500` marked on it.

Start by placing the 5V converter on the front side of the board.

Carefully flip the board over and solder one leg to hold the converter in place.

Using the same technique as the DC barrel jacks and terminal blocks, reflow the solder and push the DC-DC converter flush against the board.

Once the DC-DC converter is flush, solder the remaining legs.

Repeat for the two 12V converters.


## Busboard

The busboard kit adds six additional power headers to your Micronova.

Your busboard kit should contain the following items. If any are missing please email us at support@winterbloom.com.

- (1) Busboard PCB
- (7) 2x8 pin shielded IDC headers
- (1) 16 pin to 16 pin IDC cable (not pictured)

Assembling the busboard kit is fairly straightforward. Start by placing all seven IDC headers on the front side of the board, making sure to align the notch in the header's shield with the drawing on the board. The board is designed to hold on to these headers tightly, so you might have to give a little pressure to push them all the way in.

Flip the board over, make sure that the headers are all still flush against the board, and solder them all in to place.

That's it!


## Front entry kit

The front entry kit lets you power your Micronova via a 4hp panel in your rack.

Your front entry kit should contain the following items. If any are missing please email us at support@winterbloom.com.

- (1) Front entry panel
- (2) Panel mount DC barrel jacks
- (1) Rocker switch
- (2) M3x6 mounting screws (not pictured)

You will need hook up wire to assemble this module. We recommend 20 or 22 AWG stranded wire in red and black.

The first step is to prepare four 13cm (5") lengths of wire- two red, and two black. Strip the sleeve 1cm on both ends.

You also need two lengths of wire that will connect from the front panel to the Micronova board inside your case. Make sure you have enough length to reach and strip the sleeve 1cm on both ends.

Mount the switch in the panel, making sure that the `-` is facing upwards. The panel's switch cutout has a very tight fit, so you may have to compress the plastic springs on the switch to get it to snap into place.

Mount the two DC barrel jacks to the panel.

Wire the jacks and switch together as shown below, being care to wire the the correct leads on the barrel jacks.

Mount the panel in your rack

Run the power wires to your Micronova and use the screw terminals to connect them.


## All done

Congratulations! You've finished your very own Micronova!

![The compeleted module](/images/16-finished-1.jpg)

Now that it's all put together go check out the [User's Guide](/) and please show us your work by tweeting at [@wntrblm](https://twitter.com/wntrblm) or tagging [@wntrblm](https://instagram.com/wntrblm) in your instagram post.
