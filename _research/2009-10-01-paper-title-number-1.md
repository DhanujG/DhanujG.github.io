---
title: "Bladder cancer staging in CT urography: effect of stage labels on statistical modeling of a decision support system"
collection: research
permalink: /research/2009-10-01-paper-title-number-1
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2018-02-27
venue: 'SPIE 10575, Medical Imaging 2018'
paperurl: 'https://doi.org/10.1117/12.2295013'
citation: 'Dhanuj Gandikota, Lubomir Hadjiiski, Kenny H. Cha, Heang-Ping Chan, Elaine M. Caoili, Richard H. Cohan, Alon Weizer, Ajjai Alva, Chintana Paramagul, Jun Wei, and Chuan Zhou "Bladder cancer staging in CT urography: effect of stage labels on statistical modeling of a decision support system", Proc. SPIE 10575, Medical Imaging 2018: Computer-Aided Diagnosis, 105752B (27 February 2018);'
---
Abstract
In bladder cancer, stage T2 is an important threshold in the decision of administering neoadjuvant chemotherapy. Our long-term goal is to develop a quantitative computerized decision support system (CDSS-S) to aid clinicians in accurate staging. In this study, we examined the effect of stage labels of the training samples on modeling such a system. We used a data set of 84 bladder cancers imaged with CT Urography (CTU). At clinical staging prior to treatment, 43 lesions were staged as below stage T2 and 41 were stage T2 or above. After cystectomy and pathological staging that is considered the gold standard, 10 of the lesions were upstaged to stage T2 or above. After correcting the stage labels, 33 lesions were below stage T2, and 51 were stage T2 or above. For the CDSS-S, the lesions were segmented using our AI-CALS method and radiomic features were extracted. We trained a linear discriminant analysis (LDA) classifier with leave-one-case-out cross validation to distinguish between bladder lesions of stage T2 or above and those below stage T2. The CDSS-S was trained and tested with the corrected post-cystectomy labels, and as a comparison, CDSS-S was also trained with understaged pre-treatment labels and tested on lesions with corrected labels. The test AUC for the CDSS-S trained with corrected labels was 0.89 ± 0.04. For the CDSS-S trained with understaged pre-treatment labels and tested on the lesions with corrected labels, the test AUC was 0.86 ± 0.04. The likelihood of stage T2 or above for 9 out of the 10 understaged lesions was correctly increased for the CDSS-S trained with corrected labels. The CDSS-S is sensitive to the accuracy of stage labeling. The CDSS-S trained with correct labels shows promise in prediction of the bladder cancer stage.

[Download paper here](https://github.com/DhanujG/Bladder-Cancer-Classification-using-ML-and-Computer-Vision-Research)

Recommended citation: Dhanuj Gandikota, Lubomir Hadjiiski, Kenny H. Cha, Heang-Ping Chan, Elaine M. Caoili, Richard H. Cohan, Alon Weizer, Ajjai Alva, Chintana Paramagul, Jun Wei, and Chuan Zhou "Bladder cancer staging in CT urography: effect of stage labels on statistical modeling of a decision support system", Proc. SPIE 10575, Medical Imaging 2018: Computer-Aided Diagnosis, 105752B (27 February 2018);