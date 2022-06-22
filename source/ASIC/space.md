# Space

The ASIC Space PlugIn is a digital audio effect for creating artificial space, reverberation and delay. It is a combination of two traditional audio effects (reverb and delay) and offers the possibility to match them with complementary effects. Learn in this tutorial what features the ASIC Space Audio effect brings and how to operate them.

On our website modern-circuits.com under "Support" you will find the manuals of all ASIC PlugIns as well as separate manuals for installation and the modulation matrix.

**Usage:**

With the ASIC Space an artificial spatiality can be created and added to the original singal. The processing is divided between the Reverb and Delay effects. The subdivision is shown in color: Blue represents the Delay, purple the Reverb. The Main UI can be used to adjust these effects to the input signal and mix.

```{image} https://modern-circuits.com/static/media/asic_space_screenshot_small.5fe1d80d17742b965fd5.png
:alt: ASIC Space Screenhot
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

- **Audio FX** - This page shows the current status of the effect. It is divided into two sections. The different colors represent the two effects. The left area represents a room in the form of an X/Y diagram. The X-axis represents the stereo panorama (left/right). The Y-axis represents the dimension of the room. The effects can be distributed in the room in this way. The right area shows the filters used to process the wet signal and how they work together. Here the filter curve can be edited.
- **Preset page** - This page shows all available presets. In the left column is the name, on the right side the name of the parent bank. In the upper part there are two icons. The heart icon can be used to mark presets as favorites. The symbol with the crossing arrows activates a shuffle mode.
- **Sidechain Input** - On this page the incoming sidechain signal is edited. A gain/attenuator and a filter with high/low cut and peak are available for this purpose.
- **Settings** - The settings of the plugin can be found here. Settings - The settings of the plugin can be found here.
- **Envelope modulator** - On this page an envelope can be configured as a modulator for a parameter on the Main UI. More information about this is available on [modern-circuits.com/support/modualtion-manual](https://modern-circuits.com/support/modualtion-manual).
- **LFO modulator** - On this page an LFO can be configured as a modulator for a parameter on the Main UI. More information about this is available on [modern-circuits.com/support/modualtion-manual](https://modern-circuits.com/support/modualtion-manual)
- **Sequencer modulator** - On this page a sequencer can be configured as a modulator for a parameter on the Main UI. More information about this is available on [modern-circuits.com/support/modualtion-manual](https://modern-circuits.com/support/modualtion-manual).

## Main UI

- **Delay Time Left:** Setting of the delay time for the left side of the stereo delay in milliseconds.
- **Delay Time Right:** Setting of the delay time for the right side of the stereo delay in milliseconds.
- **Sync:** Synchronize the delay time with the BPM of the host DAW. This changes the unit of the delay time from milliseconds to relative clock units.
- **L/R Link:** Link the parameters "Delay Time Left" and "Delay Time Right". This way both parameters act synchronously, no matter which one you press.
- **Cutoff:** Adjust the cutoff frequency of the filter of the delay signal. Available are Low Cut, High Cut and Peak Filter - adjustable via the VLCD.
- **Feedback:** The feedback indicates what percentage of the signal from the last delay cycle is included in the next one.
- **Delay Dry/Wet:** Here you can adjust the ratio of the original and the pure delay signal.
- **Delay Mute:** Here you can remove the delay effect from the signal chain.
- **Blend:** With this slider you can mix the proportion of the two effects in the output signal.
- **Size:** Here you can set the size and reverberation time of the reverb.
- **Predelay:** Adjust the time until the onset of the first early reflections.
- **Damp:** Here you can set the absorption coefficient of high frequencies in the simulated room. The higher the value, the higher the absorption value.
- **HP Filter:** Filter the low frequencies from the reverb.
- **LP Filter:** Filter the high frequencies from the reverb.
- **Reverb Dry/Wet:** Filter the high frequencies from the reverb.
- **Reverb Mute:** Here you can remove the reverb effect from the signal chain.

We hope we could make the ASIC Space PlugIn understandable with this documentation. Further information is available in our FAQ at [modern-circuits.com/support](https://modern-circuits.com/support). Here you can also find email addresses to contact us.
