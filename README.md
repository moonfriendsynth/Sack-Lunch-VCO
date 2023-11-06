# Sack-Lunch-VCO
A simple AS3340-based VCO for eurorack

This VCO was designed using a number of open source schematics as well as the AS3340's data sheet. It is nothing fancy, but it gets the job done, like a sack lunch.\

You can find the schematic here as well as gerbers for the PCBs and front panel. If you want to make your own front panel, you can use the edgecuts files here to get the exact outline.

<b>If you want to print this yourself</b>
<br>Please be aware, I have made a few changes to these gerbers since I last printed them. The changes were minor, but I have not verified them myself. Print at your own (very small) risk.
<br><br>To print, download Sack Lunch VCO Board A Gerbers.zip, Sack Lunch VCO Board b Gerbers.zip, and VCO Front Plate Gerbers.zip. I used JLCPCB to print mine, and you can probably get these for about $10-15 plus shipping (which is another $15). Or email me moonfriendsynth@gmail.com and I'll send you an old version (which still works just as good with two minor changes) for much cheaper.

<b>Features</b>
1. 3 waveform outputs 10vpp
2. Hard Sync input
3. PWM for square wave, with a range from 50% to 0% (at the far clockwise on the knob, 0%, the waveform becomes silent)
4. PWM CV input - when CV is patched in, the PWM nob becomes an attenuator for the CV
5. Linear FM input with attenuator knob
6. Fine and coarse frequency knobs 
7. LED status light. This is optional and it's only purpose is to add some extra color to your rack
8. Stable tuning, as is typical of the AS3340. Once you initially tune the circuit, you likely won't need to fiddle with the trimmers in the back ever again
9. 2 forms of circuit protection: schottky diodes on the power rails, which will prevent damage in the case of polarity reversal, and a shrowded box header on the power pins. Apparently a lot of companies do not use these box headers, which is confusing since they are super cheap and they have the benefit of physically preventing you from pluggin power in backward. Seems like a no-brainer. 
10. A little owl, hanging out
11. A topographical map of Mount Rainier in the background, if you ever find yourself lost out there with only your trusty VCO to guide you

<b>Notes:</b>
There are a few things about the gerbers that are out of date or a little wonky. I recommend that if you print your own, please consider the following information:
1. The PCB is marked for 10R resistors on the power rails. You can use 10R resistors if you want, but it is much safer to use schottsy diodes like the 1n5817. If you do use diodes, PLEASE NOTE that they are not oriented the way that you might guess. Both diodes need to be "pointed" out with the cathode side closest to the side of the PCB. Please see the picture in the folder called "DIODE ORIENTATION".
2. R6 and R9 need to be swapped. When I first printed these PCBs, the COARSE knob was the big knob, but I soon wanted to change this, and the simplist way to do it was to print new front panels and just swap those two resistors around.
3. The holes for the trimmers are a liitle tight. You might consider enlarging them by like 0.2mm if you know KiCad well enough to do that.
