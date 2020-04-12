# Prusa i3 Bear Upgrade 2.1


:warning: **This is a development branch, use it at your own risk.** :warning:


## Table of contents
  1. [Introduction](#introduction)
  1. [New features since Bear Upgrade 2.0](#new-features-since-bear-upgrade-20)
  1. [Compatibility](#compatibility)
  1. [Manual](#manual)
  1. [Optional parts](#optional-parts)
  1. [Community](#community)
  1. [Where can I get an official kit?](#where-can-i-get-an-official-kit)
  1. [Partners and contributors](#partners-and-contributors)
  1. [Support my work](#support-my-work)
  1. [Thank you](#thank-you)
  1. [Credit, sources and inspiration](#credit-sources-and-inspiration)




## Introduction

The Bear Upgrade replaces the original [Prusa i3 MK2(S), MK2.5(S) and MK3(S)](https://www.prusa3d.com/) frame with a more rigid and reliable solution. It allows faster prints, increases precision, makes maintenance easier and opens the door to more customizations. Plus it looks unique with our coloured frames!

![Bear Upgrade 2.1 MK3S](doc/rendering/mk3_home_right_882px.jpg)



## New features since Bear Upgrade 2.0

  * Single frame for all Prusa versions (same frame as Full Bear 2.0 MK3)
  * New stiffer Y axis with tensioner
  * New stiffer Z axis
  * Improve X and Y axis homing accuracy
  * Improve Z axis alignment and assembly
  * Reduce Y axis stepper noise for MK3(S)
  * New build helpers for Y and Z axis
  * Support all Prusa PSU
  * Shorter LCD supports
  * New custom LCD cover
  * Nicer and stronger end caps
  * Easier assembly of printed parts
  * Improve wire management with new cable clips
  * Stiffer mounts for Rambo Mini/Einsy cover
  * Compatible with E3D Gates idlers as well as 9mm belt

:warning: This a work in progress, the current kits sold by our official distributors are not containing the hardware necessary for this upgrade.



## Compatibility

This Bear Upgrade 2.1 is compatible with Full Bear Upgrade 2.0 __MK3__ frame. If you do not know which frame you have please check [our FAQ here](https://guides.bear-lab.com/Wiki/Bear_FAQ#Section_Which_Full_Bear_frame_do_I_have).

:bulb: If you have a Full Bear Upgrade 2.0 MK2S or MK2.5 frame you can find compatible parts here: [optional_parts/bear_2.0_upgrade_mk2-2s-2.5-2.5s](optional_parts/bear_2.0_upgrade_mk2-2s-2.5-2.5s).

:warning: The new Y and Z axis are __not__ compatible with any of the existing Prusa or Bear 2.0 parts. You have to update all parts from Bear 2.1.



## Manual

The manual contains bill of materials (BOM), print settings and assembly instructions.

[Read the manual here :book:](manual/)



## Optional parts

Here is the list of official optional parts for the Bear extruder and X axis.

| Description | Link |
|-------------|------|
| Upgrade parts fo Bear 2.0 MK2(S), MK2.5(S) frame | [bear_2.0_upgrade_mk2-2s-2.5-2.5s](optional_parts/bear_2.0_upgrade_mk2-2s-2.5-2.5s) |
| Y idler for larger 9mm 2GT belt | [y_idler_9mm_belt](optional_parts/y_idler_9mm_belt) |
| Y idler tensioner for E3D idler | [y_idler_tensioner_e3d](optional_parts/y_idler_tensioner_e3d) |
| LCD cover | [lcd_cover](optional_parts/lcd_cover) |
| Bear Extruder and X Axis | [For MK2.5 and MK3 (version 0.6.0-alpha)](https://www.thingiverse.com/thing:3226689)<br/> [For MK2.5S and MK3S (version 0.7.0-beta)](https://www.thingiverse.com/thing:3716110) |

You can also find optional parts designed by the community at [https://guides.bear-lab.com/Wiki/community_optional_parts](guides.bear-lab.com/Wiki/community_optional_parts).



## Community

Here are the places were the Bear project is the most active. Do not hesitate to ask if you have a question :

* Facebook group : [facebook.com/groups/PrusaBearUpgrade](https://www.facebook.com/groups/PrusaBearUpgrade)
* Discord server of "The 602 Wasteland" community : [discordapp.com/invite/hYUjSnW](https://discordapp.com/invite/hYUjSnW)
* GitHub : [github.com/gregsaun](https://github.com/gregsaun)
* Thingiverse : [thingiverse.com/pekcitron](https://www.thingiverse.com/pekcitron)
* Openbuilds community : [openbuilds.com/builds/prusa-i3-bear-upgrade-v2.6428](https://openbuilds.com/builds/prusa-i3-bear-upgrade-v2.6428/)



## Where can I get an official kit?

Official distributors are selling a kit with all screws and extrusions ready for the upgrade, you will only need to print latest 3D printed parts.

All distributors are following [specifications](doc/vslot_specs_tolerances.pdf) to ensure you will have a perfectly squared Bear. All distributors are using professional machines dedicated to cut aluminum extrusion (like CNC machines). In case your extrusion is out of specifications, you can get a replacement for free. We have created a dedicated support channel in case customers have more technical questions or need information for a custom build.

  * ![all3d makers logo](doc/distributors/all3dmakers_logo.png)  
     All3D Makers (US)  
     [all3dmakers.com](http://all3dmakers.com/)  


  * ![blackfrog logo](doc/distributors/blackfrog_logo.jpg)  
     Blackfrog (EU)  
     [blackfrog.pl](https://blackfrog.pl)  

  * ![lecktor logo](doc/distributors/lecktor_logo.png)  
    Lecktor (EU)  
    [lecktor.com](http://lecktor.com)  

  * ![makerparts.ca logo](doc/distributors/makerpartsca_logo.jpg)  
    Makerparts.ca (CA)  
    [makerparts.ca](http://makerparts.ca)  


  * ![ooznest logo](doc/distributors/ooznest_logo.png)  
    Ooznest (EU)  
    [ooznest.co.uk](https://ooznest.co.uk/)  


  * ![ratrig logo](doc/distributors/ratrig_logo.jpg)  
    RatRig (EU)  
    [www.ratrig.com](http://www.ratrig.com/)  

By purchasing a kit from official distributors you are supporting the development of the Bear project, thank you very much!



## Partners and contributors

![LDO Motors](doc/partners/ldo_motors.png) &nbsp;[LDO Motors](http://ldomotors.com/) is the manufacturer of the Original Bear upgrade kit for all distributors with the exception of [RatRig](http://www.ratrig.com/).

![3DFused](doc/partners/3d_fused.png) &nbsp;[3DFused](https://3dfused.com/) is helping the Bear development team with linear motion knowledge and will sell custom linear rail kit for the Bear Upgrade.

Grégoire Saunier is the inventor of the Original Bear Upgrade frame and extruder.

Florian Däubler, Josh Jones and Stefan Maue are active developers supporting the work of Grégoire Saunier.

Barry Danks, David Ogles, Florian Däubler, Josh Jones, Nathan Denkin, Orlando from All3DMakers, Termlimit are admins of the Bear community and help with translations.



## Support my work

The Bear project is made possible thanks supporters, you can participate via
<br/><br/>
[![become a patron](doc/icons/patreon_50px.png)](https://www.patreon.com/gregsaun)<br/>[patreon.com/gregsaun](https://www.patreon.com/gregsaun)
<br/><br/>
[![paypal.me](doc/icons/paypal_50px.png)](https://www.paypal.me/gregsaun)<br/>[paypal.me/gregsaun](https://www.paypal.me/gregsaun)
<br/><br/>
 You can also send me a tip via [Thingiverse](https://www.thingiverse.com/pekcitron/about) if you prefer that way.

Massive thank you in advance :heart:



## Thank you

Thank you to all my Patreons : 3D-Maniac, 3DPrintronics, Aaron Rieley, Ahmed, Albe Gouws, Alberto Vargas, Alex Vasile, Anders Svendsen, Andrew Bingham, Apton Ika, Bas Borgignons, Ben Langley, Bob Collinsworth, Borja Gutierez Yañez, Brad Craig, Chris Jackson, Chris Warkocki, Christopher Lee, Christos Goulas, Corey Dryja, Corrado, Cristian Toma, darkly spectre aka that one belgian cunt, Darren Furniss, David F Morrison II, David Pesce, David Tyra, Dejan Vozlic, Doug Palmer, Elendil the tall, Emiliano Vignali, Erich Jermann, Espen Fjellvær Olsen, Evan, Evgen, Filament Frenzy, flobler, Fredrik Id, Garrett White, Garth Clardy, Gorgonbert, Greg3D, Grigori Palamartšuk, Harrison, Hector Gonzalez, Hugo Henry-garon, Illia Tsariuk, J.D. sloot, Jack Emilsen, Jacob Leonard, Jake Hamlin, Jan Andersen, Jason Bao, Jason Marcus, JD, Jim Jacques, Jimmy Lee, JimmySnails, Joan Torner Corrons, Joel Weinberg, Jonathan Ryer, Jonny Menkakow, Joseph Mizrachi, Joseph Quan, Josh Carter, Josheua R Mascote, Joshua Jones, JTa, Juan Rosario, Keith Beaul, Ken Waters, Kevin Smith, Kim Schauss, Kristof Spiszak, Kyle Rothrock, Laurent Zender, Loïc Dumont, Luke Turner, Magnus Pfeffer, Marie Julien, Martin Majewski, Merijn van Mourik, Michal Kapusnik, Michiel Plaisier, Miguel Castillo, Mike Phelps, Moody Wood Carving, Name, Narasak Mansurang, Neofitos Papadopoulos, Nicolas Pottier, Orlando E Moran, Oscar Padilla, Patrick Glyré, Patrick Hung, Phil S., Przemek, QcRetro, ra100, Rasmus Baes, RC-CnC, Richard Bateman, robert veline, Ronny Olsen, Rubens Panfili, Ryan Lenny, Ryan Lobbins, SamE0717, Satoshi Takanashi, Scott Rini, Serkan Aksu, Settle, Shawn Chronister, Shawn England, Skyler Weinkauf, sleene, Staffsmith aka Thorben Plath, Stanislav Kljuhhin, Stephan Kohls, Stephen Pope, Steve Carter, Steve Peterson, Steven Daglish, Stig Jøran Moen, Stuflo, Ted Rathkopf, Thom Sturgill, Tomáš Vydra, Total Dramatist, Trae LaPole, Trystan Jones, Tyler Townes, Víctor Martínez, Warren Schultz, Wes Warner, Zohaib.

Thank you to David Ogles, Flobler, Jason from LDO Motors, Matthew Humphrey, Nathan Denkin, Orlando from All3DMakers, Saiz, Sleene, Termlimit, Vertigo295 for helping me developing the Bear project.

Thank you to all that have send me a tip on Thingiverse and PayPal.

Thank you to everybody from Facebook group and The 602 Wasteland community.

Thank you for having purchased a kit from an official distributor.

Thank you to all official distributors for taking care of the kits and customers.

Thank you Jason from LDO Motors for the quality manufacturing and relationship.

Thank you Openbuilds for your open source hardware and community.

Thank you for making the community alive with all your comments, issues, pull requests, optional parts, make, pictures, etc.



## Credit, sources and inspiration

Here is list of sources and inspiration :

  * Original Prusa i3 printers : [prusa3d.com](http://www.prusa3d.com).
  * Prusa 3030 Haribo Edition : [github.com/PrusaMK2Users/3030_Haribo_Edition](https://github.com/PrusaMK2Users/3030_Haribo_Edition).
  * Openbuilds for the invention of opensource vslot extrusions : [openbuilds.org](https://www.openbuilds.org).
  * Roy Henriksson for the inspiration of his Y axis tensioner : [thingiverse.com/thing:3502543](https://www.thingiverse.com/thing:3502543).
  * Vecko Kojchevski for his Z axis parts and feedback : [thingiverse.com/vekoj/designs](https://www.thingiverse.com/vekoj/designs).

Massive thanks to these projects, without them this project can not exist!
