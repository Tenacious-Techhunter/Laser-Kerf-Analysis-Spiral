Laser-Kerf-Analysis-Spiral

Image File: Kerf Analysis Spiral Image.tif - This is a currently untested release.

  An image of a Logarithmic Spiral tuned for analyzing the Kerf and Taper Tolerance of Laser Cutters.

  Comes with Grid and Angle Tick-Marks to precisely measure Kerf and Taper as a difference of Logarithmic Curve Radii, which is a function of the measured angle, a more easily observed value. Engrave the Grid and Angle Tick-Marks before the Vector-Cut, which should be cut from inward to outward. A pause and alert tone should ideally take place between the Engraving and Vector-Cutting steps, so the operator can be alerted to the time most likely to cause a fire hazard.


Curve Function:
r = 0.1 + (e^((ln(2)θ)/(2π)))/1000, 4π≤θ≤12π

  This function assumes an initial radius of 0.1", on account of an assumption that the previous cycle’s cut should fully cool before the next cycle’s cut passes it, to prevent errors due to thermal expansion, and to prevent firestarting conditions. This won’t be true for all materials; some materials may require testing against a larger initial radius to prevent such errors.
  This function also asumes that the kerf will be larger than the 0.004" diameter “Spot Size” published in reference materials for the Epilog Lazer Zing 16 Model Laser Cutter. Smaller kerf measurements would require starting at θ=2π, or possibly even smaller, rather than 4π; however, this introduces a risk of fire hazard, since, practically speaking, the laser would be passing along “the same path multiple times”.

  The Vector-Cut will produce a gradually increasing spiral thickness; that much is obvious. What is not so obvious is that, when the overlap of kerf radii begins to stop, it will stop gradually, rather than suddenly, due to Tapering, and other cutting effects that produce insufficiently perpendicular edges. In this way, you can measure both a minimum and maximum for the kerf when you have an inward or outward taper, and even observe hourglass and diamond tapering. This will result in considerably more detailed understanding of the settings producing your current kerf, and allow you to adjust your laser cutter for more reliable kerf values and cleaner tolerances.


Public Domain

  This diagnostic tool is released to the public domain. Attribution is encouraged, but optional. Pull-Requests are also encouraged, but, again, optional.
