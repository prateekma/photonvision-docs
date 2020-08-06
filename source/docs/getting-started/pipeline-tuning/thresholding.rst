Thresholding
============
Thresholding is one of the most important aspects of the vision tuning pipeline. With the thresholding step, you are filtering out pixels in the frame that are not in a specific color range.

Hue
---
Since most FRC targets are illumated by green retroreflective tape, it is a good starting point to set the Hue slider with the lowest point at 60 and highest point at 100. From here, you can slowly narrow the range until only the desired target is visible in the threshold view of the UI.

.. image:: images/hue.gif