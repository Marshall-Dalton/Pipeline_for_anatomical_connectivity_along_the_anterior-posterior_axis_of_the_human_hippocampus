# Pipeline_for_anatomical_connectivity_along_the_anterior-posterior_axis_of_the_human_hippocampus

This repository contains code for the following preprint paper:

Marshall A Dalton, Arkiev D'Souza, Jinglei Lv and Fernando Calamante. "Anatomical connectivity along the anterior-posterior axis of the human hippocampus: new insights using quantitative fibre-tracking." bioRxiv (2021).

Please cite this paper if you use the scrips or code. License: CC0 1.0 Universal.


Instructions:
There are 3 steps to characterise anatomical connectivity along the anterior-posterior axis of the human hippocampus. You will need T1w and Diffusion MRI data. HCP data is used for this paper.

Step 1: 1_Preprocessing_and_whole_brain_tractography.pbs

        Preprocessing (in addition to minimal processing done by HCP) and whole brain tractography.

Step 2: 2_Hippocampus_tractography.pbs

        Use this script to conduct hippocampus tractography.

Step 3: 3_Anterior_posterior_axis_connectivity.pbs

        Use this script to conduct hippocampus tractography specific to the head, body and tail of the hippocampus.

