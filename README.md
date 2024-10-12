# Neuropixels course 2024

This repository contains all resources and assignments for the quality control part of [UCL's 2024 Neuropixels Course](https://www.ucl.ac.uk/neuropixels/training/2024-neuropixels-course). If you run into any issues or have any questions, you can send a message on the #2_2-quality-control channel of the 2024 UCL Neuropixels Cours slack or create a github issue here. 

We will go over a typical worksflow to assess unit quality, using a freely available dataset. Happy quality control-ing! 

## Setting up 
We will use a freely available dataset generated by Nick Steinmetz that spans visual cortex, hippocampus, and some parts of thalamus in a mouse. This dataset was recorded on an early version of Neuropixels probes, and spike-sorted using Kilosort2, but all these principles and methods are applicable accross Neuropixels probe types and Kilosort versions. 

### Download data
All the necessary data is located [here](https://rdr.ucl.ac.uk/articles/dataset/Recording_with_a_Neuropixels_probe/25232962/1). You will need to donwload in put in one same folder the following files: 
    - amplitudes.npy
    - channel_map.npy
    - spike_templates.npy
    - spike_times.npy
    - template_feature_ind.npy
    - templates.npy
    - params.py
    - pc_feature_ind.npy
    - similar_templates.noy
    - whitening_mat.npy
    - whitening_mat_inv.npy
    - channel_positions.npy
    - stimInfo.mat
    - pc_features.pny
    - pc_features_ind.npy
    - Hopkins_20160722_g0_t0.imec.ap.meta
    - rawDataSample.bin
Make you sure you *do not* have the following files:     
    - cluster_groups.csv
    - spike_clusters.npy
### Download and install bombcell
- MATLAB users

- Python users 
### Download and install phy

## Run bombcell 
- MATLAB users

- Python users 
## Inspect and refine results 
### General inspection
- Using UpSet plots, Hg, Wvf. check performing well. 
- Using the GUI. check performing well. 
- Using Phy
### Refine a threshold
- Use Phy to set qMetric.spatialDecay. Find in docs.
### Refinbe: splitting and merging 
