---
layout: page
title: Astrocolonialism 
subtitle: UTS 101 Final Project
bigimg:
 - "tmt_protest2.jpg" : "Maunakea Protests Against TMT NEED DATE AND COPYRIGHT"
---

# Astrocolonialim

*This code in this notebook heavily draws inspiration from the work shown in this*
[*blog post*](http://jakevdp.github.io/blog/2013/12/05/static-interactive-widgets/)
*by Jake Vanderplas on*
[*Pythonic Perambulations*](http://jakevdp.github.io/).
*Content is BSD licensed.*

#### *If you plan to use this webpage and notebook for your own research or educational purposes, please cite this (provide link)*

This notebook makes use of [ipywidgets](https://github.com/ipython/ipywidgets) developed by the Jupyter Project and [Matplotlib's plottling library](https://matplotlib.org/).

## Here in this notebook I provide context and a working definition for astrocolonialism. I also supply supplemental reading, viewing, and other resources. Finally, I provide a slide deck to be used for educational purposes and an interactive widget to contextualize the enormous size of modern astronomical observatories.

## *This is by no means an exhaustive set of materials. It is merely a consolidation of resources and ideas to which I own no intellectual property or credit. This is a working, living project as well.*

use these werid latex left quotes to make softwarey text ``like this``

## What's going on here? Astronomy is awesome!

Astronomy has advanced humanity's knowledge of the Universe in immeasurable. Simultaneously, it have motivated superb technological advances demanded by its insatiable appetite to uncover the secrets of the Cosmos. Ancillary to these technological demands are searches for the optimal astornomical observing locations. In the tradition of Western Astronomy, this unfolds as reaping of remote mountain tops. But where are these remote, pristine mountain tops that are accessible by vehicle? In the Americas and Hawai‘i, these are lands that have been stolen from Indigenous American Indians and Hawai‘ians. Furthermore, most, if not all, are sacred lands. The best example of this [Mauna Kea](https://en.wikipedia.org/wiki/Mauna_Kea), home to 12 astronomical observatories with one presently planned: The Thirty Meter Telescope. Such a telescope is apart of new emergence of extremely large modern observatories, tripling the primary mirror's size of 10 meter class observatories to 30 meters. ***Content warning: r*pe*** The construction of yet another observatory, regardless of size, has been likened to ["raping"](https://enewspaper.latimes.com/infinity/article_share.aspx?guid=3dbb9d14-cfd3-4e55-99cf-ed717c203a19) the otherwise pure, sacred Mauna.

For further reading on the Hawaiian's struggle against TMT visit the above link and these resources:
* [Astrobites piece - *Maunakea, Western Astronomy, and Hawai'i*](https://astrobites.org/2019/08/02/maunakea-western-astronomy-and-hawaii/)
* A short film by Puuhonua Puuhuluhulu documenting the July protests and stuggles against the TMT's construction: [Like a Mighty Wave: A Maunakea Film](https://www.youtube.com/watch?v=4J3ZCzHMMPQ&feature=emb_logo)

More general resources on Astrocolonialism:
* future text
* astrcolonialism in SW America
* astrocolonialism in chile
* other stuff

First we set up a function which takes some arguments and plots something:

{% include interactive_test.html %}

That's all there is to it!

### Matplotlib

And of course, you can use this to display matplotlib plots.  Keep in mind, though, that every image must be pre-generated and stored in the notebook, so if you have a large number of settings (or combinations of multiple settings), the notebook size will blow up very quickly!

For this example, I want to quickly revisit the [post](http://www.mglerner.com/blog/?p=28) which inspired me, and compare the kernel density estimation of a distribution with a couple kernels and bandwidths.  We'll make the figure smaller so as to not blow-up the size of this notebook:

## Summary

I'm pretty excited about these tools.  I think they'll allow for some really interesting demos and visualizations, especially if more time can be spent polishing them.  The package is still very rough: it offers little flexibility in how the widgets are displayed, it only implements radio buttons and a slider, and it still hiccups at times when the slider items are floating-point values (this is due to differences in Javascript's and Python's default representations of floating point numbers).  Regardless, I hope you have fun playing with this, and I hope to see some posts using this on other blogs in the near future!

Happy Hacking!

*This post was written entirely in the IPython notebook.  You can
[download](http://jakevdp.github.com/downloads/notebooks/IPythonWidgets.ipynb)
this notebook, or see a static view
[here](http://nbviewer.ipython.org/url/jakevdp.github.com/downloads/notebooks/IPythonWidgets.ipynb).*

