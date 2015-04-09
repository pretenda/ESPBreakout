# ESPBreakout

Here is a link to it on dirtypcbs: http://dirtypcbs.com/view.php?share=5472&accesskey=baa26ead4281fe835c0db18bac90b08a  
I would really appreciate it if you order one off dirtypcbs rather than using the gerbers, this helps the project fund! It'll cost you the same amount, I just get $1 store credit for every set of boards ordered.


There are a few things I decided to put on the board:

* On the bottom right there is a jumper block for setting CH_PD, GPIO0, GPIO2 and GPIO15 to either high or low.
* There is a standard FTDI breakout pinout on top of the board. I have a sparkfun FTDI basic breakout (https://www.sparkfun.com/products/9716) that I have been using for programming my ESP8266 ESP-1's. I figured having the proper header on there would be a useful thing.
* The FTDI Power jumper is to allow you to power the board from the breakout if that is what you really want to do. From what I've been reading, doing that is a really bad idea, but hey. If you want to try it, be my guest
* There is a dedicated 3v3/ground header, where you can plug your power supply into. For testing I will just be using my ebay special manson power supply.
* I have all the traces on the top of the board. I've not done this before, but in theory I guess you could etch this board at home yourself? The only thing would be isolating the traces below the ESP to make sure they don't short out the bottom of the board if that is a thing.

You will need 40 pins of standard 2.54mm male headers and 5 jumpers. You can pick them up off ebay for a few dollars.