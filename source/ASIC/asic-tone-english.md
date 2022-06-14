Tone Manual 04/2022

The ASIC Tone PlugIn is a digital audio effect for technically adjusting an atonal audio signal using a filter bank. It can be interpreted as a frequency-based tuner and influences the linear or natural harmonic spectrum. In this tutorial you will learn which functions the ASIC Tone audio effect has and how to use them.
 
On our website modern-circuits.com you will find the manuals of all ASIC PlugIns on the "Support" page as well as separate manuals for the installation and the modulation matrix. 

 
Usage:
ASIC Tone can be used to quickly edit frequency bands that belong together. The basis is either a diatonic note or a freely selectable fundamental frequency. Based on this base, the plug-in calculates the associated harmonics and automatically sets filter bands. These can be changed by the Main UI in their volume, their Q-factor and their number.


Specs
Value
Root Note
lowest: F-1;  highest: E8
Oktaven
8
Resolution
up to 20 Bands
Overtone scale 
natural, linear 

                        
Top Bar
VLCD
MAIN UI 









### "General Top Bar Stuff kommt hierher"








02 VLCD
Der VLCD zeigt den aktuellen Status des PlugIns oder das aktuelle Bearbeitungsmenü.



Seite VLCD
Beschreibung

Audio FX - Diese Seite zeigt den aktuellen Status des Effekts. Grundlage ist ein Frequenzspektrum von 20Hz bis 20kHz. Das Frequenzspektrum den Ankommenden Signals wird in Echtzeit dargestellt. 
Die vertikalen Balken stehen hier für die Frequenzbereiche, die vom PlugIn bearbeitet werden. Sie stellen die Bänder dar. 
Die mittigen Kegel stehen zur individuellen Verstärkung und Abschwächung pro Band zur verfügung. 
Anzahl und Position der Bänder lässt sich über das Main UI Kontrollieren. 
Auf dieser VLCD Seite kann das Arbeiten durch eine Zoom Funktion detailliert werden, sowie alle Bänder im Gain zurückgesetzt werden.

Preset Seite - Diese Seit zeigt alle verfügbaren Presets an. In der linken Spalte steht der Name, auf der rechten Seite der Name der übergeordneten Bank. Im oberen Teil befinden sich zwei Symbole. Mit dem Herz-Symbol können Presets als Favorit markiert werden. Das Symbol mit den sich kreuzenden Pfeilen aktiviert einen Shuffle Modus.   


Sidechain Input - Auf dieser Seite wird das ankommende Sidechain Signal editiert. Zur verfügung stehen dafür ein Gain/Attenuator sowie ein Filter mit High-/Lowcut und Peak.


Einstellungen - Hier befinden sich die Einstellungen des PlugIns.

Envelope Modulator - Auf dieser Seite kann ein Envelope als Modulator für einen Parameter auf dem Main UI konfiguriert werden. Mehr Informationen darüber sind auf morder-circuits.com/support/modualtion-manual verfügbar.

LFO Modulator - Auf dieser Seite kann ein LFO als Modulator für einen Parameter auf dem Main UI konfiguriert werden. Mehr Informationen darüber sind auf morder-circuits.com/support/modualtion-manual verfügbar.

Sequenzer Modulator - Auf dieser Seite kann ein Sequenzer als Modulator für einen Parameter auf dem Main UI konfiguriert werden. Mehr Informationen darüber sind auf morder-circuits.com/support/modualtion-manual verfügbar.


03 Main UI

Parameter
Funktion
Note/Frequency 
This is the basis of the plug-in's processing. Note describes the frequency of one of the 12 tones from F - E. Frequency cancels the scaling in diatonic frequencies and lets you freely determine any frequency. 
Intensity 
Here the gain of all generated bands is controlled. Here it can be amplified but also lowered.
Mode
Here there is the possibility to switch between a linear and the natural overtone spectrum.
Clarity
Clarity edits the quality of the individual bands.
Resolution
This sets the number of overtones that match the root note.
Octave
Here the root note can be shifted in the octave.
Dry/Wet
Here the ratio of the processed signal with the original signal is processed.



We hope we could make the ASIC Dynamic PlugIn understandable with this documentation. Further information is available in our FAQ at modern-circuits.com/support. Here you can also find email addresses to contact us.

