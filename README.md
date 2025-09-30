<p align="center">
This is a fork of the original,the original Readme is enclosed under here.
Im forking, as my setup is different.
I have my nozzle electrically connected to an input.
Then i have a bolt placed on my printbed, connected to an output.
</p>
<p align="center">
  <img src="https://github.com/browsem/klipper_z_calibration_Capacitive/blob/master/pictures/IMG_20250717_123315764.jpg" width='50%'>
    <p align="center">Bolt mounted to the printbed</p>
</p>

<p align="center">
5V on the output, to the input, works like a switch, this will be the endstop
Then i need to home my capacitive probe to the sensor
</p>

<p align="center">
  <img src="https://github.com/browsem/klipper_z_calibration_Capacitive/blob/master/pictures/IMG_20250717_123326884.jpg" width='50%'>
  <p align="center">Nozzle comming down</p>
</p>

<p align="center">
Therefore i added an extra option, probe: switch or NonTouching.
This will only matter, when trying to probe the probe height, on the z endstop
</p>


<p align="center">
  <img src="https://repository-images.githubusercontent.com/365369551/ef2987a7-0faf-4844-91c9-f221e4112b4d" alt='Z-Calibration Logo' width='50%'>
  <h1 align="center">Automatic Z-Calibration</h1>
</p>

<p align="center">
It's like automatically baby-stepping on your 3D printer before every print, and the first layer will
always be perfect - no matter which nozzle or new flex-plate is being tested.
</p>

<p align="center">
  <a aria-label="Downloads" href="https://github.com/protoloft/klipper_z_calibration/releases">
    <img src="https://img.shields.io/github/release/protoloft/klipper_z_calibration?display_name=tag&style=flat-square">
  </a>
  <a aria-label="Stars" href="https://github.com/protoloft/klipper_z_calibration/stargazers">
    <img src="https://img.shields.io/github/stars/protoloft/klipper_z_calibration?style=flat-square">
  </a>
  <a aria-label="Forks" href="https://github.com/protoloft/klipper_z_calibration/network/members">
    <img src="https://img.shields.io/github/forks/protoloft/klipper_z_calibration?style=flat-square">
  </a>
  <a aria-label="License" href="https://github.com/protoloft/klipper_z_calibration/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/protoloft/klipper_z_calibration?style=flat-square">
  </a>
</p>

## Documentation

Visit the [Wiki](https://github.com/protoloft/klipper_z_calibration/wiki) to view the full documentation for this Klipper plugin.

The latest release notes are [here](https://github.com/protoloft/klipper_z_calibration/wiki/Changelog).

:pushpin: **And remember:** The smaller the switch-offset, the further the
 nozzle is away from the bed! :wink:

## Further Resources

A great how-to video by Kapman: [https://youtu.be/oQYHFecsTto](https://youtu.be/oQYHFecsTto)

### And if you are looking for an RRF version of this automatic z-offset calibration

You can find one [here](https://github.com/pRINTERnOODLE/Auto-Z-calibration-for-RRF-3.3-or-later-and-Klicky-Probe) from pRINTERnOODLE - This is really fantastic to see :tada:

## Thanks for all your feedback and support!

And if you like my work and want to support me, you can do so here:

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/X8X1C0DTD)

## Disclaimer

You use it at your onw risk! I'm not responsible for any damage that might result. Although,
this extension works rock solid for me and many others for years now. Always be careful
and double check everything when configuring or working with your printer. And as always,
never leave unattended while printing!
