# Evaluating the reliability of human brain white matter tractometry

## HCP_TRT.ipynb
Access to HCP data can be requested here: https://db.humanconnectome.org/

After that you can run HCP_TRT.ipynb to reproduce plots that use profiles from HCP.

Note that this script uses AWS by default and will reproduce all of the processing done with pyAFQ.

The script can be easily modified to run locally instead. 

## wDSC.ipynb
You can run wDSC.ipynb to reproduce plots that use wDSC from HCP.

This script also uses AWS by default but can be easily modified to run locally.

It requires that HCP_TRT.ipynb be run first.

## UW_PREK.ipynb
We have made the UW_PREK profile data available to anyone.

Run UW_PREK.ipynb to download the profile data and reproduce our plots.

You can view the UW_PREK data using AFQ browser and these links:
https://yeatmanlab.github.io/UW_PREK_pyAFQ_pre_browser/
https://yeatmanlab.github.io/UW_PREK_pyAFQ_post_browser/

https://yeatmanlab.github.io/UW_PREK_mAFQ_pre_browser/
https://yeatmanlab.github.io/UW_PREK_mAFQ_post_browser/
