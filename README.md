# Firmware 🔧
low-level code implementing CircuitPython (port of Micropython)

# Bootloader
Built from [Adafruit's fork of the Microsoft UF2 SAMD bootloader](https://github.com/adafruit/uf2-samdx1)
Latest build (📅 2021-07-14)
   - [uf2 commit #2fd0593](https://github.com/adafruit/uf2-samdx1/commit/2fd0593fbc7dd12a13b2b4e6dc281fb5b54464b9)
   - built with `gcc-arm-none-eabi-10-2020-q4-major`

Since folks are starting to use SAMD51...`J20` and `J19` there are now separate bootloaders for each chipset. Make sure to use the correct one!

If you can access bootloader mode (double-click reset button), you can copy over the respective `update-bootloader` UF2 to update the bootloader without having to use JTAG.
<br>
<br>
## [All PyCubed Resources](https://www.notion.so/maholli/All-PyCubed-Resources-8738cab0dd0743239a3cde30c6066452)
Tutorials, design resources, and more!
<br>
<br>
<br>
<br>
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
