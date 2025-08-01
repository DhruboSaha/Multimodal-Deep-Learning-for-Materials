# Multimodal deep learning for materials

# Step 1: Synthetic Data Generation
First we must generate synthetic data for training of the CNN. The Notebook called is taken from the MEAP software.<br>
MEAP Software GitHub: https://github.com/DhruboSaha/MEAP-RVE-Microstructure-Generator<br>
MEAP Paper: https://www.sciencedirect.com/science/article/pii/S1359835X25004063?via%3Dihub#da005<br>
Please cite the MEAP algorithm as well if you use it. 

# Step 2: CNN Instance Segmentation and Object Detection

The following dataset links are pertinent to notebook 2.1. Notebook 2.1 is about an assortment of various shapes from the MEAP paper:
https://drive.google.com/drive/folders/1WmGYEBYD9PNwq-ylb7QaOl1zeMcSxdSI?usp=sharing
https://drive.google.com/drive/folders/1nTGMuFYgIsCiH8-OIBo9TuPN6yUESRba?usp=sharing

The following dataset links are pertinent to notebook 2.2:
This link is for polygons, which represent SiC particles:
https://drive.google.com/drive/folders/1wPKqgeaxcWXDhFuZdTZ3l9CnBM9wuLVu?usp=drive_link
This link is for some shapes which represent CFRP:
https://drive.google.com/drive/folders/1nQq3rcrT6b3hM5IVQBrEZttAckMd9BfH?usp=drive_link

# Step 3: ANN or Shallow ML on quantified data
The notebook on ANN on SiC-Al is demonstrated only for Young's Modulus. All other properties can be done in the same way.


Here's an old video which gives a demonstration of some of the code and data to make it easier to implement:
https://drive.google.com/file/d/1klCIoML1hvnEEw6S5Tf5dJjk-z1Antf_/view?usp=drive_link

# Paper 
The relevant paper is "A science directed progressive neural network for multimodal prediction of elastoplastic behavior in composite materials" published in Composites Part A. Please email me at dsaha36@gatech.edu or dhrubo.saha.117@gmail.com if you don't have access to the journal, and I will send you the paper.

Perpetual Link: https://www.sciencedirect.com/science/article/pii/S1359835X25004737?via%3Dihub
Limited Time Free View Link: https://www.sciencedirect.com/science/article/pii/S1359835X25004737?dgcid=coauthor
Researchgate Full Paper Access: https://www.researchgate.net/publication/393739217_A_science_directed_progressive_neural_network_for_multimodal_prediction_of_elastoplastic_behavior_in_composite_materials?_sg%5B0%5D=Sd46ertTRLba3CKDVRPWjuNHk0qH1XJn0JIWO367LTpIdLffZUElZMPklJH0B4SHi4-TlV-C34mmgFkQV1B5V0FUI1bRbCAprf8sIDtG.H_tmlx-9S0fXfDfWm5F_8X-l9GoO1A9l49BHx79X2xSoZHxCMgoEsU7TChnwkXj6D6Ui5yV8BSIJuCBJF3vRxw&_tp=eyJjb250ZXh0Ijp7ImZpcnN0UGFnZSI6InB1YmxpY2F0aW9uIiwicGFnZSI6InByb2ZpbGUiLCJwcmV2aW91c1BhZ2UiOiJwcm9maWxlIiwicG9zaXRpb24iOiJwYWdlQ29udGVudCJ9fQ


# Note
Observe the format of how these folders are arranged. If you use your own image data, you must organize it in the same way. And you have to adjust the "directories" everywhere in the codes if necessary.

