# Multimodal deep learning for materials
If you need help with anything, you can email the email addresses pasted in this ReadMe.

# Step 1: Synthetic Data Generation
First we must generate synthetic data for training the CNN. Notebook 1 above is the MEAP software.<br>
MEAP Software GitHub: https://github.com/DhruboSaha/MEAP-RVE-Microstructure-Generator<br>
MEAP Paper: https://www.sciencedirect.com/science/article/pii/S1359835X25004063?via%3Dihub#da005<br>
Please cite the MEAP paper if you use it. 

# Step 2: CNN Instance Segmentation and Object Detection

Notebook 2.1 is about an assortment of various shapes from the MEAP paper where we do both detection and segmentation. The training datasets as follows:<br>
https://drive.google.com/drive/folders/1WmGYEBYD9PNwq-ylb7QaOl1zeMcSxdSI?usp=sharing<br>
https://drive.google.com/drive/folders/1nTGMuFYgIsCiH8-OIBo9TuPN6yUESRba?usp=sharing<br>

This link is for detection on polygons, which represent SiC particles in notebook 2.2:<br>
https://drive.google.com/drive/folders/1wPKqgeaxcWXDhFuZdTZ3l9CnBM9wuLVu?usp=drive_link<br>
This link is for detection of CFRP shapes in notebook 2.2:<br>
https://drive.google.com/drive/folders/1nQq3rcrT6b3hM5IVQBrEZttAckMd9BfH?usp=drive_link<br>

# Step 3: ANN or Shallow ML on quantified data
Notebook 3.1 on ANN modelling of SiC-Al is demonstrated only for Young's Modulus. All other properties can be done in the same way.<br>

Here's an old video which gives a walkthrough of some of the code and data:<br>
https://drive.google.com/file/d/1klCIoML1hvnEEw6S5Tf5dJjk-z1Antf_/view?usp=drive_link<br>
Observe the format of how these folders are arranged. If you use your own image data, you must organize it in the same way. And you have to adjust the "directories" everywhere in the codes if necessary.

# Paper 
The relevant paper is "A science directed progressive neural network for multimodal prediction of elastoplastic behavior in composite materials" published in Composites Part A. Please email me at dsaha36@gatech.edu or dhrubo.saha.117@gmail.com if you don't have access to the journal, and I will send you the paper.<br>

Perpetual Link: https://www.sciencedirect.com/science/article/pii/S1359835X25004737?via%3Dihub<br>
Limited Time Free View Link: https://www.sciencedirect.com/science/article/pii/S1359835X25004737?dgcid=coauthor<br>
Researchgate Full Paper Access: https://www.researchgate.net/publication/393739217_A_science_directed_progressive_neural_network_for_multimodal_prediction_of_elastoplastic_behavior_in_composite_materials?_sg%5B0%5D=Sd46ertTRLba3CKDVRPWjuNHk0qH1XJn0JIWO367LTpIdLffZUElZMPklJH0B4SHi4-TlV-C34mmgFkQV1B5V0FUI1bRbCAprf8sIDtG.H_tmlx-9S0fXfDfWm5F_8X-l9GoO1A9l49BHx79X2xSoZHxCMgoEsU7TChnwkXj6D6Ui5yV8BSIJuCBJF3vRxw&_tp=eyJjb250ZXh0Ijp7ImZpcnN0UGFnZSI6InB1YmxpY2F0aW9uIiwicGFnZSI6InByb2ZpbGUiLCJwcmV2aW91c1BhZ2UiOiJwcm9maWxlIiwicG9zaXRpb24iOiJwYWdlQ29udGVudCJ9fQ<br>


# Citation
If you use the codes or datasets in your work or find them useful, please cite the paper:

```bibtex
@article{saha2025progressive,
  author  = {Saha, Dhrubo and Sun, Li and Lai, Chang Quan},
  title   = {A science directed progressive neural network for multimodal prediction of elastoplastic behavior in composite materials},
  journal = {Composites Part A: Applied Science and Manufacturing},
  year    = {2025},
  volume  = {199},
  pages   = {109179},
  doi     = {10.1016/j.compositesa.2025.109179}
}
