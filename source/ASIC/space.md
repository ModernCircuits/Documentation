Space Manual 04/2022

The ASIC Space PlugIn is a digital audio effect for creating artificial space, reverberation and delay. It is a combination of two traditional audio effects (reverb and delay) and offers the possibility to match them with complementary effects. Learn in this tutorial what features the ASIC Space Audio effect brings and how to operate them.
 
On our website modern-circuits.com under "Support" you will find the manuals of all ASIC PlugIns as well as separate manuals for installation and the modulation matrix.

Application:
With the ASIC Space an artificial spatiality can be created and added to the original singal. The processing is divided between the Reverb and Delay effects. The subdivision is shown in color: Blue represents the Delay, purple the Reverb. The Main UI can be used to adjust these effects to the input signal and mix.





                        
Top Bar
VLCD
MAIN UI 


















02 VLCD
Der VLCD zeigt den aktuellen Status des PlugIns oder das aktuelle Bearbeitungsmenü.



Seite VLCD
Beschreibung

Audio FX - This page shows the current status of the effect. It is divided into two sections. The different colors represent the two effects.
The left area represents a room in the form of an X/Y diagram. The X-axis represents the stereo panorama (left/right). The Y-axis represents the dimension of the room. The effects can be distributed in the room in this way.
The right area shows the filters used to process the wet signal and how they work together. Here the filter curve can be edited.


03 Main UI

Parameter
Effekt
Funktion
Delay Time Left
Delay
Setting of the delay time for the left side of the stereo delay in milliseconds.
Delay Time Right
Delay
Setting of the delay time for the right side of the stereo delay in milliseconds.
Sync
Delay
Synchronize the delay time with the BPM of the host DAW. This changes the unit of the delay time from milliseconds to relative clock units.
L/R Link
Delay
Link the parameters "Delay Time Left" and "Delay Time Right". This way both parameters act synchronously, no matter which one you press.
Cutoff
Delay
Adjust the cutoff frequency of the filter of the delay signal. Available are Low Cut, High Cut and Peak Filter - adjustable via the VLCD.
Feedback
Delay
The feedback indicates what percentage of the signal from the last delay cycle is included in the next one. 
Delay Dry/Wet
Delay
Here you can adjust the ratio of the original and the pure delay signal.
Delay Mute
Delay
Here you can remove the delay effect from the signal chain. 
Blend
Delay / Reverb
With this slider you can mix the proportion of the two effects in the output signal.
Size
Reverb
Here you can set the size and reverberation time of the reverb.
Predelay
Reverb
Adjust the time until the onset of the first early reflections.
Damp
Reverb
Here you can set the absorption coefficient of high frequencies in the simulated room. The higher the value, the higher the absorption value.
HP Filter
Reverb
Filter the low frequencies from the reverb
LP Filter
Reverb
Filter the high frequencies from the reverb
Reverb Dry/Wet
Reverb
Filter the high frequencies from the reverb
Reverb Mute
Reverb
Here you can remove the reverb effect from the signal chain.




We hope we could make the ASIC Space PlugIn understandable with this documentation. Further information is available in our FAQ at modern-circuits.com/support. Here you can also find email addresses to contact us.
