---
layout:     post
title:      Academic works and Research Plan
subtitle:   
date:       2018-12-16
author:     mf
header-img: img/about-bg.jpg
catalog: 	 true
tags:
    -
    -
---


## Academic works


### Determination of Arctic melt pond fraction and sea ice roughness from Unmanned Aerial Vehicle (UAV) imagery 

During the 7th Chinese National Arctic Research Expedition, **aerial photographs were taken from an Unmanned Aerial Vehicle** over an ice floe in the Canada Basin. Using threshold discrimination and three-dimensional modeling, we estimated a melt pond fraction of 1.63% and a regionally averaged surface roughness of 0.12 for the study area.

![cv](https://mingfengwang93.github.io/assets/position.bmp)

In view of the particularly foggy environment of the Arctic, **aerial images were defogged** using an improved dark channel prior based image defog algorithm, specially adapted for the special conditions of sea ice images.

![cv](https://mingfengwang93.github.io/assets/defog.bmp)

An aerial photo mosaic was generated, **melt ponds were identified** from the mosaic image and melt pond fractions were calculated. **Three-dimensional modeling techniques were used to generate a digital elevation model allowing relative elevation and roughness of the sea ice surface to be estimated**. 

![cv](https://mingfengwang93.github.io/assets/dem.bmp)

Analysis of the relationship between the distributions of melt ponds and sea ice surface roughness indicates that melt ponds are smaller on sea ice with higher surface roughness, while broader or deeper melt ponds usually occur in areas where sea ice surface roughness is lower.

![cv](https://mingfengwang93.github.io/assets/scatter.bmp)



### A new algorithm for melt pond fraction estimation using high resolution optical sensor

Melt pond occupies a large fraction on the Arctic sea ice surface during spring and summer. The fraction and distribution of melt pond make a vital impact on the climate and ecosystem by changing the sea ice mass and energy balance, oceanic mixing layer depth, salt balance, and ocean productivity. The climate influences of melt pond reveal the urgency of obtaining a longtime series MPF (melt pond fraction) data. 

MPF data acquisition mainly based on optical remote sensing. In-situ observation indicates that **the spectral properties of melt ponds are widely varied even at a local scale**. 

In the previous MPF algorithm, melt ponds are treated as only one kind of surface features, and the reflectivity of melt ponds is assumed to be constants. In this paper, we perform these previous algorithms using Sentinel-2 and Landsat8 data, the determination results indicate that **the assumption of fixed melt pond reflectivity leads to a severe underestimate of MPF**. 

![cv](https://mingfengwang93.github.io/assets/traning-area.bmp)

To correct this problem, we treat melt pond as a reflectivity variable feature by dividing them into bright blue melt ponds and dark blue melt ponds, then **proposed a new algorithm based on LinearPolar transformation**.

![cv](https://mingfengwang93.github.io/assets/two-d-histogram.bmp)

The angular coordinate θ of the polar coordinate system is used to determinate MPF, as θ is only associate with MPF and do not relate to the reflectivity of different melt ponds. The MPF determination results of **LinearPolar algorithm** is compared with that of previous algorithms and exhibited to be more reasonable. 

![cv](https://mingfengwang93.github.io/assets/position.bmp)

![cv](https://mingfengwang93.github.io/assets/s2.bmp)

![cv](https://mingfengwang93.github.io/assets/l8.bmp)




### Enhanced correlation between MPF and albedo of Arctic sea ice under the background of multi-year ice decline

The correlation between MPF and sea ice albedo gradually increase with the development of melt pond, reaching a multi-year average value above 0.6 in June, at this point, melt pond is the main affecting factor of sea ice albedo. The correlation begins to decrease in July, by this time more leads emerged and begin to influence the albedo.

![cv](https://mingfengwang93.github.io/assets/mpf-seasonal.bmp)

Under the background of multi-year ice decline, the correlation between MPF and albedo of the Arctic sea ice is increasing, at least in July and August. Because more regions will be dominated by homogeneous Seasonal sea ice , and seasonal ice is more conducive to melt pond developing.

![cv](https://mingfengwang93.github.io/assets/interannual-albedo.bmp)

![cv](https://mingfengwang93.github.io/assets/multi-year-ice.bmp)


