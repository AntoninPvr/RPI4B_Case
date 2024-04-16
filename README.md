<h1 align="center">
    <img src="https://github.com/AntoninPvr/RPI4B_Case/blob/main/img/logo.png?raw=true" alt="RPI Enclosure Logo" width="200"></a>
    <br>
    Raspberry PI 4B passive case
</h1>

---
![Static Badge](https://img.shields.io/badge/status-active-green)
![GitHub Release](https://img.shields.io/github/v/release/AntoninPvr/RPI4B_Case)
![GitHub License](https://img.shields.io/github/license/AntoninPvr/RPI4B_Case)

This enclosure is designed to be sleek and minimalistic. It is designed to be 3D printed. This case does not provide any camera or display port access. But GPIO are easily accessibles.

<p float="left">
  <img src="https://github.com/AntoninPvr/RPI4B_Case/blob/main/img/render_sd_hdmi.jpg?raw=true"  width="300"/>
  <img src="https://github.com/AntoninPvr/RPI4B_Case/blob/main/img/render_hdmi_usb.jpg?raw=true" width="300" /> 
</p>


## Compatibility
This enclosure support following boards:

* Raspberry PI 4B
* Raspberry PI 5B (not compatible with active cooling)

## Files

Two versions of the upper part are available. One with GPIO access and one without. Ideal for a clean look or server applications like VPN, DNS...

* `RPI_3bplus_enclosure_lower_1.2.STL` Lower part of the enclosure common to all
* `RPI_3bplus_enclosure_upper_1.2.STL` Orginal upper part of the enclosure with GPIO access
* `RPI_3bplus_enclosure_upper_1.2_no_gpio.STL` Upper part of the enclosure without GPIO access
* `gpio_cover.STL` Cover for GPIO. Best of both worlds, clean look and easy access to GPIO


## Thermal management
This enclosure is designed to be used with passive cooling solution. 35x35x12mm heatsink is recommended.

A 1mm copper plate between the CPU and the heatsink is needed to allow space for surrounding components.

No need for fan event with intense CPU usage.

## Material and print settings
Clearance is 0.2mm for all parts to facilitate assembly. No support is needed.

4x M3x24mm flat-head screws and 4x M3 nuts are needed to assemble the case.

## Run button
1mm hole above jack connector is designed to fit a 6x6mm push button. This button can be used to wake the Raspberry PI.
