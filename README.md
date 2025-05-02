# permafrost-cpcrw-chena

This repository contains:

1) The data needed to reproduce the figures in the Alter et al. manuscript "Using an observation-based map of permafrost extent to inform permafrost predictions in a large Alaskan watershed", which has been submitted to JGR Earth Surface, and
2) The machine learning model developed in this study that is used to predict permafrost extent in the Chena River watershed.

## Authors
Ross E. Alter<sup>1*</sup>, Nawa Raj Pradhan<sup>2</sup>, and Anna M. Wagner<sup>3</sup>

<sup>1</sup>U.S. Army Engineer Research and Development Center (ERDC), Cold Regions Research and Engineering Laboratory (CRREL), Hanover, NH, USA.

<sup>2</sup>U.S. Army Engineer Research and Development Center, Coastal and Hydraulics Laboratory, Vicksburg, MS, USA.

<sup>3</sup>U.S. Army Engineer Research and Development Center, Cold Regions Research and Engineering Laboratory, Ft. Wainwright, AK, USA.

## Created
March 2025

## Data
This repository contains one directory of data files associated with the figures in the Alter et al. manuscript as well as a .pkl file that contains the machine learning model developed in this study:

* "Figure_data"

  * This directory contains the data that are used to produce each figure in the Alter et al. manuscript.

  * *Notes*:

    * For the land cover files in "Figure_2" and "Figure_6", please use the following legend to translate the numerical data:
   
      * 11 = Open Water
      * 12 = Perennial Ice/Snow
      * 21 = Developed, Open Space
      * 22 = Developed, Low Intensity
      * 23 = Developed, Medium Intensity
      * 24 = Developed, High Intensity
      * 31 = Barren Land (Rock/Sand/Clay)
      * 41 = Deciduous Forest
      * 42 = Evergreen Forest
      * 43 = Mixed Forest
      * 51 = Dwarf Scrub
      * 52 = Shrub/Scrub
      * 71 = Grassland/Herbaceous
      * 72 = Sedge/Herbaceous
      * 81 = Pasture/Hay
      * 82 = Cultivated Crops
      * 90 = Woody Wetlands
      * 95 = Emergent Herbaceous Wetlands 

    * For the files in "Figure_4", please use the following legend to translate the numerical data:

      * 0 = n/a
      * 1 = false negative
      * 2 = false positive
      * 3 = true negative
      * 4 = true positive

    * For the file in "Figure_8", please use the following legend to translate the numerical data:

      * 0 = no permafrost
      * 0.5 = inconclusive (masked)
      * 1 = yes permafrost
        
* cpcrw_permafrost_model.pkl

  * This file contains the machine learning model developed in this study that is used to predict permafrost extent in the Chena River watershed.
