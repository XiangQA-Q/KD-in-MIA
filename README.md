# Knowledge-distillation-and-teacher-student-learning-in-medical-imaging
This is the repository of **Knowledge distillation and teacher-student learning in medical imaging: comprehensive overview, pivotal role, and future directions**, the article offers a thorough review of the current state of research concerning the application of Knowledge distillation in medical imaging.

## Abstract
Knowledge Distillation (KD) is a technique to transfer the knowledge from a complex model to a simplified model. It has been widely used in natural language processing and computer vision and has achieved advanced results. Recently, the research of KD in medical image analysis has grown rapidly. The definition of knowledge has been further expanded by combining with the medical field, and its role is not limited to simplifying the model. This paper attempts to comprehensively review the development and application of KD in the medical imaging field. Specifically, we first introduce the basic principles, explain the definition of knowledge and the classical teacher-student network framework. Then, the research progress in medical image classification, segmentation, detection, reconstruction, registration, radiology report generation, privacy protection and other application scenarios is presented. In particular, the introduction of application scenarios is based on the role of KD. We summarize eight main roles of KD techniques in medical image analysis, including model compression, semi-supervised method, weakly supervised method, class balancing, etc. The performance of these roles in all application scenarios is analyzed. Finally, we discuss the challenges in this filed and propose potential solutions. KD is still in a rapid development stage in the medical imaging field, we give four potential development directions and research hotspots.


## KD in Medical image diagnosis and classification

|Paper|PDF|Code|
|---|---|---|
|Knowledge distillation in histology landscape by multi-layer features supervision|[PDF](https://ieeexplore.ieee.org/abstract/document/10018566)|[Code]()|
|Covid-mobilexpert: On-device covid-19 screening using snapshots of chest x-ray|[PDF](https://europepmc.org/article/ppr/ppr346253)|[Code](https://github.com/xinli0928/COVID-Xray)|
|Classification of histopathologic images of breast cancer by multi-teacher small-sample knowledge distillation|[PDF](https://ieeexplore.ieee.org/abstract/document/9797592)|[Code]()|
|ADINet: Attribute driven incremental network for retinal image classification|[PDF](https://openaccess.thecvf.com/content_CVPR_2020/html/Meng_ADINet_Attribute_Driven_Incremental_Network_for_Retinal_Image_Classification_CVPR_2020_paper.html)|[Code]()|
|Pathological image classification via embedded fusion mutual learning|[PDF](https://www.sciencedirect.com/science/article/abs/pii/S1746809422006358)|[Code]()|
|Ssd-kd: A self-supervised diverse knowledge distillation method for lightweight skin lesion classification using dermoscopic images|[PDF](https://www.sciencedirect.com/science/article/abs/pii/S1361841522003218)|[Code](https://github.com/enkiwang/Portable-Skin-Lesion-Diagnosis)|
|Distilling Knowledge from Topological Representations for Pathological Complete Response Prediction|[PDF](https://link.springer.com/chapter/10.1007/978-3-031-16434-7_6)|[Code](https://github.com/zoedsy/DK_Topology_PCR)|
|Explainable Knowledge Distillation for On-Device Chest X-Ray Classification|[PDF](https://ieeexplore.ieee.org/abstract/document/10114588)|[Code]()|
|Lightweight convolutional neural network with knowledge distillation for cervical cells classification|[PDF](https://www.sciencedirect.com/science/article/abs/pii/S1746809421007746)|[Code]()|
|Overcoming limitation of dissociation between MD and MI classifications of breast cancer histopathological images through a novel decomposed feature-based knowledge distillation method|[PDF](https://www.sciencedirect.com/science/article/abs/pii/S0010482522002050)|[Code]()|
|Resolution-based distillation for efficient histology image classification|[PDF](https://www.sciencedirect.com/science/article/pii/S0933365721001299)|[Code]()|
|Fine-grained interactive attention learning for semi-supervised white blood cell classification|[PDF](https://www.sciencedirect.com/science/article/abs/pii/S1746809422001331)|[Code]()|
|Automatic grading assessments for knee MRI cartilage defects via self-ensembling semi-supervised learning with dual-consistency|[PDF](https://www.sciencedirect.com/science/article/abs/pii/S1361841522001554)|[Code](https://github.com/King-HAW/DC-MT)|
|Semi-supervised classification of radiology images with NoTeacher: A teacher that is not mean|[PDF](https://www.sciencedirect.com/science/article/abs/pii/S1361841521001948)|[Code]()|
|Semi-supervised medical image classification with relation-driven self-ensembling model|[PDF](https://ieeexplore.ieee.org/abstract/document/9095275)|[Code]()|
|Semi-supervised training of deep convolutional neural networks with heterogeneous data and few local annotations: An experiment on prostate histopathology image classification|[PDF](https://www.sciencedirect.com/science/article/pii/S1361841521002115)|[Code]()|
|Bi-directional weakly supervised knowledge distillation for whole slide image classification|[PDF](https://proceedings.neurips.cc/paper_files/paper/2022/hash/62c9aa4d48329a85d1e36d5b6d0a6a32-Abstract-Conference.html)|[Code](https://github.com/miccaiif/WENO)|
|Learning to learn by yourself: Unsupervised meta-learning with self-knowledge distillation for COVID-19 diagnosis from pneumonia cases|[PDF](https://onlinelibrary.wiley.com/doi/abs/10.1002/int.22449)|[Code]()|
|MRI-based Alzheimer’s disease prediction via distilling the knowledge in multi-modal data|[PDF](https://www.sciencedirect.com/science/article/pii/S1053811921008594)|[Code]()|
|Enhanced breast lesion classification via knowledge guided cross-modal and semantic data augmentation|[PDF](https://link.springer.com/chapter/10.1007/978-3-030-87240-3_6)|[Code]()|
|Gradient modulated contrastive distillation of low-rank multi-modal knowledge for disease diagnosis|[PDF](https://www.sciencedirect.com/science/article/abs/pii/S1361841523001342)|[Code]()|
|GMRLNet: A graph-based manifold regularization learning framework for placental insufficiency diagnosis on incomplete multimodal ultrasound data|[PDF](https://ieeexplore.ieee.org/abstract/document/10130337)|[Code]()|
|Relational subsets knowledge distillation for long-tailed retinal diseases recognition|[PDF](https://link.springer.com/chapter/10.1007/978-3-030-87237-3_1)|[Code]()|
|Long-Tailed Multi-label Retinal Diseases Recognition via Relational Learning and Knowledge Distillation|[PDF](https://link.springer.com/chapter/10.1007/978-3-031-16434-7_68)|[Code](https://github.com/liyiersan/RLKD)|
|Diagnosing glaucoma on imbalanced data with self-ensemble dual-curriculum learning|[PDF](https://www.sciencedirect.com/science/article/abs/pii/S1361841521003406)|[Code]()|
|Synergic adversarial label learning for grading retinal diseases via knowledge distillation and multi-task learning|[PDF](https://ieeexplore.ieee.org/abstract/document/9328568)|[Code]()|
|Flat-aware cross-stage distilled framework for imbalanced medical image classification|[PDF](https://link.springer.com/chapter/10.1007/978-3-031-16437-8_21)|[Code]()|
|Melanoma classification from dermatoscopy images using knowledge distillation for highly imbalanced data|[PDF](https://www.sciencedirect.com/science/article/abs/pii/S0010482523000367)|[Code]()|
|Categorical relation-preserving contrastive knowledge distillation for medical image classification|[PDF](https://link.springer.com/chapter/10.1007/978-3-030-87240-3_16)|[Code](https://github.com/hathawayxxh/CRCKD)|
|COVID-19 automatic diagnosis with radiographic imaging: Explainable attention transfer deep neural networks|[PDF](https://ieeexplore.ieee.org/abstract/document/9410346)|[Code]()|
|Knowledge distillation to ensemble global and interpretable prototype-based mammogram classification models|[PDF](https://link.springer.com/chapter/10.1007/978-3-031-16437-8_2)|[Code]()|
|RadioTransformer: a cascaded global-focal transformer for visual attention--guided disease classification|[PDF](https://link.springer.com/chapter/10.1007/978-3-031-19803-8_40)|[Code](https://github.com/bmi-imaginelab/radiotransformer)|
|MF-OMKT: Model fusion based on online mutual knowledge transfer for breast cancer histopathological image classification|[PDF](https://www.sciencedirect.com/science/article/abs/pii/S0933365722001853)|[Code]()|
|Improving the explainability of skin cancer diagnosis using CBIR|[PDF](https://link.springer.com/chapter/10.1007/978-3-030-87199-4_52)|[Code](https://github.com/catarina-barata/CBIR_Explainability_Skin_Cancer)|
