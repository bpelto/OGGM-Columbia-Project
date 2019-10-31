# OGGM-Columbia-Project
Investigating ice thickness for six glaciers in the Columbia Basin relative to surface inversion model output

<img src="images/CBT _ice_thick_cc.png" width="400">

Columbia River basin map with study glaciers

<img src="images/conrad_all_14f_18s_vel_less_5m_spm2.png" width="400">

Ice velocity map for Conrad Glacier using Lidar DEMs from 2014 to 2018 

## Notebooks

- Basin inversion: model ice thickness for the entire Columbia Basin using optimized Glen's A and SMB gradient
- MB_gradient_comp_1glacier_gpr: compares ice thickness a glacier between OGGM linear gradient and a user defined mass balance gradient
- MB_gradient_comp_7panel: plots the OGGM default SMB gradients and in situ SMB gradients
- SMB_gradients_from_point_obs: Calculates and plots SMB gradients for all study glaciers from point observations
- alt_dem_anysite_GPR: compares inversion thickness between SRTM and LiDAR DEM, and then compares to GPR obs. of ice thickness
- ice_thickness_plot: plots observed ice thickness for all study glaciers
- model_sketch: some documentation of OGGM
- optimized thickness: varies Glen's A to optimize modeled fit of observed ice thickness by minimizing the squared quadratic error  between observed and modeled ice thickness
- own_inventory...: both files utilize corrected outlines for Nordic and Illecillewaet glaciers to conduct inversion analyses
- srtm_lidar: outdated plot of SRTM versus LiDAR inversion thickness


