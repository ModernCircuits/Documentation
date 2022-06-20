# Filter

Das ASIC Space PlugIn ist ein digitaler Audio Effekt zum Erzeugen von künstlicher Räumlichkeit, Nachhall und Verzögerung. Es ist eine Kombination aus zwei traditionellen Audioeffekten (Reverb und Delay) und bietet die Möglichkeit diese mit ergänzenden Effekten aufeinander abzustimmen. Erfahren Sie in dieser Anleitung, welche Funktionen der ASIC Space Audio Effekt mitbringt und wie diese bedient werden können.

Auf unserer Internetseite modern-circuits.com finden sie unter “Support” die Anleitungen aller ASIC PlugIns sowie gesonderte Anleitungen zur Installation und der Modulationsmatrix.

Anwendung:
Mit dem ASIC Space kann eine künstliche Räumlichkeit erzeugt und dem originalen Singal hinzugefügt werden. Die Bearbeitung wird zwischen den Effekten Reverb und Delay unterteilt. Die Unterteilung wird farblich dargestellt: Blau steht für das Delay, Violett für das Reverb. Über das Main UI können diese Effekte an das Eingangssignal und den Mix angepasst werden.

```{image} https://modern-circuits.com/static/media/asic_space_screenshot_small.5fe1d80d17742b965fd5.png
:alt: ASIC Space Screenhot
:align: center
```

## General Top Bar Stuff kommt hierher

02 VLCD
Der VLCD zeigt den aktuellen Status des PlugIns oder das aktuelle Bearbeitungsmenü.

Seite VLCD
Beschreibung

Audio FX - Diese Seite zeigt den aktuellen Status des Effekts. Sie ist in zwei Bereiche unterteilt. Die verschiedenen Farben stehen dabei für die beiden Effekte.
Der linke Bereich stellt einen Raum in Form eines X/Y Diagramms dar. Die X-Achse steht für das Stereo Panorama (Links/Rechts). Die Y-Achse für die Dimension des Raums. Die Effekte können so im Raum verteilt werden.
Der rechte Bereich zeigt die Filter, mit denen das Wet-Signal bearbeitet wird und wie diese miteinander funktionieren. Hier kann die Filterkurve bearbeitet werden.

Preset Seite - Diese Seit zeigt alle verfügbaren Presets an. In der linken Spalte steht der Name, auf der rechten Seite der Name der übergeordneten Bank. Im oberen Teil befinden sich zwei Symbole. Mit dem Herz-Symbol können Presets als Favorit markiert werden. Das Symbol mit den sich kreuzenden Pfeilen aktiviert einen Shuffle Modus.

Sidechain Input - Auf dieser Seite wird das ankommende Sidechain Signal editiert. Zur verfügung stehen dafür ein Gain/Attenuator sowie ein Filter mit High-/Lowcut und Peak.

Einstellungen - Hier befinden sich die Einstellungen des PlugIns.

Envelope Modulator - Auf dieser Seite kann ein Envelope als Modulator für einen Parameter auf dem Main UI konfiguriert werden. Mehr Informationen darüber sind auf morder-circuits.com/support verfügbar.

LFO Modulator - Auf dieser Seite kann ein LFO als Modulator für einen Parameter auf dem Main UI konfiguriert werden. Mehr Informationen darüber sind auf morder-circuits.com/support/modualtion-manual verfügbar.

Sequenzer Modulator - Auf dieser Seite kann ein Sequenzer als Modulator für einen Parameter auf dem Main UI konfiguriert werden. Mehr Informationen darüber sind auf morder-circuits.com/support/modualtion-manual verfügbar.

03 Main UI

Parameter
Effekt
Funktion
Delay Time Left
Delay
Einstellung der Verzögerungszeit für die linke Seite des Stereo-Delays in Millisekunden.
Delay Time Right
Delay
Einstellung der Verzögerungszeit für die rechte Seite des Stereo-Delays in Millisekunden.
Sync
Delay
Synchronisiere die Delay Zeit mit der BPM der Host DAW. Dadurch ändert sich die Einheit der Delay Zeit von Millisekunden in relative Takteinheiten.
L/R Link
Delay
Verknüpfe die Parameter “Delay Time Left” und “Delay Time Right”. Dadurch agieren beide Parameter synchron, egal welchen Sie betätigen.
Cutoff
Delay
Reguliere die Trennfrequenz des Filter des Delay Signals. Zur Verfügung stehen Low Cut, High Cut und Peakfilter- Einstellbar über den VLCD.
Feedback
Delay
Das Feedback gibt an, wie viel Prozent des Signals aus dem letzten Delay-Zyklus’ in den nächsten mit aufgenommen wird.
Delay Dry/Wet
Delay
Hier lässt sich das Verhältnis des originalen und des reinen Delay Signals regeln.
Delay Mute
Delay
Hier kann der Delay Effekt aus der Signalkette genommen werden.
Blend
Delay / Reverb
Mit diesem Slider können die den Anteil der beiden Effekte am Ausgangssignal mischen.
Size
Reverb
Hier kann die Größe und Nachhallzeit des Reverbs eingestellt werden.
Predelay
Reverb
Justiere die Zeit bis zum Einsetzten der ersten frühen Reflexionen.
Damp
Reverb
Hier kann der Absorptionsgrad hoher Frequenzen im simulierten Raum eingestellt werden. Je höher der Wert, desto höher der Absorptionswert.
HP Filter
Reverb
Filtere die tiefen Frequenzen aus den Hall
LP Filter
Reverb
Filtere die hohen Frequenzen aus den Hall
Reverb Dry/Wet
Reverb
Hier lässt sich das Verhältnis des originalen und des reinen Reverb Signals regeln.
Reverb Mute
Reverb
Hier kann der Reverb Effekt aus der Signalkette genommen werden.

Wir hoffen, wir konnten mit dieser Dokumentation dass ASIC Space PlugIn verständlich machen. Weiter Infos stehen in unserem FAQ über modern-circuits.com/support zur Verfügung. Hier finden sie auch E-Mail Adressen um Kontakt zu uns aufzunehmen.
