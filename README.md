# Deep Learning Papers on Medical Image Analysis

## Background
To the best of our knowledge, this is the first list of deep learning papers on medical applications. There are couple of lists for deep learning papers in general, or computer vision, for example [Awesome Deep Learning Papers](https://github.com/terryum/awesome-deep-learning-papers.git). In this list, I try to classify the papers based on their deep learning techniques and learning methodology. I believe this list could be a good starting point for DL researchers on Medical Applications. 

## Criteria

1. A list of **top deep learning papers** published since 2015.
2. Papers are collected from peer-reviewed journals and high reputed conferences. However, it may have recent papers on arXiv. 
3. A meta-data is required along with the paper, i.e. Deep Learning technique, Imaging Modality, Area of Interest, Clinical Database (DB). 

*List of Journals / Conferences (J/C):*

- **[Medical Image Analysis (MedIA)](https://www.journals.elsevier.com/medical-image-analysis/)**
- **[IEEE Transaction on Medical Imaging (IEEE-TMI)](https://ieee-tmi.org/)**
- **[IEEE Transaction on Biomedical Engineering (IEEE-TBME)](http://tbme.embs.org/)**
- **[IEEE Journal of Biomedical and Health Informatics (IEEE-JBHI)](http://jbhi.embs.org/)**
- **[International Journal on Computer Assisted Radiology and Surgery (IJCARS)](http://www.springer.com/medicine/radiology/journal/11548)**
- **International Conference on Information Processing in Medical Imaging (IPMI)**
- **International Conference on Medical Image Computing and Computer Assisted Intervention (MICCAI)**
- **International Conference on Information Processing in Computer-Assisted Interventions (IPCAI)**
- **IEEE International Symposium on Biomedical Imaging (ISBI)**

## Shortcuts

*Deep Learning Techniques:*

- NN: Neural Networks 
- MLP: Multilayer Perceptron 
- RBM: Restricted Boltzmann Machine
- SAE: Stacked Auto-Encoders
- CAE: Convolutional Auto-Encoders
- CNN: Convolutional Neural Networks 
- RNN: Recurrent Neural Networks
- LSTM: Long Short Term Memory
- M-CNN: Multi-Scale/View/Stream CNN
- FCN: Fully Convolutional Networks

*Imaging Modality:*

- US: Ultrasound 
- MR/MRI: Magnetic Resonance Imaging 
- PET: Positron Emission Tomography
- MG: Mammography
- CT: Computed Tompgraphy
- H&E: Hematoxylin & Eosin Histology Images
- RGB: Optical Images 


## Table of Contents
### Deep Learning Techniques 
* [AutoEncoders/ Stacked AutoEncoders](#autoencoders--stacked-autoencoders)
* [Convolutional Neural Networks](#convolutional-neural-networks)
* [Recurrent Neural Networks](#recurrent-neural-networks)
* [Generative Adversarial Networks](#generative-adversarial-networks)

### Medical Applications 
* [Annotation](#annotation)
* [Classification](#classification)
* [Detection/ Localization](#detection--localization)
* [Segmentation](#segmentation)
* [Registration](#registration)
* [Regression](#regression)
* [Other tasks](#other-tasks)

* * * 
### Deep Learning Techniques 
#### Auto-Encoders/ Stacked Auto-Encoders
- 

#### Convolutional Neural Networks
- [AggNet: Deep Learning From Crowds for Mitosis Detection in Breast Cancer Histology Images](http://ieeexplore.ieee.org/document/7405343/)
- [Fast Convolutional Neural Network Training Using Selective Data Sampling: Application to Hemorrhage Detection in Color Fundus Images](http://ieeexplore.ieee.org/document/7401052/#full-text-section)

#### Recurrent Neural Networks
- 

#### Generative Adversarial Networks
- 

### Medical Applications 

#### Annotation 
| Technique | Modality | Area | Paper Title| DB | J/C | Year |
| ------ | ----------- | ----------- | ----------- |---|----------- | ---- |
| NN | H&E | N/A | Deep learning of feature representation with multiple instance learning for medical image analysis [[pdf]]() | | ICASSP| 2014|
| M-CNN   | H&E | Breast | AggNet: Deep Learning From Crowds for Mitosis Detection in Breast Cancer Histology Images [[pdf]](http://ieeexplore.ieee.org/document/7405343/) | [AMIDA](amida13.isi.uu.nl)| IEEE-TMI | 2016| 

#### Classification

| Technique | Modality | Area | Paper Title| DB | J/C | Year |
| ------ | ----------- | ----------- | ----------- |---|----------- | ---- |
| M-CNN | CT | Lung | Multi-scale Convolutional Neural Networks for Lung Nodule Classification [[pdf]](https://link.springer.com/chapter/10.1007/978-3-319-19992-4_46) | [LIDC-IDRI](https://wiki.cancerimagingarchive.net/display/Public/LIDC-IDRI)| IPMI| 2015|
| 3D-CNN | MRI | Brain | Predicting Alzheimer's disease: a neuroimaging study with 3D convolutional neural networks [[pdf]](https://arxiv.org/abs/1502.02506) | [ADNI](adni.loni.usc.edu)| arXiv | 2015 |
| CNN+RNN| RGB | Eye | Automatic Feature Learning to Grade Nuclear Cataracts Based on Deep Learning [[pdf]](https://pdfs.semanticscholar.org/2650/44769c0a35228d8512570f7ec4cc38e1c511.pdf)| | IEEE-TBME | 2015|
| CNN   | X-ray | Knee | Quantifying Radiographic Knee Osteoarthritis Severity using Deep Convolutional Neural Networks [[pdf]](https://arxiv.org/pdf/1609.02469) | [O.E.1](https://oai.epi-ucsf.org/datarelease/)| arXiv | 2016|
| CNN | H&E | Thyroid | A Deep Semantic Mobile Application for Thyroid Cytopathology [[pdf]](http://proceedings.spiedigitallibrary.org/proceeding.aspx?articleid=2513164) | | SPIE | 2016|
| 3D-CNN, 3D-CAE | MRI | Brain | Alzheimer's Disease Diagnostics by a Deeply Supervised Adaptable 3D Convolutional Network [[pdf]](https://arxiv.org/pdf/1607.00556.pdf) | [ADNI](adni.loni.usc.edu) | arXiv| 2016
| M-CNN | RGB | Skin| Multi-resolution-tract CNN with hybrid pretrained and skin-lesion trained layers [[pdf]](http://www.cs.sfu.ca/~hamarneh/ecopy/miccai_mlmi2016a.pdf)|[Dermofit](https://licensing.eri.ed.ac.uk/i/software/dermofit-image-library.html)| MLMI | 2016|
| CNN | RGB | Skin, Eye | Towards Automated Melanoma Screening: Exploring Transfer Learning Schemes [[pdf]](https://arxiv.org/pdf/1609.01228.pdf)| [EDRA](http://dermoscopy.org/), [DRD](https://www.kaggle.com/c/diabetic-retinopathy-detection) | arXiv | 2016|
| M-CNN | CT | Lung | Pulmonary Nodule Detection in CT Images: False Positive Reduction Using Multi-View Convolutional Networks [[pdf]](https://www.researchgate.net/profile/Geert_Litjens/publication/296624579_Pulmonary_Nodule_Detection_in_CT_Images_False_Positive_Reduction_Using_Multi-View_Convolutional_Networks/links/57f254cf08ae8da3ce517202.pdf) |  [LIDC-IDRI](https://wiki.cancerimagingarchive.net/display/Public/LIDC-IDRI), [ANODE09](https://anode09.grand-challenge.org/), [DLCST](https://clinicaltrials.gov/ct2/show/study/NCT00496977) | IEEE-TMI | 2016|
| 3D-CNN | MRI | Brain | 3D Deep Learning for Multi-modal Imaging-Guided Survival Time Prediction of Brain Tumor Patients [[pdf]](http://www.unc.edu/~eadeli/publications/Dong_MICCAI2016.pdf)| |MICCAI | 2016|
| SAE | US, CT | Breast, Lung | Computer-Aided Diagnosis with Deep Learning Architecture: Applications to Breast Lesions in US Images and Pulmonary Nodules in CT Scans [[pdf]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4832199/pdf/srep24454.pdf) | [LIDC-IDRI](https://wiki.cancerimagingarchive.net/display/Public/LIDC-IDRI)| Nature | 2016| 
| CAE | MG | Breast |Unsupervised deep learning applied to breast density segmentation and mammographic risk scoring [[pdf]](http://image.diku.dk/igel/paper/UDLAtBDSaMRS.pdf) | | IEEE-TMI | 2016| 
| GCN | MRI | Brain | Spectral Graph Convolutions for Population-based Disease Prediction [[pdf]](http://arxiv.org/abs/1703.03020) | [ADNI](http://adni.loni.usc.edu), [ABIDE](http://preprocessed-connectomes-project.org/abide/) | arXiv | 2017| 





#### Detection / Localization

| Technique | Modality | Area | Paper Title| DB | J/C | Year |
| ------ | ----------- | ----------- | ----------- |---|----------- | ---- |
| MLP   | CT | Head-Neck | 3D Deep Learning for Efficient and Robust Landmark Detection in Volumetric Data [[pdf]](https://pdfs.semanticscholar.org/6cd3/ea4361e035969e6cf819422d0262f7c0a186.pdf) | | MICCAI | 2015|
| CNN   | US | Fetal | Standard Plane Localization in Fetal Ultrasound via Domain Transferred Deep Neural Networks [[pdf]](http://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7090943) | | IEEE-JBHI | 2015|
| 2.5D-CNN   | MRI | Femur | Automated anatomical landmark detection ondistal femur surface using convolutional neural network [[pdf]](http://webpages.uncc.edu/~szhang16/paper/ISBI15_knee.pdf) | [OAI](https://oai.epi-ucsf.org/datarelease/)| ISBI | 2015|
| LSTM   | US | Fetal | Automatic Fetal Ultrasound Standard Plane Detection Using Knowledge Transferred Recurrent Neural Networks [[pdf]](https://link.springer.com/chapter/10.1007/978-3-319-24553-9_62) | | MICCAI | 2015|
| CNN   | X-ray, MRI | Hand | Regressing Heatmaps for Multiple Landmark Localization using CNNs [[pdf]](https://www.tugraz.at/fileadmin/user_upload/Institute/ICG/Images/team_bischof/mib/paper_pdfs/MICCAI2016_CNNHeatmaps.pdf) | [DHADS](http://www.ipilab.org/BAAweb/)| MICCAI | 2016|
| CNN   | MRI, US, CT | - | An artificial agent for anatomical landmark detection in medical images [[pdf]](https://www5.informatik.uni-erlangen.de/Forschung/Publikationen/2016/Ghesu16-AAA.pdf) | [SATCOM](http://stacom.cardiacatlas.org/lv-landmark-detection-challenge/)| MICCAI | 2016|
| FCN   | US | Fetal | Real-time Standard Scan Plane Detection and Localisation in Fetal Ultrasound using Fully Convolutional Neural Networks [[pdf]](https://www.doc.ic.ac.uk/~bkainz/publications/Kainz_MICCAI2016b.pdf) | | MICCAI | 2016|
| CNN+LSTM   | MRI | Heart | Recognizing end-diastole and end-systole frames via deep temporal regression network [[pdf]](https://link.springer.com/chapter/10.1007/978-3-319-46726-9_31) | | MICCAI | 2016|
| M-CNN  | MRI | Heart | Improving Computer-Aided Detection Using Convolutional Neural Networks and Random View Aggregation Neural Networks [[pdf]](http://www.cs.jhu.edu/~lelu/publication/07279156.pdf) | | IEEE-TMI | 2016|
| CNN  | PET/CT | Heart | Automated detection of pulmonary nodules in PET/CT images: Ensemble false-positive reduction using a convolutional neural network technique Neural Networks [[pdf]](http://onlinelibrary.wiley.com/doi/10.1118/1.4948498/epdf) | | MP | 2016|
| 3D-CNN  | MRI | Brain | Automatic Detection of Cerebral Microbleeds From MR Images via 3D Convolutional Neural Networks [[pdf]](http://ieeexplore.ieee.org/document/7403984/#full-text-section) | | IEEE-TMI | 2016|
| CNN  | X-ray, MG | - | Self-Transfer Learning for Fully Weakly Supervised Lesion Localization [[pdf]](https://link.springer.com/chapter/10.1007/978-3-319-46723-8_28) | [NIH,China](http://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6663723), [DDSM,MIAS](http://www.mammoimage.org/databases/)  | MICCAI | 2016|
| CNN  | RGB | Eye | Fast Convolutional Neural Network Training Using Selective Data Sampling: Application to Hemorrhage Detection in Color Fundus Images [[pdf]](http://ieeexplore.ieee.org/document/7401052/#full-text-section) | [DRD](https://www.kaggle.com/c/diabetic-retinopathy-detection/data), [MESSIDOR](http://www.adcis.net/en/Download-Third-Party/Messidor.html)  | MICCAI | 2016|
| GAN  | - | - | Unsupervised Anomaly Detection with Generative Adversarial Networks to Guide Marker Discovery | | IPMI | 2017|

#### Segmentation
| Technique | Modality | Area | Paper Title| DB | J/C | Year |
| ------ | ----------- | ----------- | ----------- |---|----------- | ---- |
| U-Net  | - | - | U-net: Convolutional networks for biomedical image segmentation | | MICCAI | 2015|



#### Registration
- 

#### Regression

| Technique | Modality | Area | Paper Title| DB | J/C | Year |
| ------ | ----------- | ----------- | ----------- |---|----------- | ---- |
| 2.5D-CNN   | MRI | | Automated anatomical landmark detection ondistal femur surface using convolutional neural network [[pdf]](http://webpages.uncc.edu/~szhang16/paper/ISBI15_knee.pdf) | [OAI](https://oai.epi-ucsf.org/datarelease/)| ISBI | 2015|


#### Other tasks
- 


## References 
