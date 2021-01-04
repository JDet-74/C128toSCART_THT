<h2>C128toSCART_THT</h2>

<p>This is a project to connect a&nbsp;Commodore C128 8-bit computer to a display with a SCART input device.</p>

<p>Here, you can find some documents to build the video adapter PCB which I developed.</p>

<p>Get the information, build your PCB and have some 8-bit fun.</p>

<p>I started this project because I wanted to use my old Commodore 128DCR with a modern display.</p>

<p>I only had&nbsp;a 30-year-old SCART-cable that combines the 9 pin D-SUB RGBI connector and the 8 pin DIN connector for audio and video output.</p>

<p>I reverse engineered the old cable and got into this content. The Commodore 128DCR has 2 separate video chips.</p>

<p>The VIC-chip that provides the 40 column video mode in a composite and s-video signal and the VDC-chip that provides the 80 column video mode in a 5V TTL level RGBI signal.&nbsp;</p>

<p>It is possible to use the C128 with 2 displays. One display that supports RGBI for the 80 column mode and another display that supports composite or s-video for the 40 column mode.</p>

<p>I wanted just one display that supports both and that was the reason why I used&nbsp;the SCART interface.</p>

<p>The SCART standard provides RGB, composite, s-video and component (Y Pb&nbsp;Pr). It is possible to use only one display and to switch between the two column modes.</p>

<p>I researched and created a PCB that converts the digital 5V TTL 4 bit RGBI signal into a analog RGB signal. For that I used a <span style="font-family: Arial, Helvetica, sans-serif; font-size: 12px;">EEPLD (electrical erasable&nbsp;</span>&nbsp;programmable logic device) that converts the 4 bit RGBI color code into a 6 bit RGB color code. A resistor network adapts the TTL level to the analog RGB voltage level.</p>

<p>This all happens between the 9 pin D-SUB connector and the manual switch.</p>

<p>The composite or s-video signal goes from the C128 DIN connector straight through the switch.</p>

<p>The SWITCH is just for switching the right signals to the right pins of the SCART connector to run the display device.</p>

<p>In the following directories you will find the necessary files for the PCB, the soldering, the part list, the housing and the switch-extension.</p>

## Contact
For any questions (technical or experience) or puchase a CNC milled housing, please use the issue tracking system of github.

<p style="color: blue; background-color: red;"><strong>Mail to: kernelpanic_74[at]yahoo.de</strong></p>

<p>Now some pictures of the project.&nbsp;Enjoy!</p>

<hr />
<p><img alt="PCB in open housing" src="./pics/C128toSCART04.jpg" style="border-width: 1px; border-style: solid;" /></p>

<p>This is the open housing with the soldered PCB mounted in</p>

<hr />
<p><img alt="closed housing - connections to the C128" src="./pics/C128toSCART06.jpg" style="border-width: 1px; border-style: solid;" /></p>

<p>The closed housing with the connections sockets to the C128 (D-SUB for RGBI &amp; DIN for the A/V Plug)</p>

<hr />
<p><img alt="closed housing - the longhole for the switch-extension" src="./pics/C128toSCART09.jpg" style="border-width: 1px; border-style: solid;" /></p>

<p>The view from above - the hole for the 3mm DUO-LED and the long hole for the switch-extension.<br />
It is also possible to toggle the switch with a pencil or something else ;)</p>

<hr />
<p><img alt="housing LED blue (80 column mode)" src="./pics/C128toSCART11.jpg" style="border-width: 1px; border-style: solid;" /></p>

<p>The 3D printed switch-extension is plugged in.<br />
Device switched in 80 column mode (the blue LED indicates that) powered from a 5V USB-Charger with a barrel plug.<br />
It is possible to use the RGBI/CGA output of an&nbsp;old PC with a CGA graphic card to&nbsp; use a SCART display device.&nbsp;</p>
