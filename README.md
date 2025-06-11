# pdp8-ld12

## Description
This is a PDP-8/i clone based on the David E. Winkel "LD12 Lab Manual". The digital simulation is based on the Manual and DaveR's KiCad schematics and his Logisim simulation.
I transfered the Logisim version to Hneemann's Digital (https://github.com/hneemann/Digital) with minor modifications to get the TTY-Simulation running. This Release has some changes to use fewer Control Pulses. 
The original version always uses all 8 Control Pulsed during EXEC, this version switches to FETCH based on the executed instruction (See LD9-FETCH-RUN-EXEC-Logic.dig).

## Panel
![Panel](Documentation/Panel.svg)
