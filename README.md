# CT_DLR

## 1.This is a public repository for the feature files and model files of the paper (Exploring Deep Learning Radiomics for Classifying Osteoporotic Vertebral Fractures in X-ray Images).  
## 2.Radiomic features are extracted using the Python third-party library PyRadiomics.  
## 3.Deep learning features are extracted through the average pooling layer of a pre-trained ResNet50 model, and then compressed through PCA analysis (this step is completed on the PixlMedAI platform, https://p.kdocs.cn/s/SROPMBAAIA).  
## 4.The best_model.pkl model is the best model established after fusing radiomic features and deep learning features.




