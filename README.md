# 0002-65C816S minimal system
This circuit board supports a single WDC 65C816S microprocessor.
It allows attachment to a Digilent Spartan3A Starter Kit via a breakout board (see project [0001](https://github.com/bobb-uk/0001-Spartan3A-FX2-breakout))

The circuit is as basic as it can be.
Only two decoupling capacitors are used, though there are two more empty places incase of decoupling problems.

## Purpose
Purely for fun, to learn Verilog and use the Spartan3A Starter Kit will all its on-board peripherals.

## Board
4 layer FR4.  Top & Bot for signal routing.  Inner 1 & 2 provide GND and Power planes.
See [fabrication PDF](https://github.com/bobb-uk/0002-65C816S-minimal-system/blob/main/Fabrication%20data/0002-65C816S-minimal%20Fabrication%20and%20Assembly.pdf) for layer geometries, silkscreen and assembly.

BOM information, what little there is, can be found in the BOM [folder](https://github.com/bobb-uk/0002-65C816S-minimal-system/tree/main/BOM).

![blank board](https://github.com/bobb-uk/0002-65C816S-minimal-system/blob/main/Images/0002-01.png)
# WDC65C816S
Information in this enhanced version of the 6502 can be found at the [wdc65xx](https://wdc65xx.com/) and [Western Design Center](https://www.westerndesigncenter.com/) websites.

# Revisions
A : 8 June 2024 : CERN-OHL-W rev 2
