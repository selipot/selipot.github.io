---
layout: post
title: "Colors of the <strike>Wind</strike> Ocean"
modified:
categories: blog
excerpt:
tags: colormap, oceanography, matlab
image:
  feature:
date: 2016-10-09  
---
*You can own the earth and still*

*All you'll own is earth until*

*You can paint with all the Colors of the <strike>Wind</strike>*
*Ocean*

Thank you to [Kim Martini](https://twitter.com/rejectedbanana) for pointing out on twitter a new article published in [Oceanography magazine](http://dx.doi.org/10.5670/oceanog.2016.66)! In that article, Thyng et al. present a set of freely available colormaps called [cmocean](https://github.com/matplotlib/cmocean) to be used for oceanographic applications. This newish set strives to provide a selection of color palettes chosen to accurately serve the representation of data, with color hues we oceanographers traditionally associate with oceanic variables (such as deep blue to white for sea ice). The set is built in order for our eyes to not misinterpret the data being presented (the analog filter of our eyes perceive colors and color gradients unevenly). In particular, the method used by Thyng et al. consists in making sure the perceptual (visual) changes in a given colormap match the changes in the underlying data, using a property of color called "lightness", and relies mostly on the [**viscm** tool](https://github.com/matplotlib/viscm). Appropriately, The authors point out the pitfalls of the *jet* colormap (which I have always personally found evil), and I think they are right on point when assigning the apparent popularity of that colormap to having been the default [MATLAB colormap](http://www.mathworks.com/help/matlab/ref/colormap.html) for many years (but recently switched to the demure parula colormap by the way).

The business of colors can be incredibly complicated, but also very useful. I am very keen on using the *phase* information of data, which is a challenging thing to represent when an associated magnitude is also present. In several of my papers I have relied on the Hue-Saturation-Value (HSV) properties of colors rather than the more traditional Red-Green-Blue (RGB) representation (see as an example my 2016 paper [*Characteristics, Energetics, and Origins of Agulhas Current Meanders and their Limited Influence on Ring Shedding*](http://dx.doi.org/10.1175/JPO-D-14-0254.1)). Another example on the use of colors in oceanography is the paper by Hughes and Williams in 2010 called [*The color of sea level*](http://dx.doi.org/10.1029/2010JC006102) who smartly used colors to represent 3D information of sea level spectra on the globe.

So, check out this new paper and the refrences therein if you are interested in colors!: *True Colors of Oceanography Guidelines for Effective and Accurate Colormap Selection* (2016) By Kristen M. Thyng, Chad A. Greene, Robert D. Hetland, Heather M. Zimmerle, and Steven F. DiMarco, [doi:10.5670/oceanog.2016.66](http://dx.doi.org/10.5670/oceanog.2016.66)

(*Pocahontas* is my second favorite Disney movie, yes, after *The Little Mermaid*) ...
