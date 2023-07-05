# Cloud Feedbacks in Radiative-Convective Equilibrium with Organized Convection

This repository contains the data and scripts used in a paper submitted to JAMES.

Note: The cloud radiative kernels use rrtmg_lw_rcemip.nc which contains the atmospheric composition data used in RRTMG, from Wing et al. (2018). This can be accessed from https://github.com/clstauffer/cloud_feedbacks_rce/tree/main

## DATA

| Data | Description |
|:-----|:------------|
|CFB295300_binnedcrh_allmodels_meancrk_taulim00.json|decomposed cloud feedbacks for 295 K to 300 K for all tau bins|
|CFB295300_binnedcrh_allmodels_meancrk_taulim03.json|decomposed cloud feedbacks for 295 K to 300 K for all but the thinnest tau bins|
|CFB295305_binnedcrh_allmodels_meancrk_taulim00.json|decomposed cloud feedbacks for 300 K to 305 K for all tau bins|
|CFB295305_binnedcrh_allmodels_meancrk_taulim03.json|decomposed cloud feedbacks for 300 K to 305 K for all but the thinnest tau bins|
|CFB300305_binnedcrh_allmodels_meancrk_taulim00.json|decomposed cloud feedbacks for 300 K to 305 K for all tau bins|
|CFB300305_binnedcrh_allmodels_meancrk_taulim03.json|decomposed cloud feedbacks for 300 K to 305 K for all but the thinnest tau bins|
|cloudradiativekernels_RCE_large.tar.gz|cloud radiative kernels
|isccphistograms_RCE_large_1.tar.gz|ISCCP histograms for CRMS 1/2
|isccphistograms_RCE_large_2.tar.gz|ISCCP histograms for CRMS 2/2
|isccphistograms_RCE_large_3.tar.gz|ISCCP histograms for GCRMS and mockwalker
|isccphistograms_RCE_large_4.tar.gz|ISCCP histograms for CESM2

## SCRIPTS

| Data | Description |
|:-----|:------------|
|cloud_kernel.py|create a cloud radiative kernel, requires rrtmg_lw_rcemip.nc (see note above)|
|isccp_hist.py|calculate histogram from ISCCP simulator output|
|tau_ctp_tbr.py|offline ISCCP simulator|
