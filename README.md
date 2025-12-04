# Development Mirror and Issue tracker for SPHINX-II model grid
1D Stellar Atmosphere model grid and spectra for mid-to-late type M-dwarfs from Iyer et al. 2025: https://arxiv.org/abs/2512.02269 
The official archived model grid is preserved in this Zenodo record and should be cited when used. This repo is to be treated as a development mirror and issue tracker.
Users can cite both publication and Zenodo DOI here: https://zenodo.org/records/17782633. Thanks!

If you have any specific model requests or spot any irregularities, please reach out to Aisha Iyer (aishwarya.iyer@nasa.gov). Thank you! 

Model directory structure as follows: 
--------------------------------------
Example code to extract .7z files on bash:
**7z x SPHINXII_condcloud.7z -oSPHINXIIMODELS/**

All "flavors" of SPHINX II models have atmosphere structures in ATMS/ and stellar spectra in SPECTRA/ folders.

(1) SPHINXII_condcloud directory: contains SPHINX II models that assume cloud sedimentation balance (following Ackerman & Marley 2001) and cloud-convection feedback (following Lefèvre et al. 2022).

(2) SPHINXII_graycloud directory: contains SPHINX II models that assume a basic gray cloud that are vertically uniform in distribution. This model grid assumed mixing-length parameter MLT of 1.

(3) SPHINXII_graycloud_MLT0.5 directory: contains SPHINX II models same as (2) however assuming mixing-length parameter MLT of 0.5. Also contains directory for fixed gray cloud opacity of -29 (cm2/g) and mixing-length parameter assumed 0.5--the grid used in Figure 5 of the paper.


