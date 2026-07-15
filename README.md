# handheld-sstc
A handheld SSTC project on PCB, designed for a large magic wand form factor, entirely powered from 8s 18650. Uses direct secondary feedback with gate driver and MOSFETs, and 555 interrupter

Actual build changes that differ from PCB:
* R13 = 100k as-built (was 150k on pcb)
* R10 = 220ohm 2W instead of 150ohm 1/4W in order to prevent it from burning out
* C6 = some sort of 0603 0.1uf SMD capacitor extracted from an old PCB because I forgot to order it on DigiKey
