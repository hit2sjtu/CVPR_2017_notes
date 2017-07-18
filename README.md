# CVPR 2017 notes (on-going)

This is my personal notes and focuses on several aspects as listed below.  

1. Feature detection and matching  
2. Geometry computer vision (and deep learning)   
3. Object detection and recognition  
4. Object tracking   
5. Face and human analysis  
6. Computation photography  
7. SLAM  
8. Real-time application of computer vision

Topics **not included** here but I am also interested with:  
  
1. Image captioning  
2. Visual question answering  
3. Vision & Sports
4. Edge detection & semantic segmentation
5. Video / temporal analysis

**If you want to see all CVPR 2017 papers, please refer to the CVF open access of all CVPR 2017 papers:   
* [Main Conference Papers](http://openaccess.thecvf.com/CVPR2017.py)  
* [Workshop Papers](http://openaccess.thecvf.com/CVPR2017_workshops/menu.py)**  

## Papers by topics
### 3D vision and Deep learning
* **Convolutional Neural Network Architecture for Geometric Matching**. **INRIA**.
Ignacio Rocco, Relja ArandjeloviÄ‡, Josef Sivic  
[Paper](https://arxiv.org/abs/1703.05593)

* Inverse Compositional Spatial Transformer Networks.
Chen-Hsuan Lin, Simon Lucey. [Paper](https://arxiv.org/abs/1612.03897)

*  Geometric Loss Functions for Camera Pose Regression with Deep Learning.
Alex Kendall, Roberto Cipolla. [Paper](https://arxiv.org/abs/1704.00390)

* Multi-Scale Continuous CRFs as Sequential Deep Networks
for Monocular Depth Estimation. [Paper](https://arxiv.org/abs/1704.02157)

* FCSS: Fully Convolutional Self-Similarity for Dense Semantic Correspondence, Seungryong Kim, Dongbo Min, 
Bumsub Ham, Sangryul Jeon, Stephen Lin, Kwanghoon Sohn 

*End-To-End Training of Hybrid CNN-CRF Models for Stereo.  Patrick Knobelreiter, Christian Reinbacher, Alexander Shekhovtsov, Thomas Pock 

### Optical Flow
* FlowNet 2.0: Evolution of Optical Flow Estimation With Deep Networks
Eddy Ilg, Nikolaus Mayer, Tonmoy Saikia, Margret Keuper, Alexey Dosovitskiy, Thomas Brox [Paper](https://arxiv.org/pdf/1612.01925.pdf) [Code](https://github.com/lmb-freiburg/flownet2)  

* Slow Flow: Exploiting High-Speed Cameras for Accurate and Diverse Optical Flow Reference Data, Joel 
Janai, Fatma Güney, Jonas Wulff, Michael J. Black, Andreas Geiger

### 2D/3D feature detection and matching
* Comparative Evaluation of Hand-Crafted and Learned Local Features. Johannes L. Schönberger,Hans Hardmeier, Torsten Sattler, **Marc Pollefeys**   
[Paper](https://cvg.ethz.ch/research/local-feature-evaluation/schoenberger2017comparative.pdf) [Website](https://cvg.ethz.ch/research/local-feature-evaluation/)

* GMS: Grid-based Motion Statistics for Fast, Ultra-robust Feature Correspondence. JiaWang Bian, Daniel Lin, Yasuyuki Matsushita, Sai-Kit Yeung, Tan Dat Nguyen, **Ming-Ming Cheng**
[Website](http://mmcheng.net/gms/)  [Github](https://github.com/JiawangBian/GMS-Feature-Matcher) [Youtube](https://www.youtube.com/watch?v=tjMpgno6k5A)

* HPatches: A benchmark and evaluation of handcrafted and learned local descriptors, Vassileios Balntas*, Karel Lenc*, Andrea Vedaldi and **Krystian Mikolajczyk**. [Paper] (https://arxiv.org/pdf/1704.05939.pdf) [Github](https://github.com/hpatches/hpatches-benchmark)

* 3DMatch: Learning Local Geometric Descriptors From RGB-D Reconstructions. Andy Zeng, Shuran Song, Matthias Niessner, Matthew Fisher, Jianxiong Xiao, Thomas Funkhouser 

### SLAM
* CNN-SLAM: Real-time dense monocular SLAM with learned depth prediction [Paper](https://arxiv.org/pdf/1704.03489.pdf)

* NID-SLAM: Robust Monocular SLAM Using Normalised Information Distance.
Geoffrey Pascoe, Will Maddern, Michael Tanner, Pedro Piniés, Paul Newman. [Paper](www.robots.ox.ac.uk/~mobile/Papers/2017CVPR_pascoe.pdf)

* Cognitive Mapping and Planning for Visual Navigation. 
Saurabh Gupta, James Davidson, Sergey Levine, Rahul Sukthankar, Jitendra Malik [Paper](https://arxiv.org/abs/1702.03920) [Project](https://sites.google.com/view/cognitive-mapping-and-planning/) [Code](https://github.com/tensorflow/models/tree/master/cognitive_mapping_and_planning)

* Visual-Inertial-Semantic Scene Representation for 3D Object Detection
Jingming Dong, Xiaohan Fei, **Stefano Soatto**

* On-The-Fly Adaptation of Regression Forests for **Online Camera Relocalisation**
   Tommaso Cavallari, Stuart Golodetz, Nicholas A. Lord, Julien Valentin, Luigi Di Stefano, Philip H. S. Torr 

### 6 DOF Object detection & tracking
* PoseAgent: Budget-Constrained 6D Object Pose Estimation via Reinforcement Learning
**Alexander Krull**, Eric Brachmann, Sebastian Nowozin, Frank 

*  Global Hypothesis Generation for 6D Object Pose Estimation. Frank Michel, Alexander Kirillov, Eric Brachmann, Alexander Krull, Stefan Gumhold, Bogdan Savchynskyy, Carsten Rother. [Paper](https://arxiv.org/abs/1612.02287)

*  Real-Time 3D Model Tracking in Color and Depth on a Single CPU Core
Wadim Kehl, Federico Tombari, Slobodan Ilic, Nassir Navab

* BIND: Binary Integrated Net Descriptors for Texture-Less Object Recognition
Jacob Chan, Jimmy Addison Lee, Qian Kemao

* Real-Time 3D Model Tracking in Color and Depth on a Single CPU Core, Wadim Kehl, Federico Tombari, Slobodan 
Ilic, Nassir Navab 


### Object Detection
* LCDet: Low-Complexity Fully-Convolutional Neural Networks for Object Detection in Embedded Systems.  **Qualcomm & UCSD**  
[Paper](https://arxiv.org/abs/1705.05922)

* Accurate Single Stage Detector Using Recurrent Rolling Convolution. **SenseTime**  Jimmy Ren, Xiaohao Chen, Jianbo Liu, Wenxiu 
Sun, Jiahao Pang, Qiong Yan, Yu-Wing Tai, Li Xu   
[Website](https://github.com/xiaohaoChen/rrc_detection)  

* Feature Pyramid Networks for Object Detection. 
Tsung-Yi Lin, **Piotr Dollar, Ross Girshick, Kaiming He**, Bharath Hariharan, Serge Belongie

* Speed/Accuracy Trade-Offs for Modern Convolutional Object Detectors
Jonathan Huang, Vivek Rathod, Chen Sun, Menglong Zhu, Anoop Korattikara, Alireza Fathi, Ian Fischer, Zbigniew Wojna, Yang Song, Sergio Guadarrama, Kevin Murphy

* Amodal Detection of 3D Objects: Inferring 3D Bounding Boxes From 2D Ones in RGB-Depth Images. Zhuo Deng, 
Longin Jan Latecki 

* Object Detection in Videos With Tubelet Proposal Networks, Kai Kang, Hongsheng Li, Tong Xiao, Wanli 
Ouyang, Junjie Yan, Xihui Liu, Xiaogang Wang 

* Fast Boosting Based Detection Using Scale Invariant Multimodal Multiresolution Filtered Features, Arthur 
Daniel Costea, Robert Varga, Sergiu Nedevschi 

*  Perceptual Generative Adversarial Networks for Small Object Detection, Jianan Li, Xiaodan Liang, Yunchao Wei, 
Tingfa Xu, Jiashi Feng, Shuicheng Yan 

### Transfer Learning & Domain Adaptation
* Borrowing Treasures From the Wealthy: Deep Transfer Learning Through Selective Joint Fine-Tuning. Weifeng Ge, Yizhou Yu . [Paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Ge_Borrowing_Treasures_From_CVPR_2017_paper.pdf)

* Fine-Grained Recognition of Thousands of Object Categories With Single-Example Training, Leonid 
Karlinsky, Joseph Shtok, Yochay Tzur, Asaf Tzadok 

*  Matrix Tri-Factorization With Manifold Regularizations for Zero-Shot Learning, Xing Xu, Fumin Shen, Yang Yang, 
Dongxiang Zhang, Heng Tao Shen, Jingkuan Song
 
* Semantically Consistent Regularization for Zero-Shot Recognition, Pedro Morgado, Nuno Vasconcelos 

* Unified Embedding and Metric Learning for Zero-Exemplar Event Detection. Noureldien Hussein, Efstratios 
Gavves, Arnold W.M. Smeulders

### Computational Photography
* A Unified Approach of Multi-scale Deep and Hand-crafted Features for Defocus
Estimation. **KAIST & Tecent Youtu**
[Paper](https://arxiv.org/abs/1704.08992) [website]()

* Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network. Christian Ledig, Lucas Theis, Ferenc HuszÃƒÂ¡r, Jose Caballero, Andrew Cunningham, Alejandro Acosta, Andrew Aitken, Alykhan Tejani, Johannes Totz, Zehan Wang, Wenzhe Shi. [Paper](https://arxiv.org/pdf/1609.04802.pdf) [Code](https://github.com/leehomyc/Photo-Realistic-Super-Resoluton)  

### 3D Reconstruction
* Using Locally Corresponding CAD Models for Dense 3D Reconstructions from a Single Image. Chen Kong, Chen-Hsuan Lin, **Simon Lucey**. Carnegie Mellon University           
[Paper](ci2cv.net/media/papers/chenkong_cvpr_2017.pdf) [Github](https://github.com/kongchen1992/LDCgraph)

* Multi-View Supervision for **Single-View Reconstruction** via Differentiable Ray Consistency. Shubham Tulsiani, Tinghui Zhou, Alexei A. Efros, Jitendra  Malik 

* Transformation-Grounded Image Generation Network for Novel 3D View Synthesis, Eunbyung Park, Jimei Yang, Ersin 
Yumer, Duygu Ceylan, Alexander C. Berg 

* SurfNet: Generating 3D Shape Surfaces Using Deep Residual Networks, Ayan Sinha, Asim Unmesh, Qixing 
Huang, Karthik Ramani 

### RGBD Sensors / Stereo
* Intel RealSense Stereoscopic Depth Cameras.   **Intel**   
[Paper](https://arxiv.org/abs/1705.05548)

* Dynamic Time-Of-Flight. Michael Schober, Amit Adam, Omer Yair, Shai Mazor, Sebastian Nowozin


### DL model compression
* On Compressing Deep Models by Low Rank and Sparse Decomposition, Xiyu Yu, Tongliang Liu, Xinchao Wang, Dacheng Tao

* A Compact DNN: Approaching GoogLeNet-Level Accuracy of Classification and Domain Adaptation, Chunpeng Wu, Wei Wen, Tariq Afzal, Yongmei Zhang, Yiran Chen, Hai (Helen) Li
   
* LCNN: Lookup-Based Convolutional Neural Network, Hessam Bagherinezhad, Mohammad Rastegari, Ali Farhad

* Budget-Aware Deep Semantic Video Segmentation, Behrooz Mahasseni, Sinisa Todorovic, Alan Fern
 
### Sensor Calibration
*  A Practical Method for Fully **Automatic Intrinsic Camera Calibration** Using Directionally Encoded Light, 
Mahdi Abbaspour Tehrani, Thabo Beeler, Anselm Grundhöfer
*  Radiometric Calibration for Internet Photo Collections, Zhipeng Mo, Boxin Shi, Sai-Kit Yeung, Yasuyuki 
Matsushita 

### Image Retrieval
* Deep Visual-Semantic Quantization for Efficient Image Retrieval, Yue Cao, Mingsheng Long, Jianmin Wang, 
Shichen Liu
 
* AMVH: Asymmetric Multi-Valued Hashing. Cheng Da, Shibiao Xu, Kun Ding, Gaofeng Meng, Shiming Xiang, Chunhong Pan

* Efficient Diffusion on Region Manifolds: Recovering Small Objects With Compact CNN Representations, Ahmet 
Iscen, Giorgos Tolias, Yannis Avrithis, Teddy Furon, Ondřej Chum

* Spatial-Semantic Image Search by Visual Feature Synthesis, Long Mai, Hailin Jin, Zhe Lin, Chen Fang, 
Jonathan Brandt, Feng Liu
   
### Human Analysis
* LCR-Net: Localization-Classification-Regression for Human Pose. Gregory Rogez, Philippe Weinzaepfel, Cordelia Schmid 

* Deep Learning on Lie Groups for Skeleton-Based Action Recognition, Zhiwu Huang, Chengde Wan, Thomas 
Probst, Luc Van Gool 

* Coarse-To-Fine Volumetric Prediction for Single-Image 3D Human Pose, Georgios Pavlakos, Xiaowei Zhou, 
Konstantinos G. Derpanis, Kostas Daniilidis 

* ArtTrack: Articulated Multi-Person Tracking in the Wild, Eldar Insafutdinov, Mykhaylo Andriluka, Leonid 
Pishchulin, Siyu Tang, Evgeny Levinkov, Bjoern Andres, Bernt Schiele 

* Realtime Multi-Person 2D Pose Estimation Using Part Affinity Fields, Zhe Cao, Tomas Simon, Shih-En Wei, 
Yaser Sheikh 

* Weakly Supervised Action Learning With RNN Based Fine-To-Coarse Modeling, Alexander Richard, Hilde 
Kuehne, Juergen Gall 

### Face Analysis 
* Learning Residual Images for Face Attribute Manipulation, Wei Shen, Rujie Liu

* Disentangled Representation Learning GAN for Pose-Invariant Face Recognition, Luan Tran, Xi Yin, 
Xiaoming Liu 

### Object Tracking
* Context-Aware Correlation Filter Tracking, Matthias Mueller, Neil Smith, Bernard Ghanem

* Template Matching With Deformable Diversity Similarity, Itamar Talmi, Roey Mechrez, Lihi Zelnik-Mano


## Workshops

