#######
 Space
#######

The ASIC Space PlugIn is a digital audio effect for creating artificial
space, reverberation and delay. It is a combination of two traditional
audio effects (reverb and delay) and offers the possibility to match
them with complementary effects. Learn in this tutorial what features
the ASIC Space Audio effect brings and how to operate them.

On our website modern-circuits.com under "Support" you will find the
manuals of all ASIC PlugIns as well as separate manuals for installation
and the modulation matrix.

.. image:: https://modern-circuits.com/static/media/asic_space_screenshot_small.5fe1d80d17742b965fd5.png
   :align: center
   :alt: ASIC Space Screenhot

*******
 Usage
*******

With the ASIC Space an artificial spatiality can be created and added to
the original singal. The processing is divided between the Reverb and
Delay effects. The subdivision is shown in color: Blue represents the
Delay, purple the Reverb. The Main UI can be used to adjust these
effects to the input signal and mix.

*********
 Top Bar
*********

.. include:: section/top_bar.rstinc

******
 VLCD
******

The VLCD shows the current status of the PlugIn or the current edit
menu.

This page shows the current status of the effect. It is divided into two
sections. The different colors represent the two effects. The left area
represents a room in the form of an X/Y diagram. The X-axis represents
the stereo panorama (left/right). The Y-axis represents the dimension of
the room. The effects can be distributed in the room in this way. The
right area shows the filters used to process the wet signal and how they
work together. Here the filter curve can be edited.

.. include:: section/vlcd.rstinc

*********
 Main UI
*********

Delay Time Left
   Setting of the delay time for the left side of the stereo delay in
   milliseconds.

Delay Time Right
   Setting of the delay time for the right side of the stereo delay in
   milliseconds.

Sync
   Synchronize the delay time with the BPM of the host DAW. This changes
   the unit of the delay time from milliseconds to relative clock units.

L/R Link
   Link the parameters "Delay Time Left" and "Delay Time Right". This
   way both parameters act synchronously, no matter which one you press.

Cutoff
   Adjust the cutoff frequency of the filter of the delay signal.
   Available are Low Cut, High Cut and Peak Filter - adjustable via the
   VLCD.

Feedback
   The feedback indicates what percentage of the signal from the last
   delay cycle is included in the next one.

Delay Dry/Wet
   Here you can adjust the ratio of the original and the pure delay
   signal.

Delay Mute
   Here you can remove the delay effect from the signal chain.

Blend
   With this slider you can mix the proportion of the two effects in the
   output signal.

Size
   Here you can set the size and reverberation time of the reverb.

Predelay
   Adjust the time until the onset of the first early reflections.

Damp
   Here you can set the absorption coefficient of high frequencies in
   the simulated room. The higher the value, the higher the absorption
   value.

HP Filter
   Filter the low frequencies from the reverb.

LP Filter
   Filter the high frequencies from the reverb.

Reverb Dry/Wet
   Filter the high frequencies from the reverb.

Reverb Mute
   Here you can remove the reverb effect from the signal chain.

**********************
 Additional Resources
**********************

.. include:: section/additional_resources.rstinc
