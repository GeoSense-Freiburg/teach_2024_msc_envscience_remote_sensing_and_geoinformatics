# teach_2024_msc_envscience_remote_sensing_and_geoinformatics
Teaching material for the MSc Module "Remote Sensing and Geoinformatics"

## News
### Wednesday
 * Maximilian Fabi will show you the orthoimage processing. He will pick you up at CIP3 at 09:15 (usual place and time).
### Thursday
* you should read https://www.sciencedirect.com/science/article/pii/S2667393223000054
  * (no need to understand every piece and term but you should have a rough overview)
* checkout the current state of the database we are currenlty setting up at https://www.deadtrees.earth
* Delindate orthoimagery; the idea was 2-5 Orthoimages per person ... depending on how much you want to support us :-)
### Friday
* Get a glimpse on why deep learning-based pattern recognition is so powerful in the remote sensing domain. You may checkout our publication in that context, e.g,:
  * https://www.sciencedirect.com/science/article/pii/S0924271620303488
  * https://www.sciencedirect.com/science/article/pii/S0924271620302938
  * (no need to understand every piece and term but you should have a rough overview)
* Compare your delineated orthoimages to our artifical intelligence (pattern recognition using Convolutional Neural Networks)
 * This might only work in Colab, as it requires GPU resources. Find the script [here](https://github.com/GeoSense-Freiburg/teach_2024_msc_envscience_remote_sensing_and_geoinformatics/tree/main/03_drone_data_and_segmentation)
* Brainstorm on what you would like to do as a individual group project next week (2 persons per group).

## Small list of advices or this course:
* dare to ask many questions
* dare to give feedback
  * in the course, to teja.kattenborn@geosense.uni-freiburg or also here in Github unter "Issues" or "Disscussions)
  * For instance, feedback on improvements for the course, errors in the code, analysis of interest, etc.
* Be patient with yourself (expect both flat and steep learning curves)
* Help eachother :-)

## Access to the data
* All data can be found [here](https://drive.google.com/drive/folders/1hiPaQaDegKOba22Mg7ZBoOSkcNBgTMnR?usp=drive_link).
* In total the data amounts to 18 GB. Let me know if you do not have sufficient storage ressources for the duration of the course.

## Where to perform the analysis?
* Your own computer
* CIP-Pool computers
* Google Colab: https://colab.research.google.com/
 * Colab-JuPyteR shortcuts: https://colab.research.google.com/drive/13IO3-gfyS9mSPuzAo6-wsYBUOVpxb_va?usp=sharing


## install packages
* pip install rioxarray (in colab)
* alternatives conda or mamba (conda install <packagename> -c conda-forge)
* list of packages that should be installed for the course: rioxarray rioxarray matplotlib numpy xarray glob2 pandas geopandas rasterstats rasterio
