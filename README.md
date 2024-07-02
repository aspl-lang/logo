# The ASPL logo
This repository contains the ASPL logo as an SVG as well as a pre-rendered PNG image of it.

![ASPL logo](logo.svg)

## Comments on the math used in the SVG
The ASPL logo is easy to draw if tilted by 45 degrees.

While this makes rendering it in SVG very easy, it also makes it impossible to correctly align a viewport with the logo. The following formulae were used to calculate the viewport size:

$width = 2.75 * (50 * \sqrt{2}) \approx 195$

$height = 2.25 * (50 * \sqrt{2}) \approx 160$

(Note that this is rounded **up**)

As you can see, the formulae contain the irrational number $\sqrt{2}$, which means that for no given viewport size, the logo will align perfectly with the viewport. This may or may not leave a pixel-wide gap between the logo and the viewport, depending on the actual viewport size and thus rounding "errors".