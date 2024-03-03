# Lesion-Detection-and-Segmentation-using-Deep-Learning

This project aims to develop deep learning models for comprehensive lesion analysis, encompassing detection, segmentation, classification, and growth analysis across diverse medical imaging modalities (CT scan). This project has the potential to significantly improve efficiency and accuracy in lesion analysis, aiding radiologists in diagnosis, treatment planning, and disease monitoring.

We plan to approach the project in 3 different segments:
1. Universal Lesion Detection: A CNN-based model will be trained to identify and localize diverse lesions throughout 
different body parts, regardless of imaging modality. Performance will be evaluated using sensitivity, specificity, and 
precision on unseen data.
2. Lesion Segmentation and Classification: Building upon detection, U-Net or DeepLab architectures will be leveraged for 
accurate lesion segmentation, followed by classification into distinct types (benign/malignant). Transfer learning from pretrained models will be explored for enhanced performance.
3. Lesion Growth Analysis: RNNs or LSTMs will be employed to analyze longitudinal data, predicting growth patterns and 
potential malignancy based on temporal changes in lesion measurements.

Dataset to be Used: 
The Deep Lesion CT Scans NIH is a publicly available dataset of over 32,000 annotated lesions identified on CT images 
from 4,400 unique patients. It was released in 2018 by the National Institutes of Health (NIH) Clinical Center.
Lesion Types: The dataset encompasses a diverse range of lesions from various organs and tissues, including but not limited 
to:
● Lung nodules
● Liver tumors
● Kidney cysts
● Bone lesions
● Vascular abnormalities
Each lesion is meticulously annotated by radiologists at the NIH Clinical Center. These annotations include:
● Location: Precise coordinates within the CT scan
● Size: Measurements of the lesion's diameter or volume
● Type: Classification of the lesion based on its characteristics (e.g., benign, malignant)
● Additional information: Depending on the specific lesion, annotations may also include details like shape, texture, 
and enhancement patterns.
The dataset can be found on the following: https://nihcc.app.box.com/v/DeepLesion/folder/50715173939
