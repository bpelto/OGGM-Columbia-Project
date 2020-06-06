# OGGM-Columbia-Project
Investigating ice thickness for six glaciers in the Columbia Basin relative to surface inversion model output

<img src="images/CBT _ice_thick_cc.png" width="400">

Columbia River basin map with study glaciers

## Notebooks

- Basin_inversion: model ice thickness for the entire Columbia Basin using optimized Glen's A and SMB gradient
- Optimized_run: OGGM run for an individual glacier with optimized A and MB gradient
- MB_gradient_comp_1glacier_gpr: compares ice thickness a glacier between OGGM linear gradient and a user defined mass balance gradient
- alt_dem_anysite_GPR: compares inversion thickness between SRTM and LiDAR DEM, and then compares to GPR obs. of ice thickness
- model_sketch: some documentation of OGGM steps
- optimized thickness: varies Glen's A to optimize modeled fit of observed ice thickness by minimizing the squared quadratic error  between observed and modeled ice thickness
- own_inventory...: both files utilize corrected outlines for Nordic and Illecillewaet glaciers to conduct inversion analyses

Plotting:
- MB_gradient_comp_7panel: plots the OGGM default SMB gradients and in situ SMB gradients
- SMB_gradients_from_point_obs: Calculates and plots linear SMB gradients from point observations of glaciological mass balance 
- dfb_error_scatterplot: plots distance from border exponent against mean absolute error
- distributed_thickness_plotting: optimized OGGM distributed thickness plots
- ice_thick_box_seaborn: creates boxplot of ice thickness from published modeled, observed and OGGM modeled ice thickness
- ice_thickness_plot: plots observed ice thickness for all study glaciers
- mb_grads_thick_scatterplot: creates a 2-panel plot of modeled versus observed ice thickness using different SMB gradients
- oggm_gpr_comp_plot: plots differences in ice thickness between modeled and observed ice thickness 
- smooth_radius_MEA_scatterplot: plot smoothing radius against mean absolute error 7-panel plot
- smooth_window_thick_scatterplot: plot smoothing window against mean absolute error 7-panel plot

Extra:
- Farinotti_2019_volume: calculate ice volume Farinotti et al. 2019 for Columbia Basin
- Resolution: small version of the resolution testing notebook with example given, tests impact of resolution on output on single run
- optimized_thickness-exports: optimized thickness script with further output options
- optimized_thickness-smoothing-DFB-combi-SRadius: optimized thickness script with smoothing radius iteration 
- optimized_thickness-smoothing-DFB-combi: optimized thickness script with distance from border exponent or smoothing window iteration, can also iterate over resolution.

<img src="images/conrad_all_14f_18s_vel_less_5m_spm2.png" width="400">

Ice velocity map for Conrad Glacier using Lidar DEMs from 2014 to 2018 




