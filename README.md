# Sack-Lunch-VCO
A simple AS3340-based VCO for eurorack

This VCO was designed using a number of open source schematics as well as the AS3340's data sheet. It is nothing fancy, but it gets the job done, like a sack lunch.\

You can find the schematic here as well as gerbers for the PCBs and front panel. If you want to make your own front panel, you can use the edgecuts files here to get the exact outline.

<b>If you want to print this yourself</b>
<br>Please be aware, I have made a few changes to these gerbers since I last printed them. The changes were minor, but I have not verified them myself. Print at your own (very small) risk.
<br><br>To print, download <a href="https://github.com/moonfriendsynth/Sack-Lunch-VCO/blob/2d1b4b25dfa2b1dbcb76dec84105f6ccebe1b944/Sack%20Lunch%20VCO%20Board%20A%20Gerber.zip">Sack Lunch VCO Board A Gerbers.zip</a>, <a href="https://github.com/moonfriendsynth/Sack-Lunch-VCO/blob/2d1b4b25dfa2b1dbcb76dec84105f6ccebe1b944/Sack%20Lunch%20VCO%20Board%20B%20Gerber.zip">Sack Lunch VCO Board B Gerbers.zip</a>, and <a href="https://github.com/moonfriendsynth/Sack-Lunch-VCO/blob/2d1b4b25dfa2b1dbcb76dec84105f6ccebe1b944/VCO%20Front%20Plate/VCO%20Gerbers/VCO%20Front%20Plate%20Gerbers.zip">VCO Front Plate Gerbers.zip</a>. I used JLCPCB to print mine, and you can probably get these for about $10-15 plus shipping (which is another $15). Or email me moonfriendsynth@gmail.com and I'll send you the previous version (which still works just as good with two minor changes) for like $5.

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
