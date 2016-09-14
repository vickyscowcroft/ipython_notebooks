ipython notebooks used in CRRP and SMHASH
==========================================

These are the ipython notebooks that are used in CRRP and SMHASH.

Note that this repo is **public**, so I don't keep any data files here. I use it only to share the notebooks. Any data files are kept in the private repos corresponding to the paper drafts, or on my computer. Data files are available on request.

Notebooks are commented as much as possible, but if something isn't clear please ask.

I use the python-markdown jupyter extension to enable expansion of variables in the markdown cells. You can find it here:

https://github.com/ipython-contrib/IPython-notebook-extensions

Please note that any bad language in these notebooks is entirely due to VS, and should not be blamed on her students.

Current notebooks
-----------------

* Convolving_uncertianties_PL_FFT.ipynb 
  *  An attempt at deconvolution of the PL components using FFT. Doesn't work yet.

*  Convolving_uncertianties_PL_KDE_extension.ipynb
  *  Meredith's notebook using Kernel Density Estimation (KDE) to represent the metallicity and photometric terms contribution to the PL relation, convolving them together to model the PL.

*  Convolving_uncertianties_PL_gaussians.ipynb
  *  A simple example of convolving gaussian distributions to represent the RRL PL relation.

*  calibrator_pl_fitting.ipynb
  * Fitting the mid-IR parallax stars using the slopes from Reticulum and M4 in various ways.  

* galactic_cepheid_compilation.ipynb
 * Merging Cepheid data from different sources into one coherent table.
 * Lots of examples here of how to tidy data and how to deal with missing data using pandas
 * Example files are cepheids_ir_metallicities.txt, mw_ceps_optical_no_ri, LMC_true_data.dat
 
* smc_multiwavelength_cepheids.ipynb
 * Multiwavelength gloess fits to SMC cepheids
 * Pulls in data from IRAC and GLOESS databases
 * If OGLE data exists, uses that in place of other VI archival
 
* oCen_phot_pipeline_comparison.ipynb
 * Comparison of old and new omega Cen photometry
 * Comparing previous version of photometry with S19.2 reduction
 * All stars, not just RRL

* matching_to_kaluzny.ipynb
 * Matching RRL in oCen fields to Kaluzny catalogs
 * See details in readme file in oCen repo for full details on rejection criteria

* add_new_data_to_gloess_database.ipynb
 * Adds new data to gloess database files
 * Updates files with new photometry in correct format
 * Cleans files removing shitty lines 
 * To do - remove 0.00 mags that have 9.99 errors -- need to read these as NaNs

* galactic_multiwavelength_cepheids.ipynb
 * Does gloess fits of Galactic Cepheids using updated database files
 * Smarter smoothing params partly implemented




