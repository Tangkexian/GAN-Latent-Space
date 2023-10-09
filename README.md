# Awesome GAN- Latent-Space

If you have any problems, suggestions or improvements, please submit the issue or PR.

## Contents

- [GAN Models](#gan models)

* [Datasets](#datasets)
* [Papers](#papers)
  * [Survey](#survey)
  * [Grading](#grading)
  * [Segmentation](#segmentation)
  * [Multimodal](#multimodal)
  * [Enhancement](#enhancement)
* [Projects](#projects)

## GAN Models

| GAN Model     | Time |
| ------------- | ---- |
| DCGAN         |      |
| WGAN          |      |
| PGGAN         |      |
| BigGAN        |      |
| StyleGAN      |      |
| StyleGAN2     |      |
| StyleGAN2-Ada |      |
| StyleGAN3     |      |

## Datasets

| Dataset                   | Time     | Images |  Format   |  Camera  |  Resolution |
|---------------------------|----------|--------|-----------|----------|-------------|
| [ImageNet](https://github.com/chehx/DGDR/blob/main/GDRBench/README.md) | 2023 | 111,357 | / | / | / |
| [CelebA](https://github.com/FDU-VTS/DRTiD) | 2022 | 3100 | jpg | / | / |
| [Flickr-Faces-HQ (FFHQ) ](https://csyizhou.github.io/FGADR/) | 2021| 2842 | / | / | / |
| [LSUN](https://github.com/nkicsl/DDR-dataset) | 2019 | 13673 | jpg | Topcon, Nikon, Canon | / |
| [DeepFashion](https://isbi.deepdr.org/index.html) | 2019 | 2256 | jpg | TOPCON | 1956×1934 |
| [AnimeFaces](https://www.kaggle.com/c/diabetic-retinopathy-detection/) | 2015 | 88k | jpeg | / | / |
| [StreetScapes](http://www.adcis.net/en/third-party/messidor/) | 2014 | 1200 | tiff | Topcpn TRC NW6 | 1440x960,<br>2240x1488,<br>2304x1536 |

## Papers
<!-- 
- Unsupervised Visual Representation Learning by Context Prediction.
  [[pdf]](https://arxiv.org/abs/1505.05192)
  [[code]](http://graphics.cs.cmu.edu/projects/deepContext/)
  - Doersch, Carl and Gupta, Abhinav and Efros, Alexei A. *ICCV 2015*
  -->

### Survey

- GAN Inversion: A Survey
  [[pdf]](https://ieeexplore.ieee.org/abstract/document/9792208)
  - Weihao Xia , Yulun Zhang , Yujiu Yang , Jing-Hao Xue ,Bolei Zhou, and Ming-Hsuan Yang , Fellow, IEEE.
  -  *[IEEE Transactions on Pattern Analysis and Machine Intelligence](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=34) ( Volume: 45, [Issue: 3](https://ieeexplore.ieee.org/xpl/tocresult.jsp?isnumber=10036240&punumber=34), 01 March 2023)*


### Grading

**2023**

- A foundation model for generalizable disease detection from retinal images
  [[pdf]](https://www.nature.com/articles/s41586-023-06555-x)
  [[code]](https://github.com/rmaphoh/RETFound_MAE)
  - Yukun Zhou, Mark A. Chia, Siegfried K. Wagner, Murat S. Ayhan, Dominic J. Williamson, Robbert R. Struyven, Timing Liu, Moucheng Xu, Mateo G. Lozano, Peter Woodward-Court, Yuka Kihara, UK Biobank Eye & Vision Consortium, Andre Altmann, Aaron Y. Lee, Eric J. Topol, Alastair K. Denniston, Daniel C. Alexander & Pearse A. Keane. **Nature 2023**
  
- DRAC: Diabetic Retinopathy Analysis Challenge with Ultra-Wide Optical Coherence Tomography Angiography Images
  [[pdf]](https://arxiv.org/pdf/2304.02389.pdf)
  - Bo Qian, Hao Chen, Xiangning Wang, Haoxuan Che, Gitaek Kwon, Jaeyoung Kim, Sungjin Choi, Seoyoung Shin, Felix Krause, Markus Unterdechler, et al. *arxiv 2023*

- Image Quality-aware Diagnosis via Meta-knowledge Co-embedding
  [[pdf]](https://arxiv.org/abs/2303.15038)
  [[code]](https://github.com/chehx/MKCNet)
  - Haoxuan Che, Siyu Chen, Hao Chen. *CVPR 2023*

- Towards Generalizable Diabetic Retinopathy Grading in Unseen Domains
  [[pdf]](https://arxiv.org/abs/2307.04378)
  [[code]](https://github.com/chehx/DGDR)
  - Haoxuan Che, Yuhan Cheng, Haibo Jin, Hao Chen. *MICCAI 2023*

- Lesion-Aware Contrastive Learning for Diabetic Retinopathy Diagnosis
  [[pdf]](https://link.springer.com/chapter/10.1007/978-3-031-43990-2_63)
  [[code]](https://github.com/IntelliDAL/Image)
  - Shuai Cheng, Qingshan Hou, Peng Cao, Jinzhu Yang, Xiaoli Liu, Osmar R. Zaiane. *MICCAI 2023*

- Diabetic Retinopathy Grading with Weakly-Supervised Lesion Priors
  [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10095713)
  [[code]](https://github.com/FDU-VTS/LANet)
  - Junlin Hou, Fan Xiao, Jilan Xu, Rui Feng, Yuejie Zhang, Haidong Zou, Lina Lu, Wenwen Xue. *ICASSP 2023*

**2022**

- Cross-Field Transformer for Diabetic Retinopathy Grading on Two-field Fundus Images 
  [[pdf]](https://arxiv.org/pdf/2211.14552)
  [[code]](https://github.com/FDU-VTS/DRTiD)
  - Junlin Hou, Jilan Xu, Fan Xiao, Rui-Wei Zhao, Yuejie Zhang, Haidong Zou, Lina Lu, Wenwen Xue, Rui Feng. *BIBM 2022*
  
- Image Quality Assessment Guided Collaborative Learning of image enhancement and classification for Diabetic Retinopathy Grading
  [[pdf]](https://ieeexplore.ieee.org/abstract/document/9997504)
  - Qingshan Hou; Peng Cao; Liyu Jia; Leqi Chen; Jinzhu Yang; Osmar R. Zaiane. *JBHI 2022*

- Focused Attention in Transformers for interpretable classification of retinal images
  [[pdf]](https://www.sciencedirect.com/science/article/pii/S1361841522002377)
  [[code]](https://github.com/ClementPla/FocusedAttention)
  - Clément Playout, Renaud Duval, Marie Carole Boucher, Farida Cheriet. *MIA 2022*
  
- SatFormer: Saliency-Guided Abnormality-Aware Transformer for Retinal Disease Classification in Fundus Image
  [[pdf]](https://www.ijcai.org/proceedings/2022/0138.pdf)
  - Yankai Jiang, Ke Xu, Xinyue Wang, Yuan Li, Hongguang Cui, Yubo Tao, Hai Lin. *IJCAI 2022*

- SSiT: Saliency-guided Self-supervised Image Transformer for Diabetic Retinopathy Grading
  [[pdf]](https://arxiv.org/pdf/2210.10969.pdf)
  [[code]](https://github.com/YijinHuang/SSiT)
  - Yijin Huang, Junyan Lyu, Pujin Cheng, Roger Tam, Xiaoying Tang. *arXiv preprint 2022.10.20*

- Uni4Eye: Unified 2D and 3D Self-supervised Pre-training via Masked Image Modeling Transformer for Ophthalmic Image Classification
  [[pdf]](https://arxiv.org/abs/2203.04614)
  - Zhiyuan Cai, Li Lin, Huaqing He, Xiaoying Tang. *MICCAI 2022*

- DRGen: Domain Generalization in Diabetic Retinopathy Classification
  [[pdf]](https://link.springer.com/chapter/10.1007/978-3-031-16434-7_61)
  - Mohammad Atwany, Mohammad Yaqub. *MICCAI 2022*

- Learning Robust Representation for Joint Grading of Ophthalmic Diseases via Adaptive Curriculum and Feature Disentanglement
  [[pdf]](https://arxiv.org/abs/2207.04183)
  - Haoxuan Che, Haibo Jin, Hao Chen. *MICCAI 2022*

- Deep-OCTA: Ensemble Deep Learning Approaches for Diabetic Retinopathy Analysis on OCTA Images
  [[pdf]](https://arxiv.org/pdf/2210.00515.pdf)
  [[code]](https://github.com/FDU-VTS/DRAC)
  - Junlin Hou, Fan Xiao, Jilan Xu, Yuejie Zhang, Haidong Zou, Rui Feng. *MICCAI Challenge 2022*
    

**2021**

- Rotation-oriented Collaborative Self-supervised Learning for Retinal Disease Diagnosis
  [[pdf]](https://ieeexplore.ieee.org/document/9411868)
  [[code]](https://github.com/xmengli/Rotation-oriented-self-supervised)
  - Xiaomeng Li, Xiaowei Hu, Xiaojuan Qi, Lequan Yu, Wei Zhao, Pheng-Ann Heng, Lei Xing. *TMI 2021*

- MVDRNet: Multi-view diabetic retinopathy detection by combining DCNNs and attention mechanisms
  [[pdf]](https://www.sciencedirect.com/science/article/pii/S0031320321002910)
  - Xiaoling Luo, Zuhui Pu, Yong Xu, Wai Keung Wong, Jingyong Su, Xiaoyan Dou, Baikang Ye, Jiying Hu, Lisha Mou. *PR 2021*

- MIL-VT: Multiple Instance Learning Enhanced Vision Transformer for Fundus Image Classification
  [[pdf]](https://link.springer.com/chapter/10.1007/978-3-030-87237-3_5)
  [[code]](https://github.com/greentreeys/MIL-VT)
  - Shuang Yu, Kai Ma, Qi Bi, Cheng Bian, Munan Ning, Nanjun He, Yuexiang Li, Hanruo Liu, Yefeng Zheng. *MICCAI 2021*
  
- Lesion-Based Contrastive Learning for Diabetic Retinopathy Grading from Fundus Images
  [[pdf]](https://arxiv.org/abs/2107.08274)
  [[code]](https://github.com/YijinHuang/Lesion-based-Contrastive-Learning)
  - Yijin Huang, Li Lin, Pujin Cheng, Junyan Lyu, Xiaoying Tang. *MICCAI 2021*
  
- Lesion-aware transformers for diabetic retinopathy grading
  [[pdf]](https://openaccess.thecvf.com/content/CVPR2021/html/Sun_Lesion-Aware_Transformers_for_Diabetic_Retinopathy_Grading_CVPR_2021_paper.html)
  - Rui Sun, Yihao Li, Tianzhu Zhang, Zhendong Mao, Feng Wu, Yongdong Zhang. *CVPR 2021*

- Deep Multi-Task Learning for Diabetic Retinopathy Grading in Fundus Images
  [[pdf]](https://ojs.aaai.org/index.php/AAAI/article/view/16388)
  - Xiaofei Wang, Mai Xu, Jicong Zhang, Lai Jiang, Liu Li. *AAAI 2021*
  
- A deep learning system for detecting diabetic retinopathy across the disease spectrum
  [[pdf]](https://www.nature.com/articles/s41467-021-23458-5?utm_source=other&utm_medium=other&utm_content=null)
  [[code]](https://zenodo.org/badge/latestdoi/334570111)
  - Ling Dai, Liang Wu, Huating Li, Chun Cai, Qiang Wu, et al. *Nature Communication 2021*

**2020**

- Self-Supervised Feature Learning via Exploiting Multi-Modal Data for Retinal Disease Diagnosis
  [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9139411)
  [[code]](https://github.com/xmengli/self_supervised)
  - Xiaomeng Li, Mengyu Jia, Md Tauhidul Islam, Lequan Yu, and Lei Xing *TMI 2020*
  
- Multi-Task Learning for Diabetic Retinopathy Grading and Lesion Segmentation
  [[pdf]](https://www.researchgate.net/publication/342540041_Multi-Task_Learning_for_Diabetic_Retinopathy_Grading_and_Lesion_Segmentation)
  - Alex Foo, Wynne Hsu, Mong Li Lee, Gilbert Lim, Tien Yin Wong. *IAAI 2020*

- A Benchmark for Studying Diabetic Retinopathy: Segmentation, Grading, and Transferability
  [[pdf]](https://arxiv.org/pdf/2008.09772.pdf)
  [[code]](https://csyizhou.github.io/FGADR/)
  - Yi Zhou, Boyang Wang, Lei Huang, Shanshan Cui, Ling Shao. *TMI 2020*

- CABNet: Category Attention Block for Imbalanced Diabetic Retinopathy Grading
  [[pdf]](https://ieeexplore.ieee.org/document/9195035/)
  [[code]](https://github.com/he2016012996/CABnet)
  - Along He, Tao Li , Ning Li, Kai Wang, and Huazhu Fu. *TMI 2020*
  
- SUNET: A LESION REGULARIZED MODEL FOR SIMULTANEOUS DIABETIC RETINOPATHY AND DIABETIC MACULAR EDEMA GRADING
  [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9098673)
  - Zhi Tu, Shenghua Gao, Kang Zhou, Xianing Chen, Jiang Liu. *ISBI 2020* 
  

**2019**

- Collaborative learning of semi-supervised segmentation and classification for medical images
  [[pdf]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Zhou_Collaborative_Learning_of_Semi-Supervised_Segmentation_and_Classification_for_Medical_Images_CVPR_2019_paper.pdf)
  - Yi Zhou, Xiaodong He, Lei Huang. *CVPR 2019*
  
- CANet: Cross-disease Attention Network for Joint Diabetic Retinopathy and Diabetic Macular Edema Grading
  [[pdf]](https://arxiv.org/abs/1911.01376)
  [[code]](https://github.com/xmengli999/CANet)
  - Xiaomeng Li, Xiaowei Hu, Lequan Yu. *TMI 2019*

- BIRA-NET: BILINEAR ATTENTION NET FOR DIABETIC RETINOPATHY GRADING
  [[pdf]](https://arxiv.org/pdf/1905.06312.pdf)
  - Ziyuan Zhao, Kerui Zhang, Xuejie Hao, Jing Tian. *ICIP 2019*
  

**2018**

- Zoom-in-Net: Deep Mining Lesions for Diabetic Retinopathy Detection
  [[pdf]](https://arxiv.org/abs/1706.04372)
  - Zhe Wang, Yanxin Yin, Jianping Shi. *MICCAI 2018*
  
- A Framework for Identifying Diabetic Retinopathy Based on Anti-noise Detection and Attention-Based Fusion
  [[pdf]](https://link.springer.com/chapter/10.1007/978-3-030-00934-2_9)
  - Zhiwen Lin, Ruoqian Guo, Yanjie Wang. *MICCAI 2018*

- Grader Variability and the Importance of Reference Standards for Evaluating Machine Learning Models for Diabetic Retinopathy
  [[pdf]](https://www.aaojournal.org/article/S0161-6420(17)32698-2/fulltext)
  - Jonathan Krause, Varun Gulshan, Ehsan Rahimy. *Ophthalmology 2018*

- Using a Deep Learning Algorithm and Integrated Gradients Explanation to Assist Grading for Diabetic Retinopathy
  [[pdf]](https://www.aaojournal.org/article/S0161-6420(18)31575-6/fulltext)
  - Rory Sayres, Ankur Taly, Ehsan Rahimy. *Ophthalmology 2018*

**2016**

- Development and Validation of a Deep Learning Algorithm for Detection of Diabetic Retinopathy in Retinal Fundus Photographs 
  [[pdf]](https://jamanetwork.com/journals/jama/fullarticle/2588763)
  - Varun Gulshan, Lily Peng, Marc Coram. *JAMA 2016*


### Segmentation

**2022**

- Progressive Multiscale Consistent Network for Multiclass Fundus Lesion Segmentation
  [[pdf]](https://ieeexplore.ieee.org/abstract/document/9781413)
  - Along He, Kai Wang, Tao Li, Wang Bo, Hong Kang, Huazhu Fu. *TMI 2022*
  
- RTNet: Relation transformer network for diabetic retinopathy multi-lesion segmentation
  [[pdf]](https://ieeexplore.ieee.org/abstract/document/9684442)
  - Shiqi Huang, Jianan Li, Yuze Xiao, Ning Shen, Tingfa Xu. *TMI 2022*
  
- SAA: Scale-Aware Attention Block For Multi-Lesion Segmentation Of Fundus Images
  [[pdf]](https://ieeexplore.ieee.org/abstract/document/9761529)
  - Wang Bo, Tao Li, Xinhui Liu, Kai Wang. *ISBI 2022*

**2020**

- LESION-AWARE SEGMENTATION NETWORK FOR ATROPHY AND DETACHMENT OF PATHOLOGICAL MYOPIA ON FUNDUS IMAGES
  [[pdf]](https://ieeexplore.ieee.org/document/9098669)
  - Yan Guo, Rui Wang, Xia Zhou, Yang Liu, Lilong Wang. *ISBI 2020*
  

**2019**

- DoFE: Domain-oriented Feature Embedding for Generalizable Fundus Image Segmentation on Unseen Datasets
  [[pdf]](https://ieeexplore.ieee.org/document/9098673)
  - Shujun Wang，Lequan Yu，Kang Li，Xin Yang，Pheng-Ann Heng. *TMI 2019*

- CE-Net: Context Encoder Network for 2D Medical Image Segmentation
  [[pdf]](https://arxiv.org/pdf/1903.02740.pdf)
  - Zaiwang Gu, Jun Cheng, Huazhu Fu, Kang Zhou, Huaying Hao, Yitian Zhao, Tianyang Zhang, Shenghua Gao and Jiang Liu. *TMI2019*
  
- Patch-based Output Space Adversarial Learning for Joint Optic Disc and Cup Segmentation
  [[pdf]](https://ieeexplore.ieee.org/document/9098673)
  - Shujun Wang, Lequan Yu, Xin Yang, Chi-Wing Fu, Pheng-Ann Heng. *TMI 2019*

- Boundary and Entropy-driven Adversarial Learning for Fundus Image Segmentation
  [[pdf]](https://pubmed.ncbi.nlm.nih.gov/30871687/)
  - Shujun Wang1, Lequan Yu, Kang Li, Xin Yang, Chi-Wing Fu1, Pheng-Ann Heng. *MICCAI 2019*

- Attention Guided Network for Retinal Image Segmentation
  [[pdf]](https://arxiv.org/pdf/1907.12930.pdf)
  - Zhang, Shihao，Fu, Huazhu，Yan, Yuguang，Zhang, Yubing，Wu, Qingyao，Yang, Ming，Tan, Mingkui，Xu, Yanwu. *MICCAI 2019*

- L-Seg: An end-to-end unified framework for multi-lesion segmentation of fundus images
  [[pdf]](https://www.sciencedirect.com/science/article/pii/S0925231219305430)
  [[code]](https://github.com/guomugong/L-Seg)
  - SongGuo, TaoLi, HongKang, NingLi, YujunZhang, KaiWang. *Neurocomputing 2019*

- Joint segmentation and classification of retinal arteries/veins from fundus images
  [[pdf]](https://pubmed.ncbi.nlm.nih.gov/30871687/)
  - Fantin Girard, Conrad Kavalec, Farida Cheriet. *artmed 2019*
  
- A coarse-to-fine deep learning framework for optic disc segmentationin fundus images
  [[pdf]](https://www.sciencedirect.com/science/article/pii/S1746809419300229?via%3Dihub)
  - Wang, Lei，Liu, Han，Lu, Yaling，Chen, Hang，Zhang, Jian，Pu, Jiantao. *BSPC 2019*
  

**2017**

- Joint Optic Disc and Cup Segmentation Based on Multi-label Deep Network and Polar Transformation
  [[pdf]](https://arxiv.org/pdf/1801.00926.pdf)
  - Huazhu Fu, Jun Cheng, Yanwu Xu, Damon Wing Kee Wong, Jiang Liu, and Xiaochun Cao. *TMI 2017*



### Multimodal 
**CF & OCT B-scan**

- Multi-Modal Multi-Instance Learning for Retinal Disease Recognition
  [[pdf]](https://arxiv.org/abs/2109.12307)
  - Xirong Li, Yang Zhou, Jie Wang, Hailan Lin, Jianchun Zhao, Dayong Ding, Weihong Yu, Youxin Chen. *ACM MM 2021*
  
- Multi-Modal Retinal Image Classification With Modality-Specific Attention Network
  [[pdf]](https://ieeexplore.ieee.org/abstract/document/9363019/)
  - Xingxin He, Ying Deng, Leyang Fang, Qinghua Peng. *TMI 2021*
  
- Two-Stream CNN with Loose Pair Training for Multi-modal AMD Categorization
  [[pdf]](https://arxiv.org/pdf/1907.12023.pdf)
  - Weisen Wang, Zhiyan Xu, Weihong Yu, Jianchun Zhao, Jingyuan Yang, Feng He, Zhikun Yang, Di Chen, Dayong Ding, Youxin Chen, Xirong Li. *MICCAI 2019*

 

### Enhancement

**2023**

- OTRE: Where Optimal Transport Guided Unpaired Image-to-Image Translation Meets Regularization by Enhancing
  [[pdf]](https://arxiv.org/abs/2302.03003)
  [[code]](https://github.com/Retinal-Research/OTRE)

  - Wenhui Zhu, Peijie Qiu, Oana M. Dumitrascu, Jacob M. Sobczak, Mohammad Farazi, Zhangsihao Yang, Keshav Nandakumar, Yalin Wang. *IPMI. 2023*

- Optimal Transport Guided Unsupervised Learning for Enhancing low-quality Retinal Images
  [[pdf]](https://arxiv.org/abs/2302.02991)
  [[code]](https://github.com/retinal-research/ote-gan)

  - Wenhui Zhu, Peijie Qiu, Mohammad Farazi, Keshav Nandakumar, Oana M. Dumitrascu, Yalin Wang. *IEEE ISBI 2023*

- Bridging Synthetic and Real Images: a Transferable and Multiple Consistency aided Fundus Image Enhancement Framework
  [[pdf]](https://ieeexplore.ieee.org/abstract/document/10049997/)
  
  - Erjian Guo, Huazhu Fu, Luping Zhou, Dong Xu. *TMI 2023*
  
- Learning Enhancement From Degradation: A Diffusion Model For Fundus Image Enhancement
  [[pdf]](https://arxiv.org/abs/2303.04603)
  [[code]](https://github.com/QtacierP/LED)
  
  - Puijin Cheng, Li Lin, Yijin Huang, Huaqing He, Wenhan Luo, Xiaoying Tang.
  
- Self-supervised Domain Adaptation for Breaking the Limits of Low-quality Fundus Image Quality Enhancement
  [[pdf]](https://arxiv.org/abs/2301.06943)
  
  - Qingshan Hou, Peng Cao, Jiaqi Wang, Xiaoli Liu, Jinzhu Yang, Osmar R. Zaiane.

**2022**

- Image Quality Assessment Guided Collaborative Learning of Image Enhancement and Classification for Diabetic Retinopathy Grading
  [[pdf]](https://ieeexplore.ieee.org/abstract/document/9997504)
  - Qingshan Hou, Peng Cao, Liyu Jia, Leqi Chen, Jinzhu Yang, Osmar R. Zaiane. *JBHI 2022*
  
- Degradation-invariant Enhancement of Fundus Images via Pyramid Constraint Network
  [[pdf]](https://link.springer.com/chapter/10.1007/978-3-031-16434-7_49)
  [[code]](https://github.com/HeverLaw/PCENet-Image-Enhancement)
  - Haofeng Liu, Heng Li, Huazhu Fu, Ruoxiu Xiao, Yunshu Gao, Yan Hu, Jiang Liu. *MICCAI 2022*
  
- Structure-Consistent Restoration Network for Cataract Fundus Image Enhancement
  [[pdf]](https://link.springer.com/chapter/10.1007/978-3-031-16434-7_47)
  [[code]](https://github.com/liamheng/ArcNet-Medical-Image-Enhancement)
  - Heng Li, Haofeng Liu, Huazhu Fu, Hai Shu, Yitian Zhao, Xiaoling Luo, Yan Hu, Jiang Liu. *MICCAI 2022*
  
- DOMAIN GENERALIZATION IN RESTORATION OF CATARACT FUNDUS IMAGES VIA HIGH-FREQUENCY COMPONENTS
  [[pdf]](https://ieeexplore.ieee.org/abstract/document/9761606/)
  [[code]](https://github.com/HeverLaw/Restoration-of-Cataract-Images-via-Domain-Generalization)
  - Haofeng Liu, Heng Li, Mingyang Ou, Yitian Zhao, Hong Qi, Yan Hu, Jiang Liu. *ISBI 2022*

- An Annotation-Free Restoration Network for Cataractous Fundus Images
  [[pdf]](https://ieeexplore.ieee.org/abstract/document/9698071/)
  [[code]](https://github.com/liamheng/Annotation-free-Fundus-Image-Enhancement)
  - Heng Li, Haofeng Liu, Yan Hu, Huazhu Fu, Yitian Zhao, Hanpei Miao, Jiang Liu. *TMI 2022*

**2021**
- I-SECRET: Importance-Guided Fundus Image Enhancement via Semi-supervised Contrastive Constraining
  [[pdf]](https://link.springer.com/chapter/10.1007/978-3-030-87237-3_9)
  [[code]](https://github.com/QtacierP/ISECRET)
  - Pujin Cheng, Li Lin, Yijin Huang, Junyan Lyu, Xiaoying Tang. *MICCAI 2021*
  

## Projects

- [[EyePACS](https://github.com/YijinHuang/pytorch-classification)] Identifying the key components in ResNet-50 for diabetic retinopathy grading from fundus images: a systematic investigation

- [[Team o_O](https://github.com/sveitser/kaggle_diabetic)] Team o_O solution for the Kaggle Diabetic Retinopathy Detection Challenge

- [[EyeNet](https://github.com/gregwchase/eyenet)] Identifying diabetic retinopathy using convolutional neural networks

