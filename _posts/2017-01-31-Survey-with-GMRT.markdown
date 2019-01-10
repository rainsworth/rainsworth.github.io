---
layout: post
title:  "A GMRT survey of regions towards the Taurus molecular cloud at 323 and 608 MHz"
date:   2017-01-31
excerpt: "Access to the publication, data and code associated with this research is provided."
project: true
tags: [GMRT, Open Science]
feature:
comments: true
---


This survey is the first in a series of surveys of star forming regions, taken at 325 and 610 MHz with the Giant Metrewave Radio Telescope ([GMRT](http://www.gmrt.ncra.tifr.res.in/)). Full details of the observations, data reduction, images and source catalogue can be found in <i>Ainsworth R. E., Coughlan C. P., Green D. A., Scaife A. M. M., Ray T. P., 2016, MNRAS, 462, 2904</i> ([ads](http://adsabs.harvard.edu/abs/2016MNRAS.462.2904A), [arXiv](https://arxiv.org/abs/1607.07245)). The main project homepage is [here](https://homepages.dias.ie/rainsworth/GMRT-TAU_catalogue.html).

## Summary

We present observations of three active sites of star formation in the Taurus Molecular Cloud complex taken at 323 and 608 MHz (90 and 50 cm, respectively) with the Giant Metrewave Radio Telescope (GMRT). Three pointings were observed as part of a pathfinder project, targeted at the young stellar objects (YSOs) L1551 IRS 5, T Tau and DG Tau (the results for these target sources were presented in a previous paper). In this paper, we search for other YSOs and present a survey comprising of all three fields; a by-product of the large instantaneous field of view of the GMRT. The resolution of the survey is of order 10&#8243; and the best rms noise at the centre of each pointing is of order 100 &#956;Jy at 323 MHz and 50 &#956;Jy at 608 MHz. We present a catalogue of 1815 and 687 field sources detected above 5&#963; at 323 and 608 MHz, respectively. A total of 440 sources were detected at both frequencies, corresponding to a total unique source count of 2062 sources. We compare the results with previous surveys and showcase a sample of extended extragalactic objects. Although no further YSOs were detected in addition to the target YSOs based on our source finding criteria, these data can be useful for targeted manual searches, studies of radio galaxies or to assist in the calibration of future observations with the Low Frequency Array (LOFAR) towards these regions.

![](https://github.com/rainsworth/GMRT-TAU_catalogue/raw/master/field_files/Taurus.png)
Overview of the Taurus Molecular Cloud. Greyscale is the high resolution CO extinction map from [Dobashi et al. (2005)](http://adsabs.harvard.edu/abs/2005PASJ...57S...1D). Circles correspond to the GMRT observed fields (the FWHM of the GMRT primary beam is approximately 85 arcmin at 323 MHz and approximately 44 arcmin at 608 MHz). Axes are J2000.0 Galactic coordinates.


### FITS Images

<p>We provide image files in FITS format for each field at each frequency at both native and re-imaged resolutions with primary beam correction applied (12 FITS images in total). The <b>*_catalogue.FITS</b> files below were used to create the source catalogue presented in this work, each with an image cell size of 1.5 arcsec and CLEAN restoring beam as listed in the paper (<a href="http://adsabs.harvard.edu/abs/2016MNRAS.462.2904A">ads</a>, <a href="https://arxiv.org/abs/1607.07245">arXiv</a>). The <b>*_native.FITS</b> files below are the original image files with the native (ROBUST 0) resolution used to detect the target sources, the results of which were presented in Ainsworth et al. (2016a; <a href="http://adsabs.harvard.edu/abs/2016MNRAS.459.1248A">ads</a>, <a href="https://arxiv.org/abs/1603.06836">arXiv</a>). </p>

#### Catalogue resolution FITS Images (data files too large for GitHub)
* [L1551_323MHz_catalogue.FITS](https://homepages.dias.ie/rainsworth/GMRT-TAU_catalogue/L1551_323MHz_catalogue.FITS) (144.2 MB)
* [L1551_608MHz_catalogue.FITS](https://homepages.dias.ie/rainsworth/GMRT-TAU_catalogue/L1551_608MHz_catalogue.FITS) (144.1 MB)
* [TTau_323MHz_catalogue.FITS](https://homepages.dias.ie/rainsworth/GMRT-TAU_catalogue/TTau_323MHz_catalogue.FITS) (144.1 MB)
* [TTau_608MHz_catalogue.FITS](https://homepages.dias.ie/rainsworth/GMRT-TAU_catalogue/TTau_608MHz_catalogue.FITS) (144.1 MB)
* [DGTau_323MHz_catalogue.FITS](https://homepages.dias.ie/rainsworth/GMRT-TAU_catalogue/DGTau_323MHz_catalogue.FITS) (144.2 MB)
* [DGTau_608MHz_catalogue.FITS](https://homepages.dias.ie/rainsworth/GMRT-TAU_catalogue/DGTau_608MHz_catalogue.FITS) (144.1 MB)

#### Native resolution FITS Images (data files too large for GitHub)
* [L1551_323MHz_native.FITS](https://homepages.dias.ie/rainsworth/GMRT-TAU_catalogue/L1551_323MHz_native.FITS) (64.2 MB)
* [L1551_608MHz_native.FITS](https://homepages.dias.ie/rainsworth/GMRT-TAU_catalogue/L1551_608MHz_native.FITS) (100.1 MB)
* [TTau_323MHz_native.FITS](https://homepages.dias.ie/rainsworth/GMRT-TAU_catalogue/TTau_323MHz_native.FITS) (64.1 MB)
* [TTau_608MHz_native.FITS](https://homepages.dias.ie/rainsworth/GMRT-TAU_catalogue/TTau_608MHz_native.FITS) (100.1 MB)
* [DGTau_323MHz_native.FITS](https://homepages.dias.ie/rainsworth/GMRT-TAU_catalogue/DGTau_323MHz_native.FITS) (64.2 MB)
* [DGTau_608MHz_native.FITS](https://homepages.dias.ie/rainsworth/GMRT-TAU_catalogue/DGTau_608MHz_native.FITS) (100.1 MB)


### CSV source catalogue and PyBDSM output catalogue

The final source catalogue is made available in a machine-readable format as part of the data release (**GMRT-TAU.dat**). In addition, a table providing all the parameter outputs from PyBDSM is provided (**GMRT-TAU_PyBDSM.csv**), see the [online documentation](http://www.astron.nl/citt/pybdsm/) for a full description.
* [GMRT-TAU.pdf](https://github.com/rainsworth/GMRT-TAU_catalogue/GMRT-TAU.pdf) - GMRT-TAU sourcelist of 2062 sources in PDF format
* [GMRT-TAU.dat](https://github.com/rainsworth/GMRT-TAU_catalogue/GMRT-TAU.dat) - GMRT-TAU sourcelist of 2062 sources in CSV format
* [ReadMe](https://github.com/rainsworth/GMRT-TAU_catalogue/ReadMe) - Description of GMRT-TAU.dat
* [GMRT-TAU_PyBDSM.csv](https://github.com/rainsworth/GMRT-TAU_catalogue/GMRT-TAU_PyBDSM.csv) - PyBDSM parameter output for each source detection (1815 detections at 323 MHz and 687 detections at 608 MHz) plus header line


### Scripts used to generate catalogue and diagnostic plots

A series of python scripts were developed to create the final catalogue and diagnostic plots from the PyBDSM catalogue files for each individual field and frequency. These files are available and can be used to re-constitute the catalogue at any time. **make_catalog.py** takes the PyBDSM output for a single field at both frequencies and generates a final catalogue,  complete with spectral indices, source matching between frequencies, and comparisons with other surveys. It outputs these results in a LaTeX format that can then be combined with results from additional fields to make the final GMRT-TAU catalogue. Additional files are also created which can read by **make_plots.py** to generate the diagnostic plots presented in this paper. Finally, a <b>*.csv</b> file is created which contains all of the information in the latex file, in addition to default PyBDSM columns and additional columns used for internal calculation by **make_catalog.py**, but which may be of use in further study.
* [make_catalogue.py](https://github.com/rainsworth/GMRT-TAU_catalogue/blob/master/make_catalogue.py)
* [make_plots.py](https://github.com/rainsworth/GMRT-TAU_catalogue/blob/master/make_plots.py)
* see also Colm Coughlan's [astro-scripts/catalog](https://github.com/colmcoughlan/astro-scripts/tree/master/catalog) repository

If you use the data from this webpage, please cite the paper ([ads](http://adsabs.harvard.edu/abs/2016MNRAS.462.2904A), [arXiv](https://arxiv.org/abs/1607.07245)).
