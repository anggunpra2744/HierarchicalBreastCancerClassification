# HierarchicalBreastCancerClassification
Bachelor's thesis project exploring how deep learning–based computer vision can support pathologists by providing accurate and consistent classification of breast cancer malignancy, while maintaining clinical relevance through domain expert collaboration.

Two level-based hierarchical classification approaches are explored:
1. Dual Model (Two flat classifier CNNs)
2. Single Model CNN (Branch CNN)

The dataset used for classification comprised of two public datasets (BACH and BRACS) and one private dataset from RSUD Dr. Soetomo Department of Pathological Anatomy (RSDS). A total of 3,163 images from 3 classes are collected and processed.
1. BACH (2018) -> 300 images
2. BRACS (2021) -> 2,792 images
3. RSDS (2025) -> 71 images



This repository consists of these files:

*Libraries Used:*
-> requirements.txt

*Merging and Naming of Classification Dataset*
-> mergedata.ipynb

*Data Preprocessing*
-> new_data-preprocessing_alldata.ipynb

*Segmentation Model (U-Net with DenseNet121 backbone)*
-> 16ags-norm_newmodel_denseunet.ipynb

*Hierarchical Classification Model 1 - Dual Model*
-> newdual-finetuned_densenet121-model-alldata.ipynb

*Hierarchical Classification Model 2 - Single Model*
-> hc-densenet121-model-alldata-ep20.ipynb (20 epoch)
-> hc-densenet121-model-alldata-ep50.ipynb (50 epoch)
