# Brake System Plausibility Device

Background
=============
Scuderia Tor Vergata is the official Formula SAE Team of the University of Rome Tor Vergata, based in Rome, Italy.

Founded in 2006, over the years Scuderia has been run by hundreds of students with one common goal, that of sharing and applying the technical and theoretical knowledge learned during their studies in a challenging project.

A total of more than 6 Formula SAE prototypes designed and fabricated, which participated in more than 10 Formula SAE events across Europe.

Electronic design
=============

The BSPD is a standalone non-programmable circuit that is used to open the shutdown circuit when hard breaking occurs for more than 500 ms. The BSPD's purpose is to maintain that the brake system is correct. This is calculated by detecting hard braking through brake system pressure sensor.Furthermore, when the throttle position exceeds 25% of the idle position, the BSPD will open the shutdown circuit. The BSPD gets supplied directly supplied from LVMS (Low Voltage Master Switch).


![bspd_final_rendered cropped (1)](https://user-images.githubusercontent.com/54326343/166416661-db14208e-ce83-4b20-b1a4-b2907256e258.png)


The BSPD resets itself if the opening condition is no longer present for more than 10 s.



PCB design with JLCPCB
=============

JLCPCB (https://jlcpcb.com/) is a company that focuses in prototyping PCBs and SMT assembly. JLCPCB guarantees quality, high precision, and fast board production, which was the primary reason we selected this company for the PCB production.

JLCPCB's website (https://jlcpcb.com/) offers a service that allows users to upload the Gerber file required for manufacturing, after which, there are numerous configurations that can be managed to meet the needs of the user, such as layers, delivery format, pcb color, and so on.

One of their standout features is that users can include a pcb stencil in their order and configure it on the website (https://jlcpcb.com/).
