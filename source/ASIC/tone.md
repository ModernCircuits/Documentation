# Tone

The ASIC Tone PlugIn is a digital audio effect for technically adjusting an atonal audio signal using a filter bank. It can be interpreted as a frequency-based tuner and influences the linear or natural harmonic spectrum. In this tutorial you will learn which functions the ASIC Tone audio effect has and how to use them.

On our website modern-circuits.com you will find the manuals of all ASIC PlugIns on the "Support" page as well as separate manuals for the installation and the modulation matrix.

**Usage:**
ASIC Tone can be used to quickly edit frequency bands that belong together. The basis is either a diatonic note or a freely selectable fundamental frequency. Based on this base, the plug-in calculates the associated harmonics and automatically sets filter bands. These can be changed by the Main UI in their volume, their Q-factor and their number.

```{image} https://modern-circuits.com/static/media/asic_tone_screenshot_small.5b1fae143a47a6cb4a98.png
:alt: ASIC Tone Screenhot
:align: center
```

## Top Bar

The Top Bar has various functions. The following table lists the controls available on the user interface from left to right.

- **Input Volume** - This slider controls the volume of the signal coming from the DAW. The arrow on the outside marks the current status and the level meter visualizes the peaks.
- **Presets** - Use this button to access the predefined effect settings. The icon on the left side opens an extensive list, the name of the current preset is in the middle and the arrow keys on the right side allow you to quickly switch between presets.
- **Bypass** - The colored logo of the plug-in is also a bypass button to disable the effect in the signal chain.
- **Undo/Redo** - With these buttons the last step can be undone and an undone step can be restored.
- **Save Preset** - Über diesen Knopf können eigene/individuelle Presets gespeichert werden.
- **Settings** - Here you can find the technical settings to personalize the software.
- **Sidechain Input** - All plug-ins of the ASIC Bundle have an additional audio input for a sidechain signal. This button takes you to the input processing of this signal.
- **Modulation** - The modulation matrix of the ASIC bundle is accessible via this menu. Three different modulators are available, which can be placed on parameters in the main UI by drag'n'drop. Detailed information about the modulators can be found at modern-circuits.com/support.
- **Output Volumen** - After the signal has been processed by the audio effect, this slider allows you to adjust the volume that the plug-in sends back to the DAW. It works identically to the input volume slider, but at the other end of the signal flow.

## VLCD

The VLCD shows the current status of the PlugIn or the current edit menu.

- **Audio FX** - Diese Seite zeigt den aktuellen Status des Effekts. Grundlage ist ein Frequenzspektrum von 20Hz bis 20kHz. Das Frequenzspektrum den Ankommenden Signals wird in Echtzeit dargestellt.
- **Preset page** - This page shows all available presets. In the left column is the name, on the right side the name of the parent bank. In the upper part there are two icons. The heart icon can be used to mark presets as favorites. The symbol with the crossing arrows activates a shuffle mode.
- **Sidechain Input** - On this page the incoming sidechain signal is edited. A gain/attenuator and a filter with high/low cut and peak are available for this purpose.
- **Settings** - The settings of the plugin can be found here. Settings - The settings of the plugin can be found here.
- **Envelope modulator** - On this page an envelope can be configured as a modulator for a parameter on the Main UI. More information about this is available on [modern-circuits.com/support/modualtion-manual](https://modern-circuits.com/support/modualtion-manual).
- **LFO modulator** - On this page an LFO can be configured as a modulator for a parameter on the Main UI. More information about this is available on [modern-circuits.com/support/modualtion-manual](https://modern-circuits.com/support/modualtion-manual)
- **Sequencer modulator** - On this page a sequencer can be configured as a modulator for a parameter on the Main UI. More information about this is available on [modern-circuits.com/support/modualtion-manual](https://modern-circuits.com/support/modualtion-manual).

## Main UI

- **Note/Frequency:** This is the basis of the plug-in's processing. Note describes the frequency of one of the 12 tones from F - E. Frequency cancels the scaling in diatonic frequencies and lets you freely determine any frequency.
- **Intensity:** Here the gain of all generated bands is controlled. Here it can be amplified but also lowered.
- **Mode:** Here there is the possibility to switch between a linear and the natural overtone spectrum.
- **Clarity:** Clarity edits the quality of the individual bands.
- **Resolution:** This sets the number of overtones that match the root note.
- **Octave:** Here the root note can be shifted in the octave.
- **Dry/Wet:** Here the ratio of the processed signal with the original signal is processed.

We hope we could make the ASIC Tone PlugIn understandable with this documentation. Further information is available in our FAQ at [modern-circuits.com/support](https://modern-circuits.com/support). Here you can also find email addresses to contact us.
