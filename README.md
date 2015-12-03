## yotta Target Description Using GCC to Compile for Freescale Kinetis K22F Chips

This is a [yotta](https://github.com/ARMmbed/yotta) target description for
compiling for Freescale's Kinetis K22F family of microcontrollers. Currently
only the MK22FN512VLH12 is supported. You should not normally use this target
description directly, but instead use a more specific description of a target
board.

This target description inherits from the generic
[mbed-gcc](https://github.com/ARMmbed/target-mbed-gcc) target description,
which provides most of the information about how to run the compiler.

**To build for the FRDM K22F development board, use the
[frdm-k22f-gcc](TBD) target
description** (which inherits from this one). The frdm-k22f target description
also provides a good starting point to copy if you are creating a new target
description for your own board using a K22F microcontroller.
