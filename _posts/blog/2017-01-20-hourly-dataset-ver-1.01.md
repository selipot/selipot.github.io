---
layout: post
title: "Hourly drifter product version 1.01 released"
modified:
categories: blog
excerpt:
tags: drifters
image:
  feature:
date: 2017-01-20  
---

We are pleased to announce the release of version 1.01 of the hourly drifter product. Now available to download from the Global drifter program [DAC website](http://www.aoml.noaa.gov/phod/dac/hourly_data.php). The methods of interpolation implemented to generate this product are the same as for version 1.00 of the dataset released in mid-2016, see [Elipot et al. 2016, doi:10.1002/2016JC011716](http://dx.doi.org/10.1002/2016JC011716). See the [release notes](http://www.aoml.noaa.gov/phod/dac/hourly_data.php).

This 1.01 update adds newer data to the previous version, one year of quality-controlled data up to 30 June 2016 for Argos-tracked drifters, and more than one year of GPS-tracked data, up to 1 October 2016. In addition, we have added data before 1 September 2005 (the start date of version 1.00) by considering all GPS-tracked drifters since the beginning of the GDP, and all Argos-tracked drifter data since the beginning of the GDP, when the average of the uneven sampling intervals per trajectory is less than or equal to 3 hours.

![Alt text](/images/data_distribution_1.01.jpg "Distribution of hourly drifter position and velocity estimates from Argos-tracked and GPS-tracked trajectories, version 1.01")

The 1.01 dataset now totals over 117.4 million estimates of position and velocity with confidence intervals from 12,287 Argos-tracked drifter trajectories, and over 5.6 million estimates of position and velocity with confidence intervals from 985 GPS-tracked drifter trajectories.

Simplified versions of the Matlab codes used to generate this dataset are available through a [GitHub repository](https://github.com/selipot/hourly-drifters/).
