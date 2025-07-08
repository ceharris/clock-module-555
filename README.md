clock-module-555
================

This repository contains KiCad sources for a clock module based on a
design by Ben Eater as presented on his YouTube channel. Ben's version
of this module uses a mechanical toggle switch to select the free-running
or single-step mode. This version uses a more easily sourced push button
to toggle a flip-flop to select the mode. Both the mode select button
and the clock pulse button are debounced using 555 timers in monostable
configuration.

In free-running mode, the clock frequency can be varied using the 
on-board potentiometer, ranging from about 1 Hz to about 3 KHz.

![Clock Module Photo](clock-module-555.png)
