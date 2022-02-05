# YM64Axx-research
Some time ago I ordered 5 Yamaha YM3012 (DAC) chips from Aliexpress. In the package came 4 YM3012 chips and a mysterious YM64A12 chip. Later I found out that this chip was part of a series of custom FM music player chips produced by Yamaha, which played custom songs programmed in Mask ROM and could be produced on order. The one I specifically got was the [YM64A12](https://www.youtube.com/watch?v=POdlaSWQCBI). These chips appear to have been used for things like alarm clocks, landline phone ringtones, and similar such items where a low-cost, mass-produced chip containing a couple of songs (4 per chip in this case) were needed.\

In terms of FM performance:\
-2 operators\
-4 simultaneous sounds\
-16 different tones, 4 per song\

The chip contains an inbuilt 9-bit DAC (similar to the YM2612 used in the Sega Genesis), however the 2-operator structure is more reminiscent of the simpler YM3812 used in the Adlib sound card. The controls are much simpler, though, with just 2 inputs used to select one of the 4 preprogrammed songs. There are only 4 preprogrammed songs, however for the proposed use cases this seems like more than enough.\

The chip uses a 0.447MHz crystal input (3.579MHz / 8 or 14.1818MHz / 32), however 500KHz and its multiples divided down will also work, just the frequencies will be different.
