# plot-3d-brains

Here is some of the code that I use for all kinds of 3D brain plotting. 

### Power Parcellation
`plot_powerROIs_3D.ipynb`: generates 3D plots of Power ROIs in brain space using **matplotlib**. Can be used to generate a single view image or a rotated multi-view image. Also can plot ROI centers or full ROI coverage in brain space. Can be used to show locations of subnetworks, or plot ROI-level fMRI activations at single timepoints. When run in loop can be used to generate several activation images that can be animated as a .gif using `imagemagick` on the commandline.

`plot_ROIs_on_glassBrain.ipynb`: generates interactive 3D plots of Power ROIs on a transparent glass brain using **nilearn**. Can color ROIs based on categorical (i.e. subnetwork membership) or continuous (i.e. activation values) variables.  
