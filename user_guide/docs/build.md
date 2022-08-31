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


## Screw terminals

The first step is placing and soldering the five 2-pin screw terminal blocks.

![Photo of the board and five screw terminal blocks](images/2-board-and-terminal-blocks.jpg)

It's easiest to solder one terminal block at a time. Place a terminal block on the front side of the board, taking care to place it so that the terminal openings face *outward* and match up with the triangles on the board.

![Photo with one of the terminal blocks placed onto the board](images/3-first-terminal-block-placement.jpg)

Hold the terminal block in place and flip the board over. It's okay if the terminal block isn't completely flush against the board, as long as the legs are through the holes.

![Photo with the board flipped over and the terminal block's legs poking through the board](images/4-first-terminal-block-flipped.jpg)

Solder one leg of the terminal block to hold it in place.

![Photo with one leg of the terminal block soldered to the board](images/5-first-terminal-tack.jpg)

Lift the board and use your iron to reflow the solder and push the terminal block flush against the board. Wait a few seconds for the joint to solidify before releasing the board.

![Photo with one leg of the terminal block being pushed flush against the board while applying the soldering iron to the joint](images/6-first-terminal-flush.jpg)

With the terminal block now flush against the board, solder the second leg into place.

![Photo of the back of the board with both legs of the terminal block soldered](images/7-first-terminal-second-leg.jpg)

Repeat this process for the four remaining terminal blocks, taking care to align the terminal openings.

![Photo of the board with all terminal blocks soldered](images/8-all-terminals-soldered.jpg)


## IDC headers

Your next task is placing and soldering the two 16 pin shielded IDC headers.

![Photo of the two 16-pin shielded IDC headers](images/10-16-pin-headers.jpg)

Place both of them on the front side of the board, being careful to align the notch in the header's shield with the drawing on the board. The board is designed to hold on to these headers tightly, so you might have to give a little pressure to push them all the way in.

![Photo of the first header placed on the front side of the board](images/11-first-header-placement.jpg)
![Photo of the second header placed on the front side of the board](images/12-second-header-placement.jpg)

Once you have both placed, flip the board over and solder just one pin on each header to tack it in place.

![Photo of one pin on the header soldered to hold the header in place](images/13-header-tack.jpg)
![Photo of the second header with one pin soldered to hold it in place](images/14-header-tack-2.jpg)

Double check that both headers are completely flush against the board, if they aren't, you can fix them using the same technique you used with the screw terminals. Once you've checked the placement, solder all 16 pins on both headers. You should be able to do them both at the same time, but if you're having trouble feel free to do them one at a time like you did with the terminal blocks.

![Photo of all of the pins on both headers soldered](images/15-headers-soldered.jpg)


## DC barrel jacks

Next up is placing and soldering the two DC barrel jacks.

![Photo of the two DC barrel jacks](images/16-barrel-jacks.jpg)

Similar to the terminal blocks, it's easiest to place these one at a time. Place one on the front side.

![Photo of one barrel jack placed on the front side of the board](images/17-barrel-jack-placement.jpg)

Then carefully flip the board over and solder just one leg to hold the barrel jack in place.

![Photo of the back of the board with the barrel jack legs poking through](images/18-barrel-jack-flipped.jpg)
![Photo of one pin on the barrel jack soldered](images/19-barrel-jack-tack.jpg)

Just as you did with the terminal blocks, lift the board and use your iron to reflow the solder and push the barrel jack flush against the board. Wait a few seconds for the joint to solidify before releasing the board.

With the barrel jack flush and held in place, solder the remaining two legs.

Finally, repeat this process for the second barrel jack.

![Photo of the back of the board with both barrel jacks completely soldered](images/20-barrel-jacks-soldered.jpg)


## DC-DC converters

The last step is to solder the three DC-DC converters. There are two 12V converters and one 5V converter. You'll need to identify them before placing them since they **must** be placed correctly for Micronova to work.

The single 5V converter is slightly smaller and has `VX7805-500` marked on it.

![Photo of the 5V DC-DC converter](images/21-5v-converter.jpg)

The two 12V converters are slightly larger and has `K7812M-100R3` marked on it.

![Photo of the 12V DC-DC converter](images/22-12v-converter.jpg)

Start by placing the **5V** converter on the front side of the board. It goes in the spot labeled `5V` on the lower left. Make sure the converter is oriented correctly so that it fits nicely within the white rectangle on the board.

![Photo of the 5V converter placed onto the front side of the board](images/23-5v-converter-placement.jpg)

Carefully flip the board over and solder one leg to hold the converter in place.

![Photo of the back of the board with just one left of the 5V converter soldered into place](images/24-5v-converter-tack.jpg)

Using the same technique as the DC barrel jacks and terminal blocks, reflow the solder and push the DC-DC converter flush against the board.

![Photo of the 5V converter being pushed flush against the board while heat is applied to the solder joint using a soldering iron](images/25-5v-converter-flush.jpg)

Once the DC-DC converter is flush, solder the remaining legs.

Repeat for the two 12V converters. They go into spots adjacent to the 5V converter marked `12V`. Again, make sure that they are oriented to match up with the corresponding white rectangle on the board.

![Photo of one of the 12V converters placed on the board](images/26-12v-converter-placement.jpg)

![Photo of the second 12V converter placed on the board](images/27-second-12v-converter-placement.jpg)

![Photo of the back of the board with all of the converters completely soldered](images/28-converters-soldered.jpg)

You're all done! If you have a busboard kit or a front panel kit, continue reading. If not, hop down to [the end](#all-done) for some useful links.


## Busboard

The busboard kit adds six additional power headers to your Micronova.

Your busboard kit should contain the following items. If any are missing please email us at support@winterbloom.com.

![Photo of the busboard kit's contents](images/bus-1-kit-contents.jpg)

- (1) Busboard PCB
- (7) 2x8 pin shielded IDC headers
- (1) 16 pin to 16 pin IDC cable (not pictured)

Assembling the busboard kit is fairly straightforward. Start by placing all seven IDC headers on the front side of the board, making sure to align the notch in the header's shield with the drawing on the board. The board is designed to hold on to these headers tightly, so you might have to give a little pressure to push them all the way in.

![Photo of three of the headers placed on the front of the board](images/bus-2-header-placement.jpg)
![Photo of all seven headers placed on the front of the board](images/bus-3-headers-all-placed.jpg)

Flip the board over and solder one pin on each header to tack them into place.

![Photo of the back of the board with the legs of all of the headers poking through](images/bus-4-flipped.jpg)
![Photo of one pin on the first header soldered](images/bus-5-tacking.jpg)
![Photo of one pin on the second header soldered](images/bus-6-tacking-2.jpg)
![Photo of one pin on each header soldered](images/bus-7-tacking-3.jpg)

Make sure that the headers are all flush against the board and adjust if needed by re-heating the solder joints. Once you're sure they're all flush, solder them all in to place.

![Photo of all headers completely soldered to the board](images/bus-8-soldered.jpg)

That's it! 🙂


## Front entry kit

The front entry kit lets you power your Micronova via a 4hp panel in your rack.

Your front entry kit should contain the following items. If any are missing please email us at support@winterbloom.com.

![Photo of the front entry kit's contents](images/front-1-kit-contents.jpg)

- (1) Front entry panel
- (2) Panel mount DC barrel jacks, including washers and nuts
- (1) Rocker switch
- (2) M3x6 mounting screws (not pictured)

You will need hook up wire to assemble this module. We recommend 20 or 22 AWG stranded wire in red and black.

The first step is to prepare four 13cm (5") lengths of wire- two red, and two black. Strip the sleeve 1cm on both ends.

You also need two lengths of wire that will connect from the front panel to the Micronova board inside your case. Make sure you have enough length to reach and strip the sleeve 1cm on both ends.

Mount the switch in the panel, making sure that the `-` is facing upwards. The panel's switch cutout has a very tight fit, so you may have to compress the plastic springs on the switch to get it to snap into place.

![Photo of the rocker switch being placed through the cutout in the panel](images/front-2-switch-placement.jpg)
![Photo of the rocker switch mounted to the panel](images/front-3-switch-mounted.jpg)

Mount the two DC barrel jacks to the panel, placing the washer and nut onto the jack from the front side of the panel.

![Photo of the first DC barrel jack placed through the top hole in the panel](images/front-4-barrel-jack-placement.jpg)
![Photo of the washer added to the DC barrel jack](images/front-5-barrel-jack-washer.jpg)
![Photo of the nut added to the DC barrel jack](images/front-5-barrel-jack-nut.jpg)
![Photo of both DC barrel jacks mounted to the panel](images/front-6-both-barrel-jacks-mounted.jpg)

Wire the jacks and switch together as shown below, being care to wire the the correct leads on the barrel jacks.

![Illustration of the front panel wiring](images/front-wiring.svg)

With everything wired up, give it a quick test by plugging in a power cable and making sure that the switch illuminates when switched on. If it does not illuminate or if it stays illuminated even when off, double-check your wiring **before** continuing.

If everything checks out, mount the panel in your rack.

![Photo of the panel placed in a rack](images/front-entry-2.jpg)

Run the power wires to your Micronova and use the screw terminals to connect them.

![Illustration of power connections](images/front-panel-screw-terminal-power.svg)


## All done

Congratulations! You've finished your very own Micronova!

Now that it's all put together go check out the [User's Guide](/) and please show us your work by tweeting at [@wntrblm](https://twitter.com/wntrblm) or tagging [@wntrblm](https://instagram.com/wntrblm) in your instagram post.
