# Alzheimer-s-Classification-and-visualization-using-Convolutional-Neural-networks

The objective of this project is for the classification of subjects with Alzheimer's Disease using a 2D CNN and a 3D CNN and to visualize the results obtained from CNN using three differnt visualization methods such as Saliency map, Guided Backpropagation and Gradient weighted Class asctivation mapping.
Visualization methods used from https://raghakot.github.io/keras-vis.
3D MRI dataset from ADNI-GO/-2 is used for this project.
Dataset can be obtained by requesting at http://adni.loni.usc.edu/data-samples/access-data/.

Visulization methods are used to identify the regions in the brain that are corresponding to Alzheimer’s disease.
The regions identified by CNN is compared with the regions present in medical literature. 
From the results obtained, it was identified that the Grad-CAM visualization method was able to clearly identify the hippocampus region in both the 2D and 3D CNNs which correspond to the region that is most affected in the case of Alzheimers disease as per the medical literature.

Due to lack of computation power, a subvoulme of the MRI (23 Coronal slices) is only considered as input. 

380 MRI samples for training and vaidation : 173 normal subjects, 207 Alzheime's subjects and 18 unlabelled samples for testing.
Visulaization results can be produced per subject for each Coronal slice in the MRI scan of that particular subject. 

In case the jupyter notebooks are not renderd, it can be be viewed in https://nbviewer.jupyter.org/, by pasting the links of the notebooks.

