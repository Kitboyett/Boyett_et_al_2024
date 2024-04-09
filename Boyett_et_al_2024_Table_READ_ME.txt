READ ME 

Boyett_et_al_2024_Table3_Identification_100424.txt
Columns:
id_fors,ra,dec,orig_par_obj,v1.0_par_obj,z_fors,z_fors_err,z_wisp,z_wisp_err,v1.0_redshift,v1.0_redshift_err,flag





Boyett_et_al_2024_Table4_Photometry_100424.txt
Columns:
id_fors,RA,DEC,FLUX_TOTAL_U,FLUXERR_TOTAL_U,FLUX_TOTAL_G,FLUXERR_TOTAL_G,FLUX_TOTAL_F475X,FLUXERR_TOTAL_F475X,FLUX_TOTAL_R,FLUXERR_TOTAL_R,FLUX_TOTAL_F600LP,FLUXERR_TOTAL_F600LP,FLUX_TOTAL_I,FLUXERR_TOTAL_I,FLUX_TOTAL_F814W,FLUXERR_TOTAL_F814W,FLUX_TOTAL_F110W,FLUXERR_TOTAL_F110W,FLUX_TOTAL_F140W,FLUXERR_TOTAL_F140W,FLUX_TOTAL_F160W,FLUXERR_TOTAL_F160W,FLUX_TOTAL_IRAC,FLUXERR_TOTAL_IRAC,comment





Boyett_et_al_2024_Table5_Emission_Lines_100424.txt
Columns:
id_fors,redshift,O_II_Flux_corr,O_II_Flux_err_corr,Hb_Flux_corr,Hb_Flux_err_corr,O_III_Flux_corr,O_III_Flux_err_corr,Ha_Flux_[NII]_corr,Ha_Flux_err_[NII]_corr,S_II_Flux_corr,S_II_Flux_err_corr,O_II_Flux_corr_rc,O_II_Flux_err_corr_rc,Hb_Flux_corr_rc_bc,Hb_Flux_err_corr_rc_bc,O_III_Flux_corr_rc,O_III_Flux_err_corr_rc,Ha_Flux_[NII]_corr_rc_bc,Ha_Flux_err_[NII]_corr_rc_bc,S_II_Flux_corr_rc,S_II_Flux_err_corr_rc,Ha_lum_[NII]_corr,Ha_lum_err_[NII]_corr

- X_Flux_corr, where X = O_II, Hb, O_III or S_II, are the line fluxes corrected for seeing only (O_II and O_III are dublets)
- Ha_Flux_[NII]_corr, is Ha line flux corrected for seeing and [NII] contribution 
- X_Flux_corr_rc, is additionally corrected for reddening (Assuming a Calzetti extinction law and A(Ha)=1)
- Hb_Flux_corr_tc_bc, is additionally corrected for reddening (as above) and Balmer stellar absorption (adopting a Hb EW correction of 3A and a beta slope=-2)
- Hb_Flux_[NII]_corr_tc_bc, is additionally corrected for, [NII] contribution, reddening (as above) and Balmer stellar absorption (adopting a Ha EW correction of 2A and a beta slope=-2)
- 

Fluxes are 1e-17 erg/s/cm2
Ha luminosity is 1e40 erg/s



Boyett_et_al_2024_Table8_Properties_100424.txt
id_fors,SFR_uv,SFR_uv_err,SFR_ha,SFR_ha_err,SFR_sed,SFR_sed_68_l,SFR_sed_68_u,M_star_mean,M_star_median,M_star_68_l,M_star_68_u,Mv,EW_rest_corr,EW_rest_err_corr,metal_O32,metal_O32_err,metal_R23,metal_R23_err,metal_comb,metal_comb_68_u,metal_comb_68_l,comment