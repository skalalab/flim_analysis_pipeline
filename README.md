# Purpose

Fitting Lifetime variables using SPCImage can be error-prone, especially when analyzing big datasets on one's own. 
Therefore, a sanity check method is in need. We use principal component analysis on your uploaded datasets and selected lifetime and morphological variables. PCA is chosen over UMAP and t-SNE because of its speed, which makes it approiate for online usage. 
You can identify the outliers by hovering over the points that show the `base_name` (we assume you dataset has a column called base_name which has the image name and cell number)


# Deployment 
It is deployed on https://skalalab-outlier-finder-main-jwlwqc.streamlit.app/