# PhD Thesis

My PhD Thesis in LaTeX!

- Title: The subglacial landscape and hydrology of Antarctica mapped from space
- Author: [Wei Ji Leong](https://orcid.org/0000-0003-2354-1988)
- Supervisor: [Huw Horgan](https://orcid.org/0000-0002-4836-0078)

[![Title coverpage for PhD thesis, with an image showing the subglacial topography of Antarctica](https://user-images.githubusercontent.com/23487320/125365824-12e71d80-e3c9-11eb-8124-2998103a2c68.png)](https://doi.org/10.26686/wgtn.14956062.v1)

Thesis PDF document is available at https://doi.org/10.26686/wgtn.14956062.v1.
Figure files are also available at https://github.com/weiji14/phdthesis/releases.

## Abstract

To narrow uncertainties in the Antarctic ice sheet's contribution to sea level rise, we present a collection of novel machine learning and automated satellite remote sensing methods which use ice surface observations to infer the subglacial nature of Antarctica.
A super-resolution deep neural network called DeepBedMap was designed and trained to produce a high-resolution (250 m) bed elevation model of Antarctica called DeepBedMap_DEM that preserves bed roughness details useful for catchment- to continent-scale ice sheet modelling.
This DeepBedMap_DEM is compared with a smoother, medium-resolution (500 m) BedMachine topography in a basal inversion experiment over Pine Island Glacier, with results motivating more research into the interacting roles of subglacial hydrology which influences skin drag and high resolution bed topographies which influences form drag.
Active subglacial lakes in Antarctica were mapped using an unsupervised density-based classification method on ICESat-2 point cloud data from 2018-2020, yielding 194 active subglacial lakes, including 36 new lakes in the 86-88°S area not detected by the previous ICESat (2003-2009) mission.
This thesis showcases both the rich diversity in subglacial landscapes and the dynamic nature of subglacial hydrology in Antarctica, forming a foundation enabling the accurate modelling of overland ice flow in critical regions of the vulnerable West Antarctic Ice Sheet.

## Plain language summary

Antarctica has a lot of ice, but we're unsure how fast ice can slide into the sea and cause water to go up in beaches around the world.
So we teach computers to solve hard math problems that tell us how fast sea water might go up.
These computers are fed with lots of pictures taken from cameras up in the sky and space.
Ice sits on top of rock in Antarctica, and with practice, the computers get pretty good at telling us how high and bumpy the rock is.
The rock under the ice appears quite bumpy, and ice probably doesn't like sliding over bumpy rocks since it's rough.
Sometimes though, ice may not mind sliding over rough bits of rock if the rock moves along with it, or if water gets in between the rock and ice to makes things slippery, but we ask our smart computers to be sure.
There are also lasers from space shooting down at earth and bouncing back to tell us how ice in Antarctica is going up or down.
Once in a while, they tell us that ice in parts of Antarctica moved up or down a bit too fast.
Smart people think these are lakes hiding under the ice, filling up with water or draining, and we found many of these lakes over Antarctica, especially in an area called Whillans Ice Stream on the Siple Coast.
We hope that the computers can keep learning faster because there's a lot of pictures showing ice moving pretty fast, and it doesn't look like there's much time before a big chunk of ice might break away in Antarctica and flood beaches around the world.

## Code availability

Python code for reproducing the methods in this thesis are publicly available at
https://github.com/weiji14/deepbedmap for Chapter 2 (DeepBedMap),
https://github.com/weiji14/pyissm for Chapter 3 (Basal inversion), and
https://github.com/weiji14/deepicedrain for Chapter 4 (ICESat-2 subglacial lakes).

## Public Talk

- Time: 6 May 2021, 10:00-11:00 NZST
- Location: CO304, Kelburn Campus, Victoria University of Wellington, New Zealand

[![PhD Public Defense presentation slide](https://user-images.githubusercontent.com/23487320/117368403-98f16e80-af17-11eb-82d7-f88d1532b653.png)](https://github.com/weiji14/phdthesis/releases/download/v0.5.0/phd_public_talk.odp)

## Citing

Please use the below citation formats (APA 7th edition) or BibTeX to cite this PhD thesis in your work!

Leong, W. J. (2021). The subglacial landscape and hydrology of Antarctica mapped from space [PhD thesis, Victoria University of Wellington | Te Herenga Waka]. https://doi.org/10.26686/wgtn.14956062.v1

```

@thesis{Leongsubglaciallandscapehydrology2021,
  title = {The Subglacial Landscape and Hydrology of {{Antarctica}} Mapped from Space},
  author = {Leong, Wei Ji},
  date = {2021-07-12},
  institution = {{Victoria University of Wellington | Te Herenga Waka}},
  location = {{Wellington, New Zealand}},
  doi = {10.26686/wgtn.14956062.v1},
  url = {https://openaccess.wgtn.ac.nz/articles/thesis/The_subglacial_landscape_and_hydrology_of_Antarctica_mapped_from_space/14956062/1},
  urldate = {2021-07-12},
  langid = {english},
  pagetotal = {134}
}
```
