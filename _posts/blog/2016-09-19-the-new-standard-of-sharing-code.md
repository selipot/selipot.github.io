---
layout: post
title: "On the new standard of sharing your code"
modified:
categories: blog
excerpt:
tags: code, data, sharing, GitHub
image:
  feature:
date: 2016-09-19
comments: true
---

Scientists in general, and oceanographers in particular, have been used for many years to sharing "their" data. A few whine about how difficult it is to obtain funding and acquire the data, and as such should keep their exclusivity. They can for a few years, but in the end it is not really their data anyway, since they most likely originate from projects funded by tax payers, through governmental funding agencies.

Something new is happening though. Recently, as part of the last checks before one of our newest manuscript got accepted, we were asked by the journal editor to disclose the "availability of our code". Obviously, stating that our messy, uncommented, code written for the commercial software MATLAB was not available, was not acceptable. I was first annoyed at the daunting task of putting together a sharable code but mostly I was surprised. I was surprised because our methods involved relatively standard statistical techniques and tools, and a few relatively unusual ones that were otherwise clearly referenced in our "methods" section. What I mean is that the references given in our article clearly spelled out the formulae used. As an example, I have become really fond of *kernel estimators* and the Nadaraya-Watson estimator with a Gaussian or an Epachnikov kernel has become my go-to for non-parametric curve estimation. The book *Local Polynomial Modelling and Its Applications* by Fan and Gijbels is a very nice introduction to these methods. So, in the end, not only do we have to say with words, or equations, what we did, but we also have to type it up for others. Isn't that too much?

I am being sarcastic and it looks like this is the way forward anyway, so the old guard better adapt, and students better get acquainted right away with these methods. The goal is to improve reproducibility of results (especially in wet labs), and as such some journals have started to hire editors for that [purpose](http://www.nature.com/news/why-scientists-must-share-their-research-code-1.20504). Thank you to my colleague [Ryan Abernathey](http://ryan.actualscience.net) for tweeting this article. In addition, it apperas that
one of the  points of this movement is to improve the quality of scientific code. That means clear structure, organization, testing, comments, and documentation.
Scripps graduate student Cesar rocha's recent project is apparently a very good [example](https://github.com/crocha700/UpperOceanSeasonality). Another example is veteran oceanographer [Jody Klymak](http://web.uvic.ca/~jklymak) is making available a lot of his analysis code through his [GitHub page](https://github.com/jklymak?tab=repositories). Finally, my collaborator [Jonathan Lilly](http://www.jmlilly.net) at NorthWest Research Associates has been working very hard for many years to put together his superb Matlab Toolbox called Jlab. It is distributed through [Matworks File Exchange](http://www.mathworks.com/matlabcentral/fileexchange/52885-jlab--a-matlab-toolbox-for-data-analysis?requestedDomain=www.mathworks.com) but it is also on [GitHub](https://github.com/jonathanlilly/jLab) for suggesting edits and modifications. GitHub watch out, here I come. (This site is hosted by [GitHub Pages](https://pages.github.com)).  
