Filter Manual 04/2022

The ASIC Filter PlugIn is a digital audio effect for equalizing and balancing the frequency characteristics of an audio signal. With five filter bands, you can intervene in any frequency range between 20 Hz - 20,000 Hz. In this tutorial you will learn which functions the ASIC Filter audio effect has and how to use them.
 
On our website modern-circuits.com you will find the manuals of all ASIC PlugIns on the "Support" page as well as separate manuals for the installation and the modulation matrix. 

Usage:
The ASIC Filter PlugIn is an equalizer with five bands. Its cutoff frequencies are 20 Hz in the low-frequency range and 20,000 Hz in the high-frequency range. Frequency ranges can be changed in volume between -12db to +12db. Three of the five bands are available via the MAIN UI, and two can be unlocked via the VLCD. Five different filter curves are available per band. High- and Lowcut are available with a -12db/octave slope as well as with in a -24db/octave and are controllable via Rotary/Slider as well as directly on the VLCD. With the modulation matrix, almost every parameter can be automated. Info about this can be found on modern-circuits.com/support in the manual ASIC Modulations.


Zusammenfassung


Specs
Value
EQ Bands
5
Frequency spectrum
20 Hz - 20.000 Hz
Filter types
Lowcut - Lowshelf - Peak/Bell - Highshelf - Highcut
Slope
-12db/O;-24db/O
Gain
-12db bis +12db
Band Features
Filtertype - Solo - Mute 



                        

Top Bar
VLCD
MAIN UI 

























01 Top Bar 







Die Top Bar hat verschiedene Funktionen. In der Folgenden Tabelle sind die auf dem User Interface verfügbaren Bedienelemente von links nach rechts aufgelistet.


Bedienelement
Funktion 


### "General Top Bar Stuff kommt hierher"

02 VLCD
Der VLCD zeigt den aktuellen Status des PlugIns oder das aktuelle Bearbeitungsmenü.



Seite VLCD
Beschreibung

Audio FX - Diese Seite zeigt den aktuellen Status des Effekts. Im Hintergrund wird das Frequenzspektrum des Inputsignals dargestellt. Die farbige Linie in der Mitte zeigt an welchen Stellen das PlugIn in den Frequenzgang eingreift. Jeder farbige Punkt steht für ein Band. Die Punkte können auf dem VLCD verschoben werden, passen sich aber auch beim Verändern der Parameter im Main UI an. Im Oberen Bereich des VLCDs befinden sich die Bedienelemente für Band 4 und Band 5. Auf der rechten Seite werden Frequenz und Verstärkung angezeigt.

Preset Seite - Diese Seite zeigt alle verfügbaren Presets an. In der linken Spalte steht der Name, auf der rechten Seite der Name der übergeordneten Bank. Im oberen Teil befinden sich zwei Symbole. Mit dem Herz-Symbol können Presets als Favorit markiert werden. Das Symbol mit den sich kreuzenden Pfeilen aktiviert einen Shuffle Modus.   


Sidechain Input - Auf dieser Seite wird das ankommende Sidechain Signal editiert. Zur verfügung stehen dafür ein Gain/Attenuator sowie ein Filter mit High-/Lowcut und Peak.


Einstellungen - Hier befinden sich die Einstellungen des PlugIns.

Envelope Modulator - Auf dieser Seite kann ein Envelope als Modulator für einen Parameter auf dem Main UI konfiguriert werden. Mehr Informationen darüber sind auf morder-circuits.com/support/modualtion-manual verfügbar.

LFO Modulator - Auf dieser Seite kann ein LFO als Modulator für einen Parameter auf dem Main UI konfiguriert werden. Mehr Informationen darüber sind auf morder-circuits.com/support/modualtion-manual verfügbar.

Sequenzer Modulator - Auf dieser Seite kann ein Sequenzer als Modulator für einen Parameter auf dem Main UI konfiguriert werden. Mehr Informationen darüber sind auf morder-circuits.com/support/modualtion-manual verfügbar.





03 Main UI

Parameter
Filterband
Funktion
Frequency 
1,2,3
Determine the frequency to be processed.
Solo
1,2,3
Mute all other bands.
Band Bypass (Knopf mit der Zahl)
1,2,3
Mute/bypass this band.
Gain
1,2,3
Set the gain of this frequency band (-12db - +12db) 
Filter Type 
1,2,3
from left to right:
Lowcut (Slope: -24/db per octave), 
Lowcut  (Slope: -12/db per octave), 
Lowshelf, Peak/Bell Filter, Highshelf; Highcut(Slope: -12/db per octave), Highcut (Slope: -24/db per octave)
Q
1,2,3
Set the quality/width of a band.

4, 5
Parameters for band 4 & 5 at the top of the VLCD. Functions are identical to functions of bands 1, 2, 3.
Frequency/Gain/Q
4, 5
The functions of these bands are only accessible through the VLCD display.



We hope we could make the ASIC Dynamic PlugIn understandable with this documentation. Further information is available in our FAQ at modern-circuits.com/support. Here you can also find email addresses to contact us.



