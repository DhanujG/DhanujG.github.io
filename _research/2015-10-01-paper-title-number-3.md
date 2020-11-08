---
title: "Convolutional neural network-based decision support system for bladder cancer staging in CT urography: decision threshold estimation and validation"
collection: research
permalink: /research/2015-10-01-paper-title-number-3
excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2020-03-16
venue: 'SPIE 11314, Medical Imaging 2020'
paperurl: 'http://academicpages.github.io/files/paper3.pdf'
citation: 'Daniel Hoklai Chapman-Sung, Lubomir Hadjiiski, Dhanuj Gandikota, Heang-Ping Chan, Ravi Samala, Elaine M. Caoili, Richard H. Cohan, Alon Weizer, Ajjai Alva, and Chuan Zhou "Convolutional neural network-based decision support system for bladder cancer staging in CT urography: decision threshold estimation and validation", Proc. SPIE 11314, Medical Imaging 2020: Computer-Aided Diagnosis, 113141T (16 March 2020);'
---
Abstract
Stage T2 is the clinical threshold to administer neoadjuvant chemotherapy for bladder cancer. In this study a deep learning convolutional neural network (DL-CNN) was trained to aid clinicians in staging of bladder cancer in CT Urography (CTU). The DL-CNN utilized two datasets for training and testing. The primary training dataset included 84 bladder cancers from CTU scans of 76 clinically staged patients, 43 cancers were below stage T2, and 41 were stage T2 or above. The second dataset served as an independent test set containing 90 bladder cancers from CTU scans of 86 clinically staged patients, all bladder cancers were staged as T2 or above. Regions of interest (ROIs) were extracted from the lesions as input to the DL-CNN. The model structure and hyper-parameters were determined and asserted using the training dataset of 84 lesions split into two balanced partitions. Based on the lesion-based T2 likelihood score obtained by averaging the scores of all ROIs extracted from a given lesion, the decision threshold providing the highest classification accuracy was determined from the leave-one-out validation. The DL-CNN with the fixed decision threshold was then applied to the test ROIs. The classification accuracy for the independent test set of 90 cancers was 0.91. This performance is slightly higher than our previous radiomics approach based on SVM and BPNN models, which achieved 0.88 and 0.90 accuracy on the same test set, respectively, but the difference was not statistically significant. The results show the promise of using a DL-CNN in bladder cancer stage assessment.

[Download paper here](https://doi.org/10.1117/12.2551309)

Daniel Hoklai Chapman-Sung, Lubomir Hadjiiski, Dhanuj Gandikota, Heang-Ping Chan, Ravi Samala, Elaine M. Caoili, Richard H. Cohan, Alon Weizer, Ajjai Alva, and Chuan Zhou "Convolutional neural network-based decision support system for bladder cancer staging in CT urography: decision threshold estimation and validation", Proc. SPIE 11314, Medical Imaging 2020: Computer-Aided Diagnosis, 113141T (16 March 2020); h