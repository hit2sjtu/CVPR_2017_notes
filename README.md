# CVPR 2017 notes (on-going)

This is my personal notes and **focuses on** several aspects as listed below.  

1. Feature detection and matching  
2. Geometry computer vision (and deep learning)   
3. Object detection and recognition  
4. Object tracking   
5. Face analysis  
6. Computation photography  
7. SLAM  
8. Real-time application of computer vision

Topics **not included** here but I am also interested with:  
  
1. Image/video captioning  
2. Visual question answering  
3. Vision & Sports
4. Edge detection & semantic segmentation
5. Video / temporal analysis
6. Denoising/deblurring
7. human action analysis
8. Texture/style network

**If you want to see all CVPR 2017 papers, please refer to the CVF open access of all CVPR 2017 papers:**   
* **[Main Conference Papers](http://openaccess.thecvf.com/CVPR2017.py)**  
* **[Workshop Papers](http://openaccess.thecvf.com/CVPR2017_workshops/menu.py)**  

## Papers by topics
### 3D vision and Deep learning
* **Convolutional Neural Network Architecture for Geometric Matching**. **INRIA**.
Ignacio Rocco, Relja ArandjeloviÄ‡, Josef Sivic  
[Paper](https://arxiv.org/abs/1703.05593)

* Inverse Compositional Spatial Transformer Networks.
Chen-Hsuan Lin, Simon Lucey. [Paper](https://arxiv.org/abs/1612.03897)

* Geometric Loss Functions for Camera Pose Regression with Deep Learning.
Alex Kendall, Roberto Cipolla. [Paper](https://arxiv.org/abs/1704.00390)

* Multi-Scale Continuous CRFs as Sequential Deep Networks
for Monocular Depth Estimation. [Paper](https://arxiv.org/abs/1704.02157)

* FCSS: Fully Convolutional Self-Similarity for Dense Semantic Correspondence, Seungryong Kim, Dongbo Min, 
Bumsub Ham, Sangryul Jeon, Stephen Lin, Kwanghoon Sohn 

* End-To-End Training of Hybrid CNN-CRF Models for Stereo.  Patrick Knobelreiter, Christian Reinbacher, Alexander Shekhovtsov, Thomas Pock 

* Semi-Supervised Deep Learning for Monocular Depth Map Prediction, Yevhen Kuznietsov, Jörg Stückler, 
Bastian Leibe 

* DSAC - Differentiable RANSAC for Camera Localization, Eric Brachmann, Alexander Krull, Sebastian 
Nowozin, Jamie Shotton, Frank Michel, Stefan Gumhold, Carsten Rother

### Optical Flow
* FlowNet 2.0: Evolution of Optical Flow Estimation With Deep Networks
Eddy Ilg, Nikolaus Mayer, Tonmoy Saikia, Margret Keuper, Alexey Dosovitskiy, Thomas Brox [Paper](https://arxiv.org/pdf/1612.01925.pdf) [Code](https://github.com/lmb-freiburg/flownet2)  

* Slow Flow: Exploiting High-Speed Cameras for Accurate and Diverse Optical Flow Reference Data, Joel 
Janai, Fatma Güney, Jonas Wulff, Michael J. Black, Andreas Geiger

* CNN-Based Patch Matching for Optical Flow With Thresholded Hinge Embedding Loss, Christian Bailer, 
Kiran Varanasi, Didier Stricker 

* Optical Flow Estimation Using a Spatial Pyramid Network, Anurag Ranjan, Michael J. Black 

* CLKN: Cascaded Lucas-Kanade Networks for Image Alignment, Che-Han Chang, Chun-Nan Chou, Edward Y. 
Chang

* S2F: Slow-To-Fast Interpolator Flow, Yanchao Yang, Stefano Soatto 
### 2D/3D feature detection and matching
* Comparative Evaluation of Hand-Crafted and Learned Local Features. Johannes L. Schönberger,Hans Hardmeier, Torsten Sattler, **Marc Pollefeys**   
[Paper](https://cvg.ethz.ch/research/local-feature-evaluation/schoenberger2017comparative.pdf) [Website](https://cvg.ethz.ch/research/local-feature-evaluation/)

* GMS: Grid-based Motion Statistics for Fast, Ultra-robust Feature Correspondence. JiaWang Bian, Daniel Lin, Yasuyuki Matsushita, Sai-Kit Yeung, Tan Dat Nguyen, **Ming-Ming Cheng**
[Website](http://mmcheng.net/gms/)  [Github](https://github.com/JiawangBian/GMS-Feature-Matcher) [Youtube](https://www.youtube.com/watch?v=tjMpgno6k5A)

* HPatches: A benchmark and evaluation of handcrafted and learned local descriptors, Vassileios Balntas*, Karel Lenc*, Andrea Vedaldi and **Krystian Mikolajczyk**. [Paper] (https://arxiv.org/pdf/1704.05939.pdf) [Github](https://github.com/hpatches/hpatches-benchmark)

* 3DMatch: Learning Local Geometric Descriptors From RGB-D Reconstructions. Andy Zeng, Shuran Song, Matthias Niessner, Matthew Fisher, Jianxiong Xiao, Thomas Funkhouser 

* AnchorNet: A Weakly Supervised Network to Learn Geometry-Sensitive Features for Semantic Matching, 
David Novotny, Diane Larlus, Andrea Vedaldi 

* Quad-Networks: Unsupervised Learning to Rank for Interest Point Detection, Nikolay Savinov, Akihito Seki, Lubor Ladicky, Torsten Sattler, Marc Pollefeys 
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

* Perceptual Generative Adversarial Networks for Small Object Detection, Jianan Li, Xiaodan Liang, Yunchao Wei, 
Tingfa Xu, Jiashi Feng, Shuicheng Yan 

* FastMask: Segment Multi-Scale Object Candidates in One Shot, Hexiang Hu, Shiyi Lan, Yuning Jiang, Zhimin 
Cao, Fei Sha 

*  Multiple Instance Detection Network With Online Instance Classifier Refinement, Peng Tang, Xinggang 
Wang, Xiang Bai, Wenyu Liu 

* Straight to Shapes: Real-Time Detection of Encoded Shapes, Saumya Jetley, Michael Sapienza, Stuart Golodetz, 
Philip H. S. Torr 

### Transfer Learning & Domain Adaptation
* Borrowing Treasures From the Wealthy: Deep Transfer Learning Through Selective Joint Fine-Tuning. Weifeng Ge, Yizhou Yu . [Paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Ge_Borrowing_Treasures_From_CVPR_2017_paper.pdf)

* Fine-Grained Recognition of Thousands of Object Categories With Single-Example Training, Leonid 
Karlinsky, Joseph Shtok, Yochay Tzur, Asaf Tzadok 

*  Matrix Tri-Factorization With Manifold Regularizations for Zero-Shot Learning, Xing Xu, Fumin Shen, Yang Yang, 
Dongxiang Zhang, Heng Tao Shen, Jingkuan Song
 
* Semantically Consistent Regularization for Zero-Shot Recognition, Pedro Morgado, Nuno Vasconcelos 

* Unified Embedding and Metric Learning for Zero-Exemplar Event Detection. Noureldien Hussein, Efstratios 
Gavves, Arnold W.M. Smeulders

* Growing a Brain: Fine-Tuning by Increasing Model Capacity, Yu-Xiong Wang, Deva Ramanan, Martial Hebert

* Zero-Shot Learning - the Good, the Bad and the Ugly,Yongqin Xian, Bernt Schiele, Zeynep Akata

* Adversarial Discriminative Domain Adaptation, Eric Tzeng, Judy Hoffman, Kate Saenko, Trevor Darrell
  
### Computational Photography
* A Unified Approach of Multi-scale Deep and Hand-crafted Features for Defocus Estimation. **KAIST & Tecent Youtu**
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

* HSfM: Hybrid Structure-from-Motion, Hainan Cui, Xiang Gao, Shuhan Shen, Zhanyi Hu 

* IM2CAD, Hamid Izadinia, Qi Shan, Steven M. Seitz

* A Point Set Generation Network for 3D Object Reconstruction From a Single Image, Haoqiang Fan, Hao 
Su, Leonidas J. Guibas 

* Learning Category-Specific 3D Shape Models From Weakly Labeled 2D Images, Dingwen Zhang, Junwei Han, 
Yang Yang, Dong Huang

### RGBD Sensors / Stereo
* Intel RealSense Stereoscopic Depth Cameras.   **Intel**   
[Paper](https://arxiv.org/abs/1705.05548)

* Dynamic Time-Of-Flight. Michael Schober, Amit Adam, Omer Yair, Shai Mazor, Sebastian Nowozin

### DL model compression
* On Compressing Deep Models by Low Rank and Sparse Decomposition, Xiyu Yu, Tongliang Liu, Xinchao Wang, Dacheng Tao

* A Compact DNN: Approaching GoogLeNet-Level Accuracy of Classification and Domain Adaptation, Chunpeng Wu, Wei Wen, Tariq Afzal, Yongmei Zhang, Yiran Chen, Hai (Helen) Li
   
* LCNN: Lookup-Based Convolutional Neural Network, Hessam Bagherinezhad, Mohammad Rastegari, Ali Farhad

* Budget-Aware Deep Semantic Video Segmentation, Behrooz Mahasseni, Sinisa Todorovic, Alan Fern
 
* Fixed-Point Factorized Networks, Peisong Wang, Jian Cheng

* Network Sketching: Exploiting Binary Structure in Deep CNNs, Yiwen Guo, Anbang Yao, Hao Zhao, Yurong Chen 
  
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

* Deep Sketch Hashing: Fast Free-Hand Sketch-Based Image Retrieval, Li Liu, Fumin Shen, Yuming Shen, 
Xianglong Liu, Ling Shao

* Bayesian Supervised Hashing, Zihao Hu, Junxuan Chen, Hongtao Lu, Tongzhen Zhang  

* Simultaneous Feature Aggregating and Hashing for Large-Scale Image Search, Thanh-Toan Do, Dang-Khoa Le Tan, 
Trung T. Pham, Ngai-Man Cheung  

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

* Detangling People: Individuating Multiple Close People and Their Body Parts via Region Assembly, Hao 
Jiang, Kristen Grauman 

* BigHand2.2M Benchmark: Hand Pose Dataset and State of the Art Analysis, Shanxin Yuan, Qi Ye, Björn Stenger, 
Siddhant Jain, Tae-Kyun Kim 

* Towards Accurate Multi-Person Pose Estimation in the Wild, George Papandreou, Tyler Zhu, Nori Kanazawa, 
Alexander Toshev, Jonathan Tompson, Chris Bregler, Kevin Murphy
 
### Face Analysis 
* Learning Residual Images for Face Attribute Manipulation, Wei Shen, Rujie Liu

* Disentangled Representation Learning GAN for Pose-Invariant Face Recognition, Luan Tran, Xi Yin, 
Xiaoming Liu 

* Photorealistic Facial Texture Inference Using Deep Neural Networks, Shunsuke Saito, Lingyu Wei, Liwen Hu, 
Koki Nagano, Hao Li 

* Synthesizing Normalized Faces From Facial Identity Features, Forrester Cole, David Belanger, Dilip Krishnan, 
Aaron Sarna, Inbar Mosseri, William T. Freeman 

* Level Playing Field for Million Scale Face recognition, Aaron Nech, Ira Kemelmacher-Shlizerman

* Reliable Crowdsourcing and Deep Locality-Preserving Learning for Expression Recognition in the Wild, Shan Li, 
Weihong Deng, JunPing Du 

* DenseReg: Fully Convolutional Dense Shape Regression In-The-Wild, Rıza Alp Güler, George Trigeorgis, Epameinondas Antonakos, Patrick Snape, Stefanos Zafeiriou, Iasonas Kokkinos
 
### Object Tracking
* Context-Aware Correlation Filter Tracking, Matthias Mueller, Neil Smith, Bernard Ghanem

* Template Matching With Deformable Diversity Similarity, Itamar Talmi, Roey Mechrez, Lihi Zelnik-Mano

### Machine Learning
* Learning From Simulated and Unsupervised Images Through Adversarial Training, Ashish Shrivastava, Tomas 
Pfister, Oncel Tuzel, Joshua Susskind, Wenda Wang, Russell 
Webb 

* Densely Connected Convolutional Networks, Gao Huang, Zhuang Liu, Laurens van der Maaten, Kilian Q. 
Weinberger 

* Network Dissection: Quantifying Interpretability of Deep Visual Representations, David Bau, Bolei Zhou, Aditya 
Khosla, Aude Oliva, Antonio Torralba 

* AGA: Attribute-Guided Augmentation, Mandar Dixit, Roland Kwitt, Marc Niethammer, Nuno Vasconcelos

* Kernel Pooling for Convolutional Neural Networks, Yin Cui, Feng Zhou, Jiang Wang, Xiao Liu, Yuanqing Lin, Serge 
Belongie 

* Local Binary Convolutional Neural Networks, Felix Juefei-Xu, Vishnu Naresh Boddeti, Marios Savvides

### Multiple View Geometry
* A New Rank Constraint on Multi-View Fundamental Matrices, and Its Application to Camera Location 
Recovery, Soumyadip Sengupta, Tal Amir, Meirav Galun, Tom Goldstein, David W. Jacobs, Amit Singer, Ronen Basri

* Efficient Solvers for Minimal Problems by Syzygy-Based Reduction, Viktor Larsson, Kalle Åström, Magnus 
Oskarsson 

* A Minimal Solution for Two-View Focal-Length Estimation Using Two Affine Correspondences, Daniel 
Barath, Tekla Toth, Levente Hajder 

* A Multi-View Stereo Benchmark With High-Resolution Images and Multi-Camera Videos, Thomas Schöps,  Johannes L. Schönberger, Silvano Galliani, Torsten Sattler, Konrad Schindler, Marc Pollefeys, Andreas Geiger 

* A Clever Elimination Strategy for Efficient Minimal Solvers. Zuzana Kukelova, Joe Kileel, Bernd Sturmfels, 
Tomas Pajdla

* An Efficient Algebraic Solution to the Perspective-Three-Point Problem, Tong Ke, Stergios I. Roumeliotis

* The Misty Three Point Algorithm for Relative Pose, Tobias Palmér, Kalle Åström, Jan-Michael Frahm

## Workshops

