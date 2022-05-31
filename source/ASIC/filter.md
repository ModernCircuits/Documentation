# Filter

The **ASIC Filter PlugIn** is a digital audio effect for equalizing and balancing the frequency characteristics of an audio signal. With five filter bands, you can intervene in any frequency range between 20 Hz - 20,000 Hz. In this tutorial you will learn which functions the ASIC Filter audio effect has and how to use them.

On our website modern-circuits.com you will find the manuals of **all ASIC PlugIns** on the "Support" page as well as separate manuals for the installation and the modulation matrix.

Usage:
The ASIC Filter PlugIn is an equalizer with five bands. Its cutoff frequencies are 20 Hz in the low-frequency range and 20,000 Hz in the high-frequency range. Frequency ranges can be changed in volume between -12db to +12db. Three of the five bands are available via the MAIN UI, and two can be unlocked via the VLCD. Five different filter curves are available per band. High- and Lowcut are available with a -12db/octave slope as well as with in a -24db/octave and are controllable via Rotary/Slider as well as directly on the VLCD. With the modulation matrix, almost every parameter can be automated. Info about this can be found on modern-circuits.com/support in the manual ASIC Modulations.

```{image} https://modern-circuits.com/static/media/asic_filter_screenshot_small.5d8ecba1df7cd652685c.png
:alt: ASIC Filter Screenhot
:align: center
```

## Summary

|       Specs        |                        Value                        |
| :----------------: | :-------------------------------------------------: |
|      EQ Bands      |                          5                          |
| Frequency spectrum |                  20 Hz - 20.000 Hz                  |
|    Filter types    | Lowcut - Lowshelf - Peak/Bell - Highshelf - Highcut |
|       Slope        |                   -12db/O;-24db/O                   |
|        Gain        |                   -12db bis +12db                   |
|   Band Features    |              Filtertype - Solo - Mute               |

## Top Bar

The Top Bar has various functions. The following table lists the controls available on the user interface from left to right.

| Control Element |                                                                                                                                         Function                                                                                                                                         |
| :-------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|                 |                                                    **Input Volume** - This slider controls the volume of the signal coming from the DAW. The arrow on the outside marks the current status and the level meter visualizes the peaks.                                                     |
|                 |               **Presets** - Use this button to access the predefined effect settings. The icon on the left side opens an extensive list, the name of the current preset is in the middle and the arrow keys on the right side allow you to quickly switch between presets.               |
|                 |                                                                                     **Bypass** - The colored logo of the plug-in is also a bypass button to disable the effect in the signal chain.                                                                                      |
|                 |                                                                                            **Undo/Redo** - With these buttons the last step can be undone and an undone step can be restored.                                                                                            |
|                 |                                                                                                **Save Preset** - Über diesen Knopf können eigene/individuelle Presets gespeichert werden.                                                                                                |
|                 |                                                                                                   **Settings** - Here you can find the technical settings to personalize the software.                                                                                                   |
|                 |                                                        **Sidechain Input** - All plug-ins of the ASIC Bundle have an additional audio input for a sidechain signal. This button takes you to the input processing of this signal.                                                        |
|                 | **Modulation** - The modulation matrix of the ASIC bundle is accessible via this menu. Three different modulators are available, which can be placed on parameters in the main UI by drag'n'drop. Detailed information about the modulators can be found at modern-circuits.com/support. |
|                 |               **Output Volumen** - After the signal has been processed by the audio effect, this slider allows you to adjust the volume that the plug-in sends back to the DAW. It works identically to the input volume slider, but at the other end of the signal flow.                |

## VLCD

The VLCD shows the current status of the PlugIn or the current edit menu.

| Page |                                                                                                                                                                                 Beschreibung                                                                                                                                                                                 |
| :--: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|      | **Audio FX** - This page shows the current status of the compression. On the left is a histogram showing the compression of past peaks for comparison with the current value. In the middle is the gain reduction meter and the expander switch. On the right side is an input/output diagram showing the threshold and ratio. The soft knee function can also be read here. |
|      |                                    **Preset page** - This page shows all available presets. In the left column is the name, on the right side the name of the parent bank. In the upper part there are two icons. The heart icon can be used to mark presets as favorites. The symbol with the crossing arrows activates a shuffle mode.                                     |
|      |                                                                                                    **Sidechain Input** - On this page the incoming sidechain signal is edited. A gain/attenuator and a filter with high/low cut and peak are available for this purpose.                                                                                                     |
|      |                                                                                                                            **Settings** - The settings of the plugin can be found here. Settings - The settings of the plugin can be found here.                                                                                                                             |
|      |                                                    **Envelope modulator** - On this page an envelope can be configured as a modulator for a parameter on the Main UI. More information about this is available on [modern-circuits.com/support/modualtion-manual](https://modern-circuits.com/support/modualtion-manual).                                                    |
|      |                                                         **LFO modulator** - On this page an LFO can be configured as a modulator for a parameter on the Main UI. More information about this is available on [modern-circuits.com/support/modualtion-manual](https://modern-circuits.com/support/modualtion-manual)                                                          |
|      |                                                   **Sequencer modulator** - On this page a sequencer can be configured as a modulator for a parameter on the Main UI. More information about this is available on [modern-circuits.com/support/modualtion-manual](https://modern-circuits.com/support/modualtion-manual).                                                    |

## Main UI

| Parameter |                                                                                                Funktion                                                                                                |
| :-------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Frequency |                                                                                Determine the frequency to be processed.                                                                                |
|   Solo    |                                                                                         Mute all other bands.                                                                                          |
|  Bypass   |                                                                                         Mute/bypass this band.                                                                                         |
|   Gain    |                                                                          Set the gain of this frequency band (-12db - +12db)                                                                           |
|   Type    | from left to right: Lowcut (Slope: -24/db per octave), Lowcut (Slope: -12/db per octave), Lowshelf, Peak/Bell Filter, Highshelf; Highcut(Slope: -12/db per octave), Highcut (Slope: -24/db per octave) |
|     Q     |                                                                                    Set the quality/width of a band.                                                                                    |
|           |                                                Parameters for band 4 & 5 at the top of the VLCD. Functions are identical to functions of bands 1, 2, 3.                                                |
|           |                                                               The functions of these bands are only accessible through the VLCD display.                                                               |

## Additional Resources

We hope we could make the ASIC Filter PlugIn understandable with this documentation. Further information is available in our FAQ at [modern-circuits.com/support](https://modern-circuits.com/support). Here you can also find email addresses to contact us.
