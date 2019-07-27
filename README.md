# firmware
low-level code implementing CircuitPython (port of Micropython) 

❗ Flashing the bootloader via JTAG is only necessary the first time the board is powered. See the section below for more details. 

During standard operation, the firmware (CircuitPython) and bootloader (custom UF2) can both be updated via USB. 
- To put the board into firmware/bootloader "programming mode," connect it to a computer using a micro USB cable and toggle the RESET button twice in quick succession. The PyCubed board will now mount as a mass storage device labeled `PYBOOT`. Updated firmware/bootloader UF2 files can now be dragged onto the drive. After the file is transfered, the board will reboot and resume normal operation.

# Help Wanted ❗
See the issues tab for a list of tasks in need of YOUR ☝ help!
