Power Switch Shield with S202S02
================================

Simple shield with [2N7002](http://www.nxp.com/documents/data_sheet/2N7002.pdf) MOSFET to drive the [S202S02](http://www.sharpsma.com/webfm_send/303) Solid State Relay.  
The board is panelized to have two sub-boards with one S202S02 and also
a sub-board with three S202S02.

![](https://github.com/susisstrolch/PowerSwitchShield/blob/master/26deed2d59c932266c655a1408c2c5e5-17641_top.png)

Boards are available from [dirtypcbs.com.](http://dirtypcbs.com/view.php?share=17641&accesskey=2531b32f0bd15d34d1d7f6f8c30357b9)

The PCB contains spare places to solder pull-up / pull-down resistors.  
Pull-Up: R5, R8, R12, R14, R16  
Pull-Down: R6, R7, R13, R15, R17

Resistors (R1, R3, R18, R19, R20) are calculated to get 20mA current at 3.3V supply.  
By using larger values (180R) it may also be used as a 5V shield.

#WARNING
**The shield is designed to switch main power.** So you must care about proper isolation.  
Don't use metal nuts or bolds to fix the board - only use plastic ones!  
For **inductive loads** (e.g. motors) either **connect a [snubber](https://www.google.de/?gws_rd=ssl#q=snubber+circuit)** (surge absorption) circuit as close as possible to the AC clamps or use a *S202S11*.

![](https://github.com/susisstrolch/PowerSwitchShield/blob/master/snubber.jpg)

For AC current > 1A you should consider to use a heat sink (see datasheet "Fig.2 RMS ON-state Current vs. 
Ambient Temperature")!

[Sharp Documentation: Use of Solid State Relays (SSRs)](http://www.datasheetarchive.com/dlmain/SFDatasheet-3/sf-00061711.pdf)

