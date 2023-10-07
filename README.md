# 1D-CNN-for-bio-Raman-Spectroscopy
A 1D CNN architecture for classifying Raman spectra of biological samples with explainability technique based on Grad-CAM.
I used this code to classify Raman spectra of human tumour cell lines according to their radiation sensitivity, but the model can be used for classifying cell and tissue data according to other features (e.g., cancer vs non-cancer, ki67 status).
The explainability technique is based on Grad-CAM but the gradients are not globally averaged as we found this increases the resolution of the maps for spectral data. The heatmaps highlight in red the most important spectral peaks corresponding to a given classification results. We used the heatmaps to identify the Raman peaks, and therefore biomolecules, associated with radioresistance and radiosensitivity in our cell lines. 
To use our code, have your Raman spectra data and labels in an .xlsx or .csv file.

Authors: Alejandra Fuentes and Mitchell Wiebe. 
