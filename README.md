# Firmware 🔧
low-level code implementing CircuitPython (port of Micropython)

# Bootloader
Built from [Adafruit's fork of the Microsoft UF2 SAMD bootloader](https://github.com/adafruit/uf2-samdx1)
Latest build (📅 2021-03-08)
   - [uf2 commit #530fedf](https://github.com/adafruit/uf2-samdx1/tree/530fedf5dab77a54e272f0ea1ad3ac0453241f8f)
   - built with `gcc-arm-none-eabi-10-2020-q4-major`

Since folks are starting to use SAMD51...`J20` and `J19` there are now separate bootloaders for each chipset. Make sure to use the correct one!

If you can access bootloader mode (double-click reset button), you can copy over the respective `update-bootloader` UF2 to update the bootloader without having to use JTAG.

## [⭐ See the PyCubed Quick Start page for tutorials, design resources, and more!](https://www.notion.so/maholli/PyCubed-4cbfac7e9b684852a2ab2193bd485c4d)
<br>
<br>

# Help Wanted ❗
See the issues tab for a list of tasks in need of YOUR ☝ help!

<br>
<br>
<br>
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
