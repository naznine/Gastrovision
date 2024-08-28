"Detection of various gastrointestinal tract diseases through a deep learning method with ensemble ELM and explainable AI"

https://doi.org/10.1016/j.eswa.2024.124908

title = {Detection of various gastrointestinal tract diseases through a deep learning method with ensemble ELM and explainable AI},

journal = {Expert Systems with Applications},

volume = {256},

pages = {124908},

year = {2024},

issn = {0957-4174},

doi = {https://doi.org/10.1016/j.eswa.2024.124908},

url = {https://www.sciencedirect.com/science/article/pii/S0957417424017755},

author = {Md. Faysal Ahamed and Md. Nahiduzzaman and Md. Rabiul Islam and Mansura Naznine and Mohamed {Arselene Ayari} and Amith Khandakar and Julfikar Haider},

Abstract:

The rising prevalence of gastrointestinal (GI) tract disorders worldwide highlights the urgent need for precise diagnosis, as these diseases greatly affect human life and contribute to high mortality rates. Fast identification, accurate classification, and efficient treatment approaches are essential for addressing this critical health issue. Common side effects include abdominal pain, bloating, and discomfort, which can be chronic and debilitating. Nausea and vomiting are also frequent, leading to difficulties in maintaining adequate nutrition and hydration. The current study intends to develop a deep learning (DL)-based approach that automatically classifies GI tract diseases. For the first time, a GastroVision dataset with 8000 images of 27 different GI diseases was utilized in this work to design a computer-aided diagnosis (CAD) system. This study presents a novel lightweight feature extractor with a compact size and minimum number of layers named Parallel Depthwise Separable Convolutional Neural Network (PD-CNN) and a Pearson Correlation Coefficient (PCC) as the feature selector. Furthermore, a robust classifier named the Ensemble Extreme Learning Machine (EELM), combined with pseudo inverse ELM (ELM) and L1 Regularized ELM (RELM), has been proposed to identify diseases more precisely. A hybrid preprocessing technique, including scaling, normalization, and image enhancement techniques such as erosion, CLAHE, sharpening, and Gaussian filtering, are employed to enhance image representation and improve classification performance. The proposed approach consists of twenty-four layers and only 0.815 million parameters with a 9.79 MB model size. The proposed PD-CNN-PCC-EELM extracts essential features, reduces computational overhead, and achieves excellent classification performance on multiclass GI images. The PD-CNN-PCC-EELM achieved the highest precision, recall, f1, accuracy, ROC-AUC, and AUC-PR values of 88.12 ± 0.332 %, 87.75 ± 0.348 %, 87.12 ± 0.324 %, 87.75 %, 98.89 %, and 92 %, respectively, while maintaining a minimum testing time of 0.000001 s. A comparative study utilizes 10-fold cross-validation, ablation study and various state-of-the-art (SOTA) transfer learning (TL) models as feature extractors. Then, the PCC and EELM are integrated with TL to generate predictions, notably in terms of performance and real-time processing capability; the proposed model significantly outperforms the other models. Moreover, various explainable AI (XAI) methods, such as SHAP (Shapley Additive Explanations), heatmap, guided heatmap, Grad-Cam (Gradient-weighted Class Activation Mapping), guided Grad-CAM, and guided Saliency mapping, have been employed to explore the interpretability and decision-making capability of the proposed model. Therefore, the model provides practical intelligence for increasing confidence in diagnosing GI diseases in real-world scenarios.
