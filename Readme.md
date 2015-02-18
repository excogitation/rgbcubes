[makefu](https://github.com/makefu/) and I stumbled upon the
[LEDbar project](https://brmlab.cz/project/ledbar) of hackerspace prague.
We were intrigued by the simplicity of the box design - some cardboard,
hot glue and what looked like to be sandwich paper for the front - that
worked very well / looks amazing.

To get the same evenly distributed light effect I opted for
some matte acrylic (that I had in a box somewhere) and the first
box was built within no time making use of the outline generation @ [boxmaker](http://boxmaker.connectionlab.org/).

The result was even better than expected:
![firstbox yellow](https://raw.github.com/excogitation/rgbcubes/master/pics/firstbox_yellow.png)
![firstbox blue](https://raw.github.com/excogitation/rgbcubes/master/pics/firstbox_blue.png)

^ This is done with a single ws1812b led.

The light bounces (becomes diffuse) to even illuminate the whole box.

We decided we wanted to make an IOT version off it with multiple, connected cubes
that you can control through a webpage or better yet through your phone and
doubles as a room light (defaulting to white when switching the power on).

BOM / cost estimation for 50 pcs as follows:
* ~~ 250€ (5€/piece) acrylic 6.144 qm   @ ~ 40€/qm
* 25€ wr703n 
* 5,30$ [32u4](http://www.aliexpress.com/item/Free-Shipping-New-Pro-Micro-for-arduino-ATmega32U4-5V-16MHz-Module-with-2-row-pin-header/1576902211.html)
* 12,87$ [50 pcs led on pcb](http://www.aliexpress.com/item/DC5V-mini-board-10mm-3mm-WS2812B-LED-with-Heatsink-RGB-5050-SMD-WS2811-IC-Built-in/32227387034.html)
* 16,14$ [50 pcs male + female connectors](http://www.aliexpress.com/item/50-pairs-lot-4-PIN-Male-and-Female-RGB-connector-coupler-Wire-Cable-For-3528-5050/1374657964.html)
^^ could have longer leads; could do with only 3 pins
[JSTSM connector datasheet (SMB-04v-B(N)C)](https://www.adafruit.com/datasheets/JSTSM.pdf).
___
350€ / 50pcs (including laser cutter time)

All credit for the IOT software part goes to makefu and is available [in this repository](https://github.com/makefu/rgbcubes).
Future software improvements will propably happen there.

[rgbcubes picture album](https://picasaweb.google.com/115792422633543473919/ProjectsRgbcubes?authkey=Gv1sRgCLTzz46ci8fZ7QE)