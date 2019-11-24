                   .:                     :,                                          
,:::::::: ::`      :::                   :::                                          
,:::::::: ::`      :::                   :::                                          
.,,:::,,, ::`.:,   ... .. .:,     .:. ..`... ..`   ..   .:,    .. ::  .::,     .:,`   
   ,::    :::::::  ::, :::::::  `:::::::.,:: :::  ::: .::::::  ::::: ::::::  .::::::  
   ,::    :::::::: ::, :::::::: ::::::::.,:: :::  ::: :::,:::, ::::: ::::::, :::::::: 
   ,::    :::  ::: ::, :::  :::`::.  :::.,::  ::,`::`:::   ::: :::  `::,`   :::   ::: 
   ,::    ::.  ::: ::, ::`  :::.::    ::.,::  :::::: ::::::::: ::`   :::::: ::::::::: 
   ,::    ::.  ::: ::, ::`  :::.::    ::.,::  .::::: ::::::::: ::`    ::::::::::::::: 
   ,::    ::.  ::: ::, ::`  ::: ::: `:::.,::   ::::  :::`  ,,, ::`  .::  :::.::.  ,,, 
   ,::    ::.  ::: ::, ::`  ::: ::::::::.,::   ::::   :::::::` ::`   ::::::: :::::::. 
   ,::    ::.  ::: ::, ::`  :::  :::::::`,::    ::.    :::::`  ::`   ::::::   :::::.  
                                ::,  ,::                               ``             
                                ::::::::                                              
                                 ::::::                                               
                                  `,,`


http://www.thingiverse.com/thing:3372910
Mechanical Keyboard - Tada68 by FedorSosnin is licensed under the Creative Commons - Attribution license.
http://creativecommons.org/licenses/by/3.0/

# Summary

In my search for a 3D Printed keyboard case, I came across the WhiteFox by @Matt3o. He has many build threads and videos that are extremely useful and has inspired me to try my hand at hand-wiring my own from scratch.

I loved his WhiteFox build and design but was more interested in a Tada68 layout. This is a remix of his brilliant board with my ideas for a unique, custom keyboard. Also included are the "non standard" keys you will need for this layout.

Here is the layout of the Tada68:
![Image](https://thingiverse-production-new.s3.amazonaws.com/assets/6f/9b/d4/2e/13/Yy9tVd7A.png)

For this build I went for the cheapest mechanical keyboard I could make. To achieve this you will need patience because you will have order some parts on eBay or AliExpress from China. Heres what you will need:

Teensy 2.0 - $11 (or buy a knock off for ~$6)
Mini USB cable - $5
Rubber feet - $4-6 (or print them if you have TPU)
Hardware - $4
Standard "OEM" Keycaps - $8-10 (for single color)
70 - Cherry MX style switches - $10 (MX Blue clones)
100 - 1N4148 Diodes - $3
3 - Costar plate mounted 2u stabilizers - $4
1 - Costar plate mounted 6.25u stabilizer - $2
Thin wire - ?
Solder + Iron - ?
Patience - ?

<b>Added a how to add firmware via EasyAVR including all files for this same layout on my other keyboard here:</b> https://www.thingiverse.com/thing:3478494

Enjoy and post your makes!

<I>If you found my Things useful, treat me to a cup of coffee by using the PayPal button below :) </I>


<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
<input type="hidden" name="cmd" value="_s-xclick">
<input type="hidden" name="hosted_button_id" value="98PY7JLC48DJN">
<table>
<tr><td><input type="hidden" name="on0" value="Buy me a cup of coffee">Buy me a cup of coffee</td></tr><tr><td><select name="os0">
	<option value="Buy me a cup of coffee">Buy me a cup of coffee $3.00 USD</option>
	<option value="Buy me a massive cups of coffee">Buy me a massive cups of coffee $5.00 USD</option>
	<option value="Give me a caffeine coma">Give me a caffeine coma $10.00 USD</option>
</select> </td></tr>
</table>
<input type="hidden" name="currency_code" value="USD">
<input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_buynow_LG.gif" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!">
<img alt="" border="0" src="https://www.paypalobjects.com/en_US/i/scr/pixel.gif" width="1" height="1">
</form>

------------------------------------------------------------- 

<b> Update 1: Added v2 of Bottom Right Panel that holds in the teensy for a better fit. Also added v2 of the Left Side of the keyboard for a bigger and better fitting opening for the teensy microcontroller. Everything should now fit without modification.

# Post-Printing

![Alt text](https://cdn.thingiverse.com/assets/4e/fe/ed/c3/3e/Tada68231.JPG)
Here are the parts you need to print as well as hardware, teensy, and keys. The two chassis pieces (I have a Creality Ender 3 that prints 220x220mm max so it had to be split) to make up the main body, the back plates, some dove tails, and a few non standard (OEM) size keys for shift, page up/down, and Alt, FN, Cntr.

![Alt text](https://cdn.thingiverse.com/assets/ca/ce/45/f8/f6/Tada68239.JPG)
This is where the Teensy 2.0, the micro controller that will power the keyboard, gets tucked away.

![Alt text](https://cdn.thingiverse.com/assets/77/d1/d4/20/f8/Tada68237.JPG)
The panel on the bottom has a tab that holds the teensy in place

![Alt text](https://cdn.thingiverse.com/assets/6b/3b/31/c1/1f/Tada68240.JPG)
Threading in the hardware into the PLA is actually really easy. Just be gentle and don't over tighten the screws.

![Alt text](https://cdn.thingiverse.com/assets/64/c1/d2/4a/b0/Tada68242.JPG)
Finally, the diodes, and the "NewGiant" Blue (Outemu blue clones) switches came.

![Alt text](https://cdn.thingiverse.com/assets/b9/5b/df/bb/df/Tada68244.JPG)
You need to glue the chassis together and use the dove tails to make the two pieces into one. Take your time here and make sure everything is aligned. Then, insert the switches.

![Alt text](https://cdn.thingiverse.com/assets/fb/51/11/3d/2c/Tada68_handwiring_diagram_-_teensy_2.0.JPG)
Here is a wiring diagram I made. Take your time planning at this step as small mistakes could take a long time to undo. I would also go ahead and Google "EasyAVR" and get your hands on a hardwired.py example so you can start creating the firmware for your custom keyboard. 

![Alt text](https://cdn.thingiverse.com/assets/17/b8/7a/43/14/Tada68247.JPG)
Time for some hand wiring! This is my first time soldering more that a few wires. So, please keep that in mind...

![Alt text](https://cdn.thingiverse.com/assets/16/10/16/57/46/Tada68249.JPG)
The rows done!

![Alt text](https://cdn.thingiverse.com/assets/05/35/7b/27/b2/Tada68251.JPG)
And now the columns. The green row wires in this photo are soldered to the pins of the switch but actually needed to be soldered above the diode to work. I fixed this issue shortly after this photo.

![Alt text](https://cdn.thingiverse.com/assets/e9/81/4a/b1/23/Tada68253.JPG)
And here is the teensy all wired up to the rows and columns.

![Alt text](https://cdn.thingiverse.com/assets/a6/5b/b9/ed/3c/Tada68257.JPG)
The back panels and the feet are on. I actually had to move the feet around a bit to get it to be perfectly level. Its a 3D Print after all.

![Alt text](https://cdn.thingiverse.com/assets/e1/2d/52/cb/e1/Tada68259.JPG)
Here's the finished keyboard! So excited to have it wired and working. I used EasyAVR to program the teensy. The next step is to figure out some backlighting. I'd love to use an LED strip to light up the case. :)

![Alt text](https://cdn.thingiverse.com/assets/8b/8e/c2/e6/e7/Its_Lit_1.JPG)
Got an LED strip working via QMK!