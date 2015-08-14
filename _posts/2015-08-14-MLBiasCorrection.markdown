---
layout: post
title:  "Estimation and Bias Correction of Aerosol Abundance using Data-Driven Machine Learning and Remote Sensing"
date:   2015-08-14 15:30:39
categories: Research Physics
tags: Research Physics Computer Science Data Big Machine Learning Satellite Health Particulate Pollution
---
Air quality information is increasingly becoming a public health concern, since some of the aerosol particles pose harmful effects to peoples health. One widely available metric of aerosol abundance is the aerosol optical depth (AOD). The AOD is the integrated light extinction coefficient over a vertical atmospheric column of unit cross section, which represents the extent to which the aerosols in that vertical profile prevent the transmission of light by absorption or scattering. The comparison between the AOD measured from the ground-based Aerosol Robotic Network (AERONET) system and the satellite MODIS instruments at 550 nm shows that there is a bias between the two data products. We performed a comprehensive search exploring possible factors which may be contributing to the inter-instrumental bias between MODIS-Aqua land data set and AERONET. The analysis used several measured variables, including the MODIS AOD, as input in order to train a neural network in regression mode to predict the AERONET AOD values. This not only allowed us to obtain an estimate, but also allowed us to infer the optimal sets of variables that played an important role in the prediction. In addition, we applied machine learning to infer the global abundance of ground level PM2.5 from the AOD data and other ancillary satellite and meteorology products. This research is part of our goal to provide air quality information, which can also be useful for global epidemiology studies.

[Check out the paper][MLBiasCorrection-paper] for more info!

[MLBiasCorrection-paper]: http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=6382197&tag=1
