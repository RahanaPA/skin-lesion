# Skin Lesion Analyser 

This repository contains code for the paper, Skin Lesion Classification

### Overview
Skin cancer, the most typical form of cancer, is a critical public health problem with 123,000 newly diagnosed melanoma cases and over 3 million non-melanoma cases worldwide each year. The leading cause of skin cancer is high exposure of skin cells to UV radiation, which can damage the DNA inside skin cells leading to uncontrolled growth of skin cells. Early detection and screening of skin cancer have the potential to reduce mortality and morbidity. We propose a seven-way automated multi-class skin cancer classification system having performance comparable with expert dermatologists. We used a pretrained MobileNet model to train over HAM10000 dataset using transfer learning. The model classifies skin lesion image with a categorical accuracy of 83.15%, top2 accuracy of 91.36% and top3 accuracy of 95.34%. The weighted average of precision, recall, and f1-score were found to be 0.89, 0.83, and 0.83 respectively. The model has been deployed as a web application for use at (https://RahanaPA.github.io). The TensorFlow.js library was used to convert and train MobileNet model in JavaScript. The web application interface was developed with HTML, CSS and JavaScript.

### Web Application
https://RahanaPA.github.io