READ ME: column definitions for the 4 tables provided 

Boyett_et_al_2024_Table3_Identification_100424.txt
Columns:
id_fors, 	The VLT/FORS2 id, the combination of the WISP field, the slit mask and slit the target was assigned to (e.g. 309_1_16)
ra, 		Right Ascension (Degrees)
dec,		Declination (Degrees)
orig_par_obj,	The ID from the early WISP emission line catalogues, the combination of the WISP field and object number (e.g. 309_40)
v1.0_par_obj,	The ID from the Battisti et al. (2024) V1.00 catalogue
z_fors,		The redshift determined from FORS2 spectroscopy
z_fors_err,	The associated uncertainty on the redshift determined from FORS2 spectroscopy	
z_wisp,		The redshift determined from WFC3 WFSS
z_wisp_err,	The associated uncertainty on the redshift determined from WFC3 WFSS
v1.0_redshift,	The redshift determined from the Battisti et al. (2024) V1.00 catalogue
v1.0_redshift_err,	The associated uncertainty on the redshift from the Battisti et al. (2024) V1.00 catalogue
flag, 		Single emission line flag for the early WFC3 WFSS catalogue, 0=Multiple 3sigma detections, 1=only one detection above 3sigma, 2=only a single emission line reported in WFC3/WFSS


Boyett_et_al_2024_Table4_Photometry_100424.txt
Columns:
id_fors,				The VLT/FORS2 id, the combination of the WISP field, the slit mask and slit the target was assigned to (e.g. 309_1_16)
RA,					Right Ascension (Degrees)
DEC,					Declination (Degrees)
FLUX_TOTAL_U,FLUXERR_TOTAL_U,		u-band Magellan-Megacam sloan-like photometry (flux and uncertainty) (micro JY)
FLUX_TOTAL_G,FLUXERR_TOTAL_G,		g-band Magellan-Megacam sloan-like photometry (flux and uncertainty) (micro JY)
FLUX_TOTAL_F475X,FLUXERR_TOTAL_F475X,	F475X HST photometry (flux and uncertainty) (micro JY)
FLUX_TOTAL_R,FLUXERR_TOTAL_R,		r-band Magellan-Megacam sloan-like photometry (flux and uncertainty) (micro JY)
FLUX_TOTAL_F600LP,FLUXERR_TOTAL_F600LP,	F600LP HST photometry (flux and uncertainty) (micro JY)
FLUX_TOTAL_I,FLUXERR_TOTAL_I,		i-band WIYN-Mini Mosaic sloan-like photometry (flux and uncertainty) (micro JY)
FLUX_TOTAL_F814W,FLUXERR_TOTAL_F814W,	F814W HST photometry (flux and uncertainty) (micro JY)
FLUX_TOTAL_F110W,FLUXERR_TOTAL_F110W,	F110W HST photometry (flux and uncertainty) (micro JY)
FLUX_TOTAL_F140W,FLUXERR_TOTAL_F140W,	F140W HST photometry (flux and uncertainty) (micro JY)
FLUX_TOTAL_F160W,FLUXERR_TOTAL_F160W,	F160W HST photometry (flux and uncertainty) (micro JY)
FLUX_TOTAL_IRAC,FLUXERR_TOTAL_IRAC,	3.6micron Spitzer/IRAC photometry (flux and uncertainty) (micro JY)
comment,				Notes on galaxies


Boyett_et_al_2024_Table5_Emission_Lines_100424.txt
Columns:
id_fors,						The VLT/FORS2 id, the combination of the WISP field, the slit mask and slit the target was assigned to (e.g. 309_1_16)
redshift,						The spectroscopic redshift from FORS2 when available, otherwise from the early WFC3/WFSS catalogue
O_II_Flux_corr,O_II_Flux_err_corr,			[OII]3727,3729 doublet line flux and uncertainty, corrected for seeing (1e-17 erg/s/cm2)
Hb_Flux_corr,Hb_Flux_err_corr,				Hbeta line flux and uncertainty, corrected for seeing (1e-17 erg/s/cm2)
O_III_Flux_corr,O_III_Flux_err_corr,			[OIII]4959,5007 doublet line flux and uncertainty, corrected for seeing (1e-17 erg/s/cm2)
Ha_Flux_[NII]_corr,Ha_Flux_err_[NII]_corr,		Halpha line flux and uncertainty, corrected for seeing and [NII] contribution (1e-17 erg/s/cm2) 
S_II_Flux_corr,S_II_Flux_err_corr,			[SII] doublet line flux and uncertainty, corrected for seeing  (1e-17 erg/s/cm2)
O_II_Flux_corr_rc,O_II_Flux_err_corr_rc,		[OII]3727,3729 doublet line flux and uncertainty, corrected for seeing, reddening (A(Ha)=1mag), Calzetti+00 extinction law) (1e-17 erg/s/cm2)
Hb_Flux_corr_rc_bc,Hb_Flux_err_corr_rc_bc,		Hbeta line flux and uncertainty, corrected for seeing, reddening (as above), Balmer stellar absorption (adopting a Hb EW correction of 3A and a beta slope=-2) (1e-17 erg/s/cm2)
O_III_Flux_corr_rc,O_III_Flux_err_corr_rc,		[OIII]4959,5007 doublet line flux and uncertainty, corrected for seeing, reddening (as above) (1e-17 erg/s/cm2)
Ha_Flux_[NII]_corr_rc_bc,Ha_Flux_err_[NII]_corr_rc_bc,	Halpha line flux and uncertainty, corrected for seeing, [NII] contribution, reddening (as above), Balmer stellar absorption (adopting a Ha EW correction of 2A and a beta slope=-2) (1e-17 erg/s/cm2)
S_II_Flux_corr_rc,S_II_Flux_err_corr_rc,		[SII] doublet line flux and uncertainty, corrected for seeing, reddening (as above) (1e-17 erg/s/cm2)
Ha_lum_[NII]_corr,Ha_lum_err_[NII]_corr,		Halpha Luminosity and uncertainty, corrected for seeing, [NII] contribution (1e40 erg/s)


Boyett_et_al_2024_Table8_Properties_100424.txt
id_fors,				The VLT/FORS2 id, the combination of the WISP field, the slit mask and slit the target was assigned to (e.g. 309_1_16)
SFR_uv,SFR_uv_err,			Star formation rate and uncertainty, derived from the rest-frame 2800A UV continuum luminosity, adopting the Kennicutt&Evans+12 relation (Msol/yr)
SFR_ha,SFR_ha_err,			Star formation rate and uncertainty, derived from the Halpha luminosity, adopting the Kennicutt&Evans+12 relation (Msol/yr)
SFR_sed,SFR_sed_68_l,SFR_sed_68_u,	Star formation rate, upper and lower 68th percentile uncertainty, derived from the BEAGLE SED fitting (Msol/yr)
M_star_mean,M_star_median,		Mean and Median stellar mass estimates, derived from the BEAGLE SED fitting (log10 M/Msol)
M_star_68_l,M_star_68_u,		Upper and lower 68th percentile uncertainty on the stellar mass, derived from the BEAGLE SED fitting  (log10 M/Msol)
Mv,					Absolute V-band magnitude
EW_rest_corr,EW_rest_err_corr,		Halpha rest-frame equivalent width and uncertainty (Angstrom) 
metal_O32,metal_O32_err,		Oxygen abundance, metallicity derived from O32 line diagnostic adopting Curti at al. (2017,20) relation. 
metal_R23,metal_R23_err,		Oxygen abundance, metallicity derived from R23 line diagnostic adopting Curti at al. (2017,20) relation.
metal_comb,				Oxygen abundance, metallicity derived from maximum likelihood of the O32, R23 and R3 line diagnostics adopting Curti at al. (2017,20) relation.
metal_comb_68_u,metal_comb_68_l,	Upper and lower 68th percentile uncertainty on the metallicity derived from maximum likelihood of the O32, R23 and R3 line diagnostics adopting Curti at al. (2017,20) relation.
comment,				Notes on galaxies
