# BSPD

Electronic design
=============

The BSPD is a non-programmable circuit which is embedded in the Tractive System Accumulator Container that is used to open the shutdown circuit when hard breaking occurs for more than 500 ms. The BSPD's purpose is to maintain that the brake system is correct. This is calculated by comparing the force applied to the brake pedal as well as the power supplied to the motors. When more than five kilowatts of power are delivered to the motors, the BSPD will open the shutdown circuit. A DC circuit current sensor can be used for measuring the power delivery. Furthermore, the BSPD will get triggered if the throttle position is more than 25% higher than the idle position. The BSPD gets supplied directly from LVMS (Low Voltage Master Switch).


The BSPD resets itself if the opening condition is no longer present for more than 10 s.


PCB design with JLCPCB
=============

JLCPCB (https://jlcpcb.com/) is a company that focuses in prototyping PCBs and SMT assembly. JLCPCB guarantees quality, high precision, and fast board production, which was the primary reason we selected this company for the PCB production.

JLCPCB's website (https://jlcpcb.com/) offers a service that allows users to upload the Gerber file required for manufacturing, after which, there are numerous configurations that can be managed to meet the needs of the user, such as layers, delivery format, pcb color, and so on.

One of their standout features is that users can include a pcb stencil in their order and configure it on the website (https://jlcpcb.com/).
