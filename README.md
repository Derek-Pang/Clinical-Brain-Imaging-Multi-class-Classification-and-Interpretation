# Clinical Brain Imaging Multi-class Classification and Interpretation 
## CNN Model and Layer-wise Relevance Propagation Analysis

This report covered some deep learning applications to clinical brain imaging, from training CNN models to interpreting and visualizing the results. We configured cloud computing machine to utilize all of the ~10,000 MRI images to build three binary classification models (AD/CN, AD/MCI, MCI/CN) and one six-class classification model (CN/EMCI/MCI/LMCI/AD/SMC). We have achieved the same level of top accuracy ratios for binary classification as the start-of-art (>96\%). The accuracy ratio of our six-class models reaches 77.11%. 

In this project, there are several challenges that we have solved: 

(1) generate TFRecords and read them into TensorFlow backend; 

(2) train, save and read a CNN model using multi-GPUs; 

(3) implement layer-wise relevance propagation to brain features resulting in our predictions. 

We also compared the results of two different LRP methods. Our results will provide some insights for clinicians in the field of Alzheimer’s disease.
