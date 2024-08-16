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

## KD in Medical image segmentation

|Paper|PDF|Code|
|---|---|---|
|Enhancing tiny tissues segmentation via self-distillation|[PDF](https://ieeexplore.ieee.org/abstract/document/9313542)|-|
|Learning tubule-sensitive CNNs for pulmonary airway and artery-vein segmentation in CT|[PDF](https://ieeexplore.ieee.org/abstract/document/9363945)|[Code](http://www.pami.sjtu.edu.cn/News/56)|
|Towards efficient medical image segmentation via boundary-guided knowledge distillation|[PDF](https://ieeexplore.ieee.org/abstract/document/9428395)|-|
|Difficulty-Aware Brain Lesion Segmentation from MRI Scans|[PDF](https://link.springer.com/article/10.1007/s11063-021-10714-4)|-|
|GID: Global information distillation for medical semantic segmentation|[PDF](https://www.sciencedirect.com/science/article/abs/pii/S0925231222007950)|-|
|Efficient Multi-Organ Segmentation from 3D Abdominal CT Images with Lightweight Network and Knowledge Distillation|[PDF](https://ieeexplore.ieee.org/abstract/document/10083150)|[Code](https://github.com/HiLab-git/LCOVNet-and-KD)|
|Efficient medical image segmentation based on knowledge distillation|[PDF](https://ieeexplore.ieee.org/abstract/document/9491090)|-|
|Distill DSM: Computationally efficient method for segmentation of medical imaging volumes|[PDF](https://proceedings.mlr.press/v143/maheshwari21a/maheshwari21a.pdf)|-|
|SurgiNet: Pyramid attention aggregation and class-wise self-distillation for surgical instrument segmentation|[PDF](https://www.sciencedirect.com/science/article/abs/pii/S1361841521003558)|-|
|Low-memory CNNs enabling real-time ultrasound segmentation towards mobile deployment|[PDF](https://ieeexplore.ieee.org/abstract/document/8999615)|[Code](https://github.com/sagarvaze96/lightweight_unet)|
|Coco distillnet: a cross-layer correlation distillation network for pathological gastric cancer segmentation|[PDF](https://ieeexplore.ieee.org/abstract/document/9669551)|-|
|Deep semi-supervised segmentation with weight-averaged consistency targets|[PDF](https://link.springer.com/chapter/10.1007/978-3-030-00889-5_2)|-|
|Uncertainty-aware self-ensembling model for semi-supervised 3D left atrium segmentation|[PDF](https://link.springer.com/chapter/10.1007/978-3-030-32245-8_67)|[Code](https://github.com/yulequan/UA-MT)|
|Double-uncertainty weighted method for semi-supervised learning|[PDF](https://link.springer.com/chapter/10.1007/978-3-030-59710-8_53)|-|
|Local and global structure-aware entropy regularized mean teacher model for 3d left atrium segmentation|[PDF](https://link.springer.com/chapter/10.1007/978-3-030-59710-8_55)|-|
|Transformation-consistent self-ensembling model for semisupervised medical image segmentation|[PDF](https://ieeexplore.ieee.org/abstract/document/9104928)|-|
|3D graph-S 2 Net: shape-aware self-ensembling network for semi-supervised segmentation with bilateral graph convolution|[PDF](https://link.springer.com/chapter/10.1007/978-3-030-87196-3_39)|-|
|All-around real label supervision: Cyclic prototype consistency learning for semi-supervised medical image segmentation|[PDF](https://ieeexplore.ieee.org/abstract/document/9741294)|-|
|Bootstrapping semi-supervised medical image segmentation with anatomical-aware contrastive distillation|[PDF](https://link.springer.com/chapter/10.1007/978-3-031-34048-2_49)|-|
|Cross-mix monitoring for medical image segmentation with limited supervision|[PDF](https://ieeexplore.ieee.org/abstract/document/9721091)|-|
|Knowledge Distillation from Cross Teaching Teachers for Efficient Semi-supervised Abdominal Organ Segmentation in CT|[PDF](https://link.springer.com/chapter/10.1007/978-3-031-23911-3_10)|[Code](https://github.com/jwc-rad/MISLight)|
|Simcvd: Simple contrastive voxel-wise representation distillation for semi-supervised medical image segmentation|[PDF](https://ieeexplore.ieee.org/abstract/document/9740182)|-|
|Semi-Supervised Medical Image Segmentation With Voxel Stability and Reliability Constraints|[PDF](https://ieeexplore.ieee.org/abstract/document/10120761)|-|
|Weakly supervised segmentation of COVID19 infection with scribble annotation on CT images|[PDF](https://www.sciencedirect.com/science/article/pii/S0031320321005215)|-|
|PA-Seg: Learning from Point Annotations for 3D Medical Image Segmentation using Contextual Regularization and Cross Knowledge Distillation|[PDF](https://ieeexplore.ieee.org/abstract/document/10044712)|-|
|A noise-robust framework for automatic segmentation of COVID-19 pneumonia lesions from CT images|[PDF](https://ieeexplore.ieee.org/abstract/document/9109297)|-|
|Distilling effective supervision for robust medical image segmentation with noisy labels|[PDF](https://link.springer.com/chapter/10.1007/978-3-030-87193-2_63)|-|
|Study group learning: Improving retinal vessel segmentation trained with noisy labels|[PDF](https://link.springer.com/chapter/10.1007/978-3-030-87193-2_6)|[Code](https://github.com/SHI-Labs/SGL-Retinal-Vessel-Segmentation)|
|Anti-interference from noisy labels: Mean-teacher-assisted confident learning for medical image segmentation|[PDF](https://ieeexplore.ieee.org/abstract/document/9779756)|-|
|Segmentation with mixed supervision: Confidence maximization helps knowledge distillation|[PDF](https://www.sciencedirect.com/science/article/abs/pii/S1361841522002985)|[Code](https://github.com/by-liu/ConfKD)|
|Teacher-student approach for lung tumor segmentation from mixed-supervised datasets|[PDF](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0266147)|-|
|A teacher-student framework for liver and tumor segmentation under mixed supervision from abdominal CT scans|[PDF](https://link.springer.com/article/10.1007/s00521-022-07240-2)|-|
|CFEA: Collaborative feature ensembling adaptation for domain adaptation in unsupervised optic disc and cup segmentation|[PDF](https://link.springer.com/chapter/10.1007/978-3-030-32254-0_58)|-|
|Privileged modality distillation for vessel border detection in intracoronary imaging|[PDF](https://ieeexplore.ieee.org/abstract/document/8896024)|-|
|Dual-teacher: Integrating intra-domain and inter-domain teachers for annotation-efficient cardiac segmentation|[PDF](https://link.springer.com/chapter/10.1007/978-3-030-59710-8_41)|-|
|Student Becomes Decathlon Master in Retinal Vessel Segmentation via Dual-Teacher Multi-target Domain Adaptation|[PDF](https://link.springer.com/chapter/10.1007/978-3-031-21014-3_4)|-|
|A Structure-aware Framework of Unsupervised Cross-Modality Domain Adaptation via Frequency and Spatial Knowledge Distillation|[PDF](https://ieeexplore.ieee.org/abstract/document/10261458)|[Code](https://github.com/slliuEric/FSUDA)|
|Mt-uda: Towards unsupervised cross-modality medical image segmentation with limited source labels|[PDF](https://link.springer.com/chapter/10.1007/978-3-030-87193-2_28)|-|
|Had-net: A hierarchical adversarial knowledge distillation network for improved enhanced tumour segmentation without post-contrast images|[PDF](https://proceedings.mlr.press/v143/vadacchino21a.html)|[Code](https://github.com/SaverioVad/HAD_Net)|
|Learning with privileged multimodal knowledge for unimodal segmentation|[PDF](https://ieeexplore.ieee.org/abstract/document/9567675)|-|
|A Single Stage Knowledge Distillation Network for Brain Tumor Segmentation on Limited MR Image Modalities|[PDF](https://www.sciencedirect.com/science/article/abs/pii/S0169260723003097)|-|
|D 2-Net: Dual disentanglement network for brain tumor segmentation with missing modalities|[PDF](https://ieeexplore.ieee.org/abstract/document/9775681)|[Code](https://github.com/CityU-AIM-Group/D2Net)|
|M3AE: Multimodal Representation Learning for Brain Tumor Segmentation with Missing Modalities|[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/25253)|[Code](https://github.com/ccarliu/m3ae)|
|Modality-Agnostic Learning for Medical Image Segmentation Using Multi-modality Self-distillation|[PDF](https://arxiv.org/abs/2306.03730)|-|



## KD in Medical image detection

|Paper|PDF|Code|
|---|---|---|
|Classification and localization consistency regularized student-teacher network for semi-supervised cervical cell detection|[PDF](https://ieeexplore.ieee.org/abstract/document/9474764)|-|
|Detection and recognition of ultrasound breast nodules based on semi-supervised deep learning: a powerful alternative strategy|[PDF](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8107344/)|-|
|Knowledge distillation with adaptive asymmetric label sharpening for semi-supervised fracture detection in chest x-rays|[PDF](https://link.springer.com/chapter/10.1007/978-3-030-78191-0_46)|-|
|SSMD: Semi-Supervised medical image detection with adaptive consistency and heterogeneous perturbation|[PDF](https://www.sciencedirect.com/science/article/abs/pii/S1361841521001638)|-|
|A semi-supervised Teacher-Student framework for surgical tool detection and localization|[PDF](https://www.tandfonline.com/doi/full/10.1080/21681163.2022.2150688)|-|
|A source-free domain adaptive polyp detection framework with style diversification flow|[PDF](https://ieeexplore.ieee.org/abstract/document/9709278)|[Code](https://github.com/CityU-AIM-Group/SFPolypDA)|
|Weakly Supervised Lesion Detection and Diagnosis for Breast Cancers with Partially Annotated Ultrasound Images|[PDF](https://ieeexplore.ieee.org/abstract/document/10439278)|-|
|Attention distillation for detection transformers: application to real-time video object detection in ultrasound|[PDF](https://proceedings.mlr.press/v158/rubin21a.htm)|-|
|Automated detection of cerebral microbleeds on MR images using knowledge distillation framework|[PDF](https://www.frontiersin.org/journals/neuroinformatics/articles/10.3389/fninf.2023.1204186/full)|-|
|Oxnet: Deep omni-supervised thoracic disease detection from chest x-rays|[PDF](https://link.springer.com/chapter/10.1007/978-3-030-87196-3_50)|[Code](https://github.com/LLYXC/OXnet)|
|Anatomical Landmark Detection Using a Feature-Sharing Knowledge Distillation-Based Neural Network|[PDF](https://www.mdpi.com/2079-9292/11/15/2337)|-|
|Knowledge distillation with a class-aware loss for endoscopic disease detection|[PDF](https://link.springer.com/chapter/10.1007/978-3-031-17979-2_7)|-|



## KD in Medical image reconstruction

|Paper|PDF|Code|
|---|---|---|
|Deep neural networks for low-dose CT image reconstruction via cooperative meta-learning strategy|[PDF](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/11312/1131243/Deep-neural-networks-for-low-dose-CT-image-reconstruction-via/10.1117/12.2548950.short#_=_)|-|
|Semi-supervised learning via improved teacher-student network for robust 3d reconstruction of stereo endoscopic image|[PDF](https://dl.acm.org/doi/abs/10.1145/3474085.3475527)|-|
|Semi-supervised Distillation Learning Based on Swin Transformer for MRI Reconstruction|[PDF](https://link.springer.com/chapter/10.1007/978-3-031-18910-4_6)|-|
|KD-MRI: A knowledge distillation framework for image reconstruction and image restoration in MRI workflow|[PDF](https://proceedings.mlr.press/v121/murugesan20a.html)|-|
|SFT-KD-Recon: Learning a Student-friendly Teacher for Knowledge Distillation in Magnetic Resonance Image Reconstruction|[PDF](https://proceedings.mlr.press/v227/matcha24a.html)|-|
|Realistic medical image super-resolution with pyramidal feature multi-distillation networks for intelligent healthcare systems|[PDF](https://link.springer.com/article/10.1007/s00521-021-06287-x)|-|
|Universal undersampled mri reconstruction|[PDF](https://link.springer.com/chapter/10.1007/978-3-030-87231-1_21)|-|
|Total-body low-dose CT image denoising using a prior knowledge transfer technique with a contrastive regularization mechanism|[PDF](https://aapm.onlinelibrary.wiley.com/doi/abs/10.1002/mp.16163)|-|


## KD in Medical image registration

|Paper|PDF|Code|
|---|---|---|
|Light-weight deformable registration using adversarial learning with distilling knowledge|[PDF](https://ieeexplore.ieee.org/abstract/document/9672098)|[Code](https://github.com/aioz-ai/LDR_ALDK)|
|Cross-resolution distillation for efficient 3D medical image registration|[PDF](https://ieeexplore.ieee.org/abstract/document/9782430)|-|
|Adapting the Mean Teacher for keypoint-based lung registration under geometric domain shifts|[PDF](https://link.springer.com/chapter/10.1007/978-3-031-16446-0_27)|[Code](https://github.com/multimodallearning/registration-da-mean-teacher)|
|Joint few-shot registration and segmentation self-training of 3D medical images|[PDF](https://www.sciencedirect.com/science/article/abs/pii/S1746809422007480)|-|
|Self-Distilled Hierarchical Network for Unsupervised Deformable Image Registration|[PDF](https://ieeexplore.ieee.org/abstract/document/10042453)|[Code](https://github.com/Blcony/SDHNet)|

## KD in Radiology report generation and VQA

|Paper|PDF|Code|
|---|---|---|
|An inclusive task-aware framework for radiology report generation|[PDF](https://link.springer.com/chapter/10.1007/978-3-031-16452-1_54)|[Code](https://github.com/Reremee/ITA)|
|KiUT: Knowledge-injected U-Transformer for Radiology Report Generation|[PDF](https://openaccess.thecvf.com/content/CVPR2023/html/Huang_KiUT_Knowledge-Injected_U-Transformer_for_Radiology_Report_Generation_CVPR_2023_paper.html)|-|
|Bridging the Gap: Cross-modal Knowledge Driven Network for Radiology Report Generation|[PDF](https://ieeexplore.ieee.org/abstract/document/10385967)|-|
|Exploring and distilling posterior and prior knowledge for radiology report generation|[PDF](https://openaccess.thecvf.com/content/CVPR2021/html/Liu_Exploring_and_Distilling_Posterior_and_Prior_Knowledge_for_Radiology_Report_CVPR_2021_paper.html)|-|
|Improving chest X-ray report generation by leveraging warm starting|[PDF](https://www.sciencedirect.com/science/article/pii/S0933365723001471)|[Code](https://github.com/aehrc/cvt2distilgpt2)|
|Contrastive pre-training and representation distillation for medical visual question answering based on radiology images|[PDF](https://link.springer.com/chapter/10.1007/978-3-030-87196-3_20)|[Code](https://github.com/awenbocc/cprd)|
|MHKD-MVQA: Multimodal Hierarchical Knowledge Distillation for Medical Visual Question Answering|[PDF](https://ieeexplore.ieee.org/abstract/document/9995473)|-|





## KD in Medical image privacy protection

|Paper|PDF|Code|
|---|---|---|
|Ensemble attention distillation for privacy-preserving federated learning|[PDF](https://openaccess.thecvf.com/content/ICCV2021/html/Gong_Ensemble_Attention_Distillation_for_Privacy-Preserving_Federated_Learning_ICCV_2021_paper.html)|-|
|Medisecfed: Private and secure medical image classification in the presence of malicious clients|[PDF](https://ieeexplore.ieee.org/abstract/document/9664357)|-|
|Cyclic Federated Learning Method Based on Distribution Information Sharing and Knowledge Distillation for Medical Data|[PDF](https://www.mdpi.com/2079-9292/11/23/4039)|-|
|Federated learning with privacy-preserving ensemble attention distillation|[PDF](https://ieeexplore.ieee.org/abstract/document/9915468)|-|
|Preserving privacy in federated learning with ensemble cross-domain knowledge distillation|[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/21446)|-|
|FedTD: Efficiently Share Telemedicine Data with Federated Distillation Learning|[PDF](https://link.springer.com/chapter/10.1007/978-3-031-20096-0_37)|-|
|Medical Image Segmentation Based on Federated Distillation Optimization Learning on Non-IID Data|[PDF](https://link.springer.com/chapter/10.1007/978-981-99-4749-2_30)|-|
|Compressed gastric image generation based on soft-label dataset distillation for medical data sharing|[PDF](https://www.sciencedirect.com/science/article/abs/pii/S0169260722005703)|-|
|SEDA: Self-ensembling ViT with Defensive Distillation and Adversarial Training for Robust Chest X-Rays Classification|[PDF](https://link.springer.com/chapter/10.1007/978-3-031-45857-6_13)|[Code](https://github.com/Razaimam45/SEDA)|









