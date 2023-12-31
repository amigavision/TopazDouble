# Topaz Double

**Double-height recreation of Amiga’s iconic Topaz typeface.**

This is an Amiga-native recreation of one of the most beautiful and readable 8×8 pixel typefaces ever created: Topaz — now rendered in pixel-perfect 8×16px for modern resolutions.

Out of the box, Amiga used a tall (~2:1) resolution — 640×200 (NTSC) or 640×256 (PAL) -- which means that the standard Topaz typeface/font would be half-height if you were using it with resolutions with a pixel aspect ratio closer to 1:1.

For some reason, there has never been an Amiga-native version of a double-height Topaz (at least not that I could find) for use with resolutions with a square (1:1) pixel ratio, so I made one.

This typeface is ideal for “modern” resolutions like 800×600, 1024×768, classic Amiga resolutions like 640×400 and 640×512 (Hi-Res Interlace) — as well as 16:9 resolutions like 720p and 1080p, which are supported by the MiSTer FPGA Amiga core and RTG graphics implementations.

Two typefaces are included:

## Topaz Double Sans

A double-height recreation of the Topaz variant used in AmigaOS 2 and 3.

<img src="Images/Topaz Double Sans.png">

## Topaz Double Serif

A double-height recreation of the Topaz variant used in AmigaOS 1.2 and 1.3.

<img src="Images/Topaz Double Serif.png">

## Installation

Copy the contents of the `Fonts` directory to your `FONTS:` assign on the Amiga.

## Colophon

The typeface was lovingly recreated by hand, since there are no obvious ways to easily scale an Amiga font file to be twice the height, and I didn’t feel like reverse engineering the Amiga font file format.

<img src="Images/BobBurns.gif">

Original Serif (1.x) typeface design by [Bob Burns] (AmiWest 2016 talk).

Original Sans (2.x/3.x) typeface design by [Peter J Cherna]. [Some Amiga History] on this.

The typeface was made by using the excellent [modernized version of the Amiga Font Editor](http://bax.comlab.uni-rostock.de/en/projects/fonted/) by Henryk Richter.

If you find any errors in the conversion, file an issue in the [issue tracker].

*—Alex Limi* · https://limi.net

[issue tracker]:https://github.com/amigavision/TopazDouble/issues
[Bob Burns]:https://youtu.be/p_A_ZrDaF9w
[Peter J Cherna]:https://twitter.com/PChernaScala
[Some Amiga History]:https://www.gregdonner.org/workbench/wb_14_20_explanation.html
