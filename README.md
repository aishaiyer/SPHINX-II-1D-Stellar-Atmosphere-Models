# SPHINX-II-1D-Stellar-Atmosphere-Models
1D Stellar Atmosphere model grid and spectra for mid-to-late type M-dwarfs from Iyer et al. 2025. 
Hosting model grid files on github. Github link listed on zenodo repository that is linked in the publication.
Users can cite both publication and Zenodo DOI. Thanks!
Please reach out to Aisha Iyer (aishwarya.iyer@nasa.gov) if you have any specific model requests. Thank you! 

Model directory structure as follows: 

All "flavors" of SPHINX II models have atmosphere structures in ATMS/ and stellar spectra in SPECTRA/ folders.

(1) SPHINXII_condcloud directory: contains SPHINX II models that assume cloud sedimentation balance (following Ackerman & Marley 2001) and cloud-convection feedback (following Lefèvre et al. 2022).

(2) SPHINXII_graycloud directory: contains SPHINX II models that assume a basic gray cloud that are vertically uniform in distribution. This model grid assumed mixing-length parameter MLT of 1.

(3) SPHINXII_graycloud_MLT0.5 directory: contains SPHINX II models same as (2) however assuming mixing-length parameter MLT of 0.5. Also contains directory for fixed gray cloud opacity of -29 (cm2/g) and mixing-length parameter assumed 0.5--the grid used in Figure 5 of the paper.

