# Shape

The ASIC Shape PlugIn is a digital audio effect for creating artificial harmonics and distortion. Through various algorithms, a range of different distortion effects can be applied to the signal. In this tutorial you will learn about the functions of the ASIC Shape audio effect and how to use them.

On our website modern-circuits.com you will find the manuals of **all ASIC PlugIns** on the "Support" page as well as separate manuals for the installation and the modulation matrix.

Usage:
The ASIC Shape can be used to artificially distort a signal. To make the processing as detailed as possible, various processing tools are available. Besides the selection of one of the 10 algorithms, two filters, an envelope follower and a transient designer are available. These effects can be adjusted to the input signal and the mix via the Main UI.

```{image} https://modern-circuits.com/static/media/asic_shape_screenshot_small.803961c9dbc798e8ce75.png
:alt: ASIC Shape Screenhot
:align: center
```

|    Algorithmen     |                                            Beschreibung                                            |
| :----------------: | :------------------------------------------------------------------------------------------------: |
|     Saturation     |                             Increase saturation by slight distortion.                              |
|     Brickwall      |                        Classic clip distortion that cuts the waveform hard.                        |
|        Sine        |                              Classic distortion by the sine function.                              |
|        Tan         |                            Classic distortion by the tangent function.                             |
| Reversed Brickwall |      Classic clip distortion that negatively flips down all values above the clip threshold.       |
|       Floor        | Classic clip distortion, which maps all values above the clip threshold offset from the zero line. |
|  Anti-Saturation   |                       Boosts already loud samples and reduces quiet samples.                       |
|      Rectify       |                                Sets all samples to positive values                                 |
|      Aliasing      |                                Classic reduction of the sample rate                                |
|       Modulo       |              Uses the mathematical calculation operation "Modulo" to modify the wave               |

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

- **Audio FX** - This page shows the current status of the compression. On the left is a histogram showing the compression of past peaks for comparison with the current value. In the middle is the gain reduction meter and the expander switch. On the right side is an input/output diagram showing the threshold and ratio. The soft knee function can also be read here.
- **Preset page** - This page shows all available presets. In the left column is the name, on the right side the name of the parent bank. In the upper part there are two icons. The heart icon can be used to mark presets as favorites. The symbol with the crossing arrows activates a shuffle mode.
- **Sidechain Input** - On this page the incoming sidechain signal is edited. A gain/attenuator and a filter with high/low cut and peak are available for this purpose.
- **Settings** - The settings of the plugin can be found here. Settings - The settings of the plugin can be found here.
- **Envelope modulator** - On this page an envelope can be configured as a modulator for a parameter on the Main UI. More information about this is available on [modern-circuits.com/support/modualtion-manual](https://modern-circuits.com/support/modualtion-manual).
- **LFO modulator** - On this page an LFO can be configured as a modulator for a parameter on the Main UI. More information about this is available on [modern-circuits.com/support/modualtion-manual](https://modern-circuits.com/support/modualtion-manual)
- **Sequencer modulator** - On this page a sequencer can be configured as a modulator for a parameter on the Main UI. More information about this is available on [modern-circuits.com/support/modualtion-manual](https://modern-circuits.com/support/modualtion-manual).

## Main UI

- **Drive** Determine how much influence the distortion has on the original signal.
- **Trim** Adjust the volume of the distorted signal.
- **Select** Here is the selection of the different distortion algorithms.
- **Pre/Post** The plug-in comes with two filters that are placed at different points in the signal chain: The Pre Filter before the distortion (Input Signal) - the Post Filter after the distortion (Output Signal). With these buttons you can switch between the filters. The following parameters (Cutoff/Filter Curves and Q) adjust to this selection.
- **Cutoff** Adjust the crossover frequency at which the filter starts filtering.
- **Filterkurven** Choose from three different filter curves. High pass, low pass and bell band.
- **Q** Adjust the quality of the filter.
- **Follow** This is an envelope follower that can modulate the pre-filter based on the envelope of the input signal. "Follow" controls the intensity with the envelope mapping in the filter movement.
- **Attack** Controls how fast the pre-filter reacts to an input signal.
- **Release** Controls how long the pre-filter takes to return to its original position after modulation by the envelope follower.
- **Transient Attack** Here the volume of the transients can be raised or lowered.
- **Transient Sustain** Here you can raise or lower the volume of the signal behind the transients.
- **Dry/Wet** Dry/Wet determines the ratio of processed and unprocessed signal at the output.

We hope we could make the ASIC Shape PlugIn understandable with this documentation. Further information is available in our FAQ at [modern-circuits.com/support](https://modern-circuits.com/support). Here you can also find email addresses to contact us.
