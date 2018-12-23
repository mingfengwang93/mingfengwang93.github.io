---
layout:     post
title:      Current works and Research Plan
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

### A new algorithm for melt pond fraction estimation using high resolution optical sensor

Melt pond occupies a large fraction on the Arctic sea ice surface during spring and summer. The fraction and distribution of melt pond make a vital impact on the climate and ecosystem by changing the sea ice mass and energy balance, oceanic mixing layer depth, salt balance, and ocean productivity. The climate influences of melt pond reveal the urgency of obtaining a longtime series MPF (melt pond fraction) data. 
MPF data acquisition mainly based on optical remote sensing. In-situ observation indicates that the spectral properties of melt ponds are widely varied even at a local scale. 
In the previous MPF algorithm, melt ponds are treated as only one kind of surface features, and the reflectivity of melt ponds is assumed to be constants. In this paper, we perform these previous algorithms using Sentinel-2 and Landsat8 data, the determination results indicate that the assumption of fixed melt pond reflectivity leads to a severe underestimate of MPF. 
![cv](https://mingfengwang93.github.io/assets/traning-area.bmp)
To correct this problem, we treat melt pond as a reflectivity variable feature by dividing them into bright blue melt ponds and dark blue melt ponds, then proposed a new algorithm based on LinearPolar transformation.

FIG.2 2D HISTOGRAM

The angular coordinate θ of the polar coordinate system is used to determinate MPF, as θ is only associate with MPF and do not relate to the reflectivity of different melt ponds. The MPF determination results of LinearPolar algorithm is compared with that of previous algorithms and exhibited to be more reasonable. 

FIG.3 POSITION

FIG.4 S2 SAMPLES

FIG.5 L8 SAMPLES

### Determination of Arctic melt pond fraction and sea ice roughness from Unmanned Aerial Vehicle (UAV) imagery 

During the 7th Chinese National Arctic Research Expedition, aerial photographs were taken from an Unmanned Aerial Vehicle over an ice floe in the Canada Basin. Using threshold discrimination and three-dimensional modeling, we estimated a melt pond fraction of 1.63% and a regionally averaged surface roughness of 0.12 for the study area.

FIG.1 POSITION

In view of the particularly foggy environment of the Arctic, aerial images were defogged using an improved dark channel prior based image defog algorithm, specially adapted for the special conditions of sea ice images.

FIG.2  DEFOG

An aerial photo mosaic was generated, melt ponds were identified from the mosaic image and melt pond fractions were calculated. Three-dimensional modeling techniques were used to generate a digital elevation model allowing relative elevation and roughness of the sea ice surface to be estimated. 

FIG.3 DEM

Analysis of the relationship between the distributions of melt ponds and sea ice surface roughness shows that melt ponds are smaller on sea ice with higher surface roughness, while broader or deeper melt ponds usually occur in areas where sea ice surface roughness is lower.


FIG.4 SCATTER

