#########
 Dynamic
#########

The ASIC Dynamic PlugIn is a digital audio effect to edit the volume and
dynamic range of an audio signal. It combines the traditional audio
effects compressor and expander. In this manual you will learn about the
functions of the ASIC Dynamic Audio Effect and how to use them.

On our website modern-circuits.com you will find the manuals of all ASIC
PlugIns on the "Support" page as well as separate manuals for the
installation and the modulation matrix.

.. image:: https://modern-circuits.com/static/media/asic_dynamic_screenshot_small.c115bdaeee7ff0b0318e.png
   :align: center
   :alt: ASIC Dynamic Screenhot

*******
 Usage
*******

The ASIC Dynamic PlugIn is a combination of a compressor and an
expander, both controllable via the same user interface. The VLCD
graphically displays the current and past compression level. A display
shows the gain reduction in decibels (dB). With a click on the expander
button in the VLCD, the expander can be operated in the main UI. At the
output, an auto gain function is available to balance the level. There
is also a sidechain function.

*********
 Top Bar
*********

.. include:: section/top_bar.rstinc

******
 VLCD
******

.. include:: section/vlcd.rstinc

*********
 Main UI
*********

Expander
   The threshold, ratio, attack, release and soft knee parameters and
   visualizations on the VLCD now map the expander.

Threshold
   Set the threshold at which the compressor/expander starts working.
   The compressor processes the dynamic range above its threshold, the
   expander does so below it.

Ratio
   Determine the reduction ratio when the threshold is exceeded or
   undershot.

Attack
   Determine the time needed to react to the threshold crossing.

Release
   Determine the time it takes for the effect to return to its normal
   state.

Soft Knee
   Determine how fast the set compression takes effect after the
   threshold has been exceeded.

Sidechain Input
   Adjust the input level of the external sidechain signal.

Expander Sync
   Sets the threshold of the expander equal to that of the compressor.

Filter
   Activate the filter to filter the external sidechain signal before it
   is processed further.

Filter/Slider
   Set the frequency of the sidechain filter

Make Up
   Compensates the compressed volume

Dry/Wet
   Here the ratio of the processed signal with the original signal is
   processed. For example, for parallel compression.

Auto Gain
   When activated, the signal is amplified by a level resulting from the
   ratio of ratio and threshold.

**********************
 Additional Resources
**********************

.. include:: section/additional_resources.rstinc
