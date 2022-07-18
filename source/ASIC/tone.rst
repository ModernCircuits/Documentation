######
 Tone
######

.. contents::
   :local:

The ASIC Tone PlugIn is a digital audio effect for technically adjusting
an atonal audio signal using a filter bank. It can be interpreted as a
frequency-based tuner and influences the linear or natural harmonic
spectrum. In this tutorial you will learn which functions the ASIC Tone
audio effect has and how to use them.

On our website modern-circuits.com you will find the manuals of all ASIC
PlugIns on the "Support" page as well as separate manuals for the
installation and the modulation matrix.

.. image:: https://modern-circuits.com/static/media/asic_tone_screenshot_small.5b1fae143a47a6cb4a98.png
   :align: center
   :alt: ASIC Tone Screenhot

*******
 Usage
*******

ASIC Tone can be used to quickly edit frequency bands that belong
together. The basis is either a diatonic note or a freely selectable
fundamental frequency. Based on this base, the plug-in calculates the
associated harmonics and automatically sets filter bands. These can be
changed by the Main UI in their volume, their Q-factor and their number.

*********
 Top Bar
*********

.. include:: section/top_bar.rstinc

******
 VLCD
******

Diese Seite zeigt den aktuellen Status des Effekts. Grundlage ist ein
Frequenzspektrum von 20Hz bis 20kHz. Das Frequenzspektrum den
Ankommenden Signals wird in Echtzeit dargestellt.

.. include:: section/vlcd.rstinc

*********
 Main UI
*********

Note/Frequency
   This is the basis of the plug-in's processing. Note describes the
   frequency of one of the 12 tones from F - E. Frequency cancels the
   scaling in diatonic frequencies and lets you freely determine any
   frequency.

Intensity
   Here the gain of all generated bands is controlled. Here it can be
   amplified but also lowered.

Mode
   Here there is the possibility to switch between a linear and the
   natural overtone spectrum.

Clarity
   Clarity edits the quality of the individual bands.

Resolution
   This sets the number of overtones that match the root note.

Octave
   Here the root note can be shifted in the octave.

Dry/Wet
   Here the ratio of the processed signal with the original signal is
   processed.

**********************
 Additional Resources
**********************

.. include:: section/additional_resources.rstinc
