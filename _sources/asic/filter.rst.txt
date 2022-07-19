########
 Filter
########

The **ASIC Filter PlugIn** is a digital audio effect for equalizing and
balancing the frequency characteristics of an audio signal. With five
filter bands, you can intervene in any frequency range between 20 Hz -
20,000 Hz. In this tutorial you will learn which functions the ASIC
Filter audio effect has and how to use them.

On our website modern-circuits.com you will find the manuals of **all
ASIC PlugIns** on the "Support" page as well as separate manuals for the
installation and the modulation matrix.

.. image:: https://modern-circuits.com/static/media/asic_filter_screenshot_small.5d8ecba1df7cd652685c.png
   :align: center
   :alt: ASIC Filter Screenhot

*******
 Usage
*******

The ASIC Filter PlugIn is an equalizer with five bands. Its cutoff
frequencies are 20 Hz in the low-frequency range and 20,000 Hz in the
high-frequency range. Frequency ranges can be changed in volume between
-12db to +12db. Three of the five bands are available via the MAIN UI,
and two can be unlocked via the VLCD. Five different filter curves are
available per band. High- and Lowcut are available with a -12db/octave
slope as well as with in a -24db/octave and are controllable via
Rotary/Slider as well as directly on the VLCD. With the modulation
matrix, almost every parameter can be automated. Info about this can be
found on modern-circuits.com/support in the manual ASIC Modulations.

+--------------------+-----------------------------------------------------+
| Spec               | Value                                               |
+====================+=====================================================+
| EQ Bands           | 5                                                   |
+--------------------+-----------------------------------------------------+
| Frequency spectrum | 20 Hz - 20.000 Hz                                   |
+--------------------+-----------------------------------------------------+
| Filter types       | Lowcut - Lowshelf - Peak/Bell - Highshelf - Highcut |
+--------------------+-----------------------------------------------------+
| Slope              | -12db/O;-24db/O                                     |
+--------------------+-----------------------------------------------------+
| Gain               | -12db bis +12db                                     |
+--------------------+-----------------------------------------------------+
| Band Features      | Filtertype - Solo - Mute                            |
+--------------------+-----------------------------------------------------+

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

Frequency
   Determine the frequency to be processed.

Solo
   Mute all other bands.

Bypass
   Mute/bypass this band.

Gain
   Set the gain of this frequency band (-12db - +12db)

Type
   -  Lowcut (Slope: -24/db per octave)
   -  Lowcut (Slope: -12/db per octave)
   -  Lowshelf
   -  Peak/Bell Filter
   -  Highshelf
   -  Highcut (Slope: -12/db per octave)
   -  Highcut (Slope: -24/db per octave)

Q
   Set the quality/width of a band.

**********************
 Additional Resources
**********************

.. include:: section/additional_resources.rstinc
