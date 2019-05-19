---
layout:     post
title:      Academic works
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
![cv](https://mingfengwang93.github.io/assets/icebridgeflight3.png)
                   Fig.1. Overview of the study area with the locations of the selected Sentinel-2 
                   scenes (red frames). The 40 selected samples within the scenes 1-5, Scene 5 is 
                   used for validation with IceBrige aerial image.  The acquired times of Scene 1-5 
                   are 29 July 2016, 4 July 2017, 29 June 2017 and 12 June 2017, 24 July 2017 respectively. 

MPF information has generally been acquired from optical imagery. Conventional MPF algorithms based on high-resolution optical sensors have treated melt ponds as a feature with constant reflectance. However, **the spectral reflectance of ponds can vary by up to 70% in the visible range, even at a local scale**.
![cv](https://mingfengwang93.github.io/assets/case00s2_after_pct (2).png)
                   Fig.2. Transformed new coordinate system with axes θ and r. The scatter distributions
                   of selected areas are illustrated with different marks.
Here we use Sentinel-2 imagery to demonstrate that **previous algorithms assuming fixed melt pond-reflectance largely underestimate MPF**. To address this problem, we propose a new algorithm based on the polar coordinate transformation that treats melt ponds as variable-reflectance features and calculates MPF across the vector bisecting melt pond and bare ice axes. The angular coordinate θ of the polar coordinate system, which is only associated with pond fraction rather than reflectance, is used to determinate MPF.
![cv](https://mingfengwang93.github.io/assets/compare.bmp)
                  Fig.3. Melt pond fraction determined by the three algorithms 
                  along the IceBridge aerial observation flight track (Red, Blue 
                  and Green line). Melt pond fraction discrimination result of the 
                  IceBridge aerial image (Black line).
![cv](https://mingfengwang93.github.io/assets/case1.png)
![cv](https://mingfengwang93.github.io/assets/case2.png)
![cv](https://mingfengwang93.github.io/assets/case3.png)
                  Fig.4. (1)-(3) are 3 selected samples among the 36 IceBridge aerial images. a) 
                  True colour images of Sentinel-2, b) IceBridge aerial image, c) classification 
                  results of IceBridge aerial images, d) MPF determination result of Markus algorithm 
                  (%), e) MPF determination result of PCA algorithm (%), and f) MPF determination result 
                  of LinearPolar algorithm (%), g) MPF determination result of IceBridge aerial images


By comparing the new algorithm and previous methods with Operation IceBridge (OIB) aerial observation data, across a variety of Sentinel-2 images with melt ponds at various stages of development, we show that **the accuracy of MPF retrievals can be improved by up to 40%**. 











### Determination of Arctic melt pond fraction and sea ice roughness from Unmanned Aerial Vehicle (UAV) imagery 

During the 7th Chinese National Arctic Research Expedition, **aerial photographs were taken from an Unmanned Aerial Vehicle** over an ice floe in the Canada Basin. Using threshold discrimination and three-dimensional modeling, we estimated a melt pond fraction of 1.63% and a regionally averaged surface roughness of 0.12 for the study area.

![cv](https://mingfengwang93.github.io/assets/position.bmp)

In view of the particularly foggy environment of the Arctic, **aerial images were defogged** using an improved dark channel prior based image defog algorithm, specially adapted for the special conditions of sea ice images.

![cv](https://mingfengwang93.github.io/assets/defog.bmp)

An aerial photo mosaic was generated, **melt ponds were identified** from the mosaic image and melt pond fractions were calculated. **Three-dimensional modeling techniques were used to generate a digital elevation model allowing relative elevation and roughness of the sea ice surface to be estimated**. 

![cv](https://mingfengwang93.github.io/assets/dem.bmp)

Analysis of the relationship between the distributions of melt ponds and sea ice surface roughness indicates that melt ponds are smaller on sea ice with higher surface roughness, while broader or deeper melt ponds usually occur in areas where sea ice surface roughness is lower.

![cv](https://mingfengwang93.github.io/assets/scatter.bmp)








### Enhanced correlation between MPF and albedo of Arctic sea ice under the background of multi-year ice decline

The correlation between MPF and sea ice albedo gradually increase with the development of melt pond, reaching a multi-year average value above 0.6 in June, at this point, melt pond is the main affecting factor of sea ice albedo. The correlation begins to decrease in July, by this time more leads emerged and begin to influence the albedo.

![cv](https://mingfengwang93.github.io/assets/mpf-seasonal.bmp)

Under the background of multi-year ice decline, the correlation between MPF and albedo of the Arctic sea ice is increasing, at least in July and August. Because more regions will be dominated by homogeneous Seasonal sea ice , and seasonal ice is more conducive to melt pond developing.

![cv](https://mingfengwang93.github.io/assets/interannual-albedo.bmp)

![cv](https://mingfengwang93.github.io/assets/multi-year-ice.bmp)


