# COVID-19 classification

This project is an experimental investigation in medical image analysis using deep neural networks to automatically classify COVID-19 abnormalities from chest radiographs.

## Aim
COVID-19 is five times deadlier than flu and PCR-based detection is possible only with a delay of a few hours to days. Although chest radiographs can be obtained in minutes, the similarity of COVID-19 to other bacterial and viral pneumonia on chest radiograms makes diagnosis difficult. This project aims to develop an artificial intelligence model to identify COVID-19 abnormalities from chest radiograms and classify them.

Successful implementation of the project can facilitate quick and confident diagnosis of millions of Covid 19 patients by radiologists. Better diagnosis can help to provide the best care and mitigate the spread and severe effects of the virus.

## Abstract

This project explores deep learning techniques, such as two approaches of transfer learning with pre-trained CNN – deep feature extraction and finetuning that achieved 97.8% and 96.67%, respectively, in classifying chest radiographs as COVID-19 positive and negative. Furthermore, the study proposed a novel CNN model with a simpler architecture and trained end-to-end using 7196 images from the dataset achieving 94.22% accuracy. The model’s classification accuracy was improved to 96.33% by using image pre-processing techniques and retaining simple architecture, making it easy
to finetune and adopt in practical applications.

Furthermore, to verify the executability of the model in a clinical setting, the new CNN model was evaluated on an external dataset. There was a significant drop in accuracy to 40.06%, demonstrating the dataset bias issue in medical image analysis, and the project report discusses possible mitigation strategies. The research study results demonstrate the potential of deep learning for medical diagnosis and the need for further research to make these models executable at the frontlines of clinical practice.
