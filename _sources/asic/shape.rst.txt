#######
 Shape
#######

The ASIC Shape PlugIn is a digital audio effect for creating artificial
harmonics and distortion. Through various algorithms, a range of
different distortion effects can be applied to the signal. In this
tutorial you will learn about the functions of the ASIC Shape audio
effect and how to use them.

On our website modern-circuits.com you will find the manuals of **all
ASIC PlugIns** on the "Support" page as well as separate manuals for the
installation and the modulation matrix.

.. image:: https://modern-circuits.com/static/media/asic_shape_screenshot_small.803961c9dbc798e8ce75.png
   :align: center
   :alt: ASIC Shape Screenhot

*******
 Usage
*******

The ASIC Shape can be used to artificially distort a signal. To make the
processing as detailed as possible, various processing tools are
available. Besides the selection of one of the 10 algorithms, two
filters, an envelope follower and a transient designer are available.
These effects can be adjusted to the input signal and the mix via the
Main UI.

Algorithms
==========

Saturation
   Increase saturation by slight distortion.

Brickwall
   Classic clip distortion that cuts the waveform hard.

Sine
   Classic distortion by the sine function.

Tan
   Classic distortion by the tangent function.

Reversed Brickwall
   Classic clip distortion that negatively flips down all values above
   the clip threshold.

Floor
   Classic clip distortion, which maps all values above the clip
   threshold offset from the zero line.

Anti-Saturation
   Boosts already loud samples and reduces quiet samples.

Rectify
   Sets all samples to positive values

Aliasing
   Classic reduction of the sample rate

Modulo
   Uses the mathematical calculation operation "Modulo" to modify the
   wave

*********
 Top Bar
*********

.. include:: section/top_bar.rstinc

******
 VLCD
******

This page shows the current status of the compression. On the left is a
histogram showing the compression of past peaks for comparison with the
current value. In the middle is the gain reduction meter and the
expander switch. On the right side is an input/output diagram showing
the threshold and ratio. The soft knee function can also be read here.

.. include:: section/vlcd.rstinc

*********
 Main UI
*********

Drive
   Determine how much influence the distortion has on the original
   signal.

Trim
   Adjust the volume of the distorted signal.

Select
   Here is the selection of the different distortion algorithms.

Pre/Post
   The plug-in comes with two filters that are placed at different
   points in the signal chain: The Pre Filter before the distortion
   (Input Signal) - the Post Filter after the distortion (Output
   Signal). With these buttons you can switch between the filters. The
   following parameters (Cutoff/Filter Curves and Q) adjust to this
   selection.

Cutoff
   Adjust the crossover frequency at which the filter starts filtering.

Filterkurven
   Choose from three different filter curves. High pass, low pass and
   bell band.

Q
   Adjust the quality of the filter.

Follow
   This is an envelope follower that can modulate the pre-filter based
   on the envelope of the input signal. "Follow" controls the intensity
   with the envelope mapping in the filter movement.

Attack
   Controls how fast the pre-filter reacts to an input signal.

Release
   Controls how long the pre-filter takes to return to its original
   position after modulation by the envelope follower.

Transient Attack
   Here the volume of the transients can be raised or lowered.

Transient Sustain
   Here you can raise or lower the volume of the signal behind the
   transients.

Dry/Wet
   Dry/Wet determines the ratio of processed and unprocessed signal at
   the output.

**********************
 Additional Resources
**********************

.. include:: section/additional_resources.rstinc
