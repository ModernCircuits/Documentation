############
 Modulation
############

.. contents::
   :local:

.. literalinclude:: snippets/test.cpp
   :language: cpp

*****
 LFO
*****

+-----------+------------------------------------+-------------+
| Control   | Range                              | Description |
+===========+====================================+=============+
| Shape     | Sine, Square, Saw, Triangle, Noise |             |
+-----------+------------------------------------+-------------+
| Width     | 0 - 100%                           |             |
+-----------+------------------------------------+-------------+
| Frequency | 0.01Hz - 20Hz                      |             |
+-----------+------------------------------------+-------------+
| Stop      | 0 - 1000 ms                        |             |
+-----------+------------------------------------+-------------+
| Fade      | 0 - 1000 ms                        |             |
+-----------+------------------------------------+-------------+

.. note::

   Some note...

*****
 SEQ
*****

+----------+--------------+-------------+
| Control  | Range        | Description |
+==========+==============+=============+
| Sync     | Off, On      |             |
+----------+--------------+-------------+
| Rate     | 1 - 1000ms   |             |
+----------+--------------+-------------+
| Multiply | 0.5, 1, 2, 4 |             |
+----------+--------------+-------------+
| Mode     | Normal,      |             |
|          | Reverse      |             |
+----------+--------------+-------------+
| Smooth   | 0 - 100%     |             |
+----------+--------------+-------------+

*****************
 Trigger Section
*****************

Lorem ipsum dolor sit amet, consectetur adipiscing elit. In tincidunt
sem non metus ultricies aliquam. Duis in magna varius, accumsan mi ut,
mollis dui. Maecenas scelerisque vel massa at pulvinar. Aliquam tempus
arcu eu ex pulvinar rutrum. Quisque at varius felis. Phasellus pulvinar
euismod placerat. Praesent id placerat arcu, vitae condimentum ante.

+------------+-------------+-----------------------------------+
| Control    | Range       | Description                       |
+============+=============+===================================+
| Oneshot    |             | Restart modulator once            |
+------------+-------------+-----------------------------------+
| Free       | 0 - 1000 ms | Restart modulator every N seconds |
+------------+-------------+-----------------------------------+
| Timecode   | 1/16 - 16   | Restart modulator every N bars    |
+------------+-------------+-----------------------------------+
| Input      | 0 - 100 %   |                                   |
+------------+-------------+-----------------------------------+
| Side-Chain | 0 - 100 %   |                                   |
+------------+-------------+-----------------------------------+
