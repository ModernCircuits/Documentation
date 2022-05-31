# Dynamic

The ASIC Dynamic PlugIn is a digital audio effect to edit the volume and dynamic range of an audio signal. It combines the traditional audio effects compressor and expander. In this manual you will learn about the functions of the ASIC Dynamic Audio Effect and how to use them.

On our website modern-circuits.com you will find the manuals of all ASIC PlugIns on the "Support" page as well as separate manuals for the installation and the modulation matrix.

Usage:

The ASIC Dynamic PlugIn is a combination of a compressor and an expander, both controllable via the same user interface. The VLCD graphically displays the current and past compression level. A display shows the gain reduction in decibels (dB). With a click on the expander button in the VLCD, the expander can be operated in the main UI. At the output, an auto gain function is available to balance the level. There is also a sidechain function.

![ASIC Dynamic Screenhot](https://modern-circuits.com/static/media/asic_dynamic_screenshot_small.c115bdaeee7ff0b0318e.png)

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

|    Parameter    |                                                                             Funktion                                                                              |
| :-------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|    Expander     |                        The threshold, ratio, attack, release and soft knee parameters and visualizations on the VLCD now map the expander.                        |
|    Threshold    | Set the threshold at which the compressor/expander starts working. The compressor processes the dynamic range above its threshold, the expander does so below it. |
|      Ratio      |                                            Determine the reduction ratio when the threshold is exceeded or undershot.                                             |
|     Attack      |                                                   Determine the time needed to react to the threshold crossing.                                                   |
|     Release     |                                             Determine the time it takes for the effect to return to its normal state.                                             |
|    Soft Knee    |                                    Determine how fast the set compression takes effect after the threshold has been exceeded.                                     |
| Sidechain Input |                                                     Adjust the input level of the external sidechain signal.                                                      |
|  Expander Sync  |                                                Sets the threshold of the expander equal to that of the compressor.                                                |
|     Filter      |                                    Activate the filter to filter the external sidechain signal before it is processed further.                                    |
|  Filter/Slider  |                                                             Set the frequency of the sidechain filter                                                             |
|     Make Up     |                                                                 Compensates the compressed volume                                                                 |
|     Dry/Wet     |                       Here the ratio of the processed signal with the original signal is processed. For example, for parallel compression.                        |
|    Auto Gain    |                                When activated, the signal is amplified by a level resulting from the ratio of ratio and threshold.                                |

## Additional Resources

We hope we could make the ASIC Dynamic PlugIn understandable with this documentation. Further information is available in our FAQ at [modern-circuits.com/support](https://modern-circuits.com/support). Here you can also find email addresses to contact us.
