# A low-level vision paperReading List for 2019 & 2020

The following papers are related to low-level vision, including deblur, dehaze, denoise, derain, inpainting, super resolution, lowlight enhancement, demoireing, reflection removal and image restoration.

Pull Requests are welcomed. Feel free to add related papers you like to this list.

A lot of interesting papers are not yet covered by me in the arxiv sections.

## TODO

- [x] [IJCAI 2019](https://www.ijcai19.org/accepted-papers.html)
- [x] [ICLR 2019](https://openreview.net/group?id=ICLR.cc/2019/Conference)
- [x] [ICML 2019](https://icml.cc/Conferences/2019/Schedule?type=Poster)
- [x] [CVPR 2019](http://openaccess.thecvf.com/CVPR2019_search.py) 
- [x] [AAAI 2019](https://aaai.org/Conferences/AAAI-19/wp-content/uploads/2018/11/AAAI-19_Accepted_Papers.pdf)
- [x] [BMVC 2019](https://bmvc2019.org/programme/detailed-programme/#/)
- [x] [ACM MM 2019](https://2019.acmmm.org/accepted-papers/index.html)
- [x] [ICIP 2019](https://cmsworkshops.com/ICIP2019/Papers/TechnicalProgram_MS.asp)
- [x] [ICME](https://www.icme2019.org/conf_schedule)
- [x] [ICCV 2019](http://openaccess.thecvf.com/ICCV2019.py)
- [ ] AAAI 2020

`[Note]`: 

- some IJCAI accepted papers are not available at the moment
- arxiv sections are updated on 2019.7.2
- only titles are maintained for new papers

## Workshops

- [NTIRE 2018](http://openaccess.thecvf.com/CVPR2018_workshops/CVPR2018_W13.py)
- [NTIRE 2019](http://openaccess.thecvf.com/CVPR2019_workshops/CVPR2019_NTIRE.py)
- [AIM 2019](http://openaccess.thecvf.com/ICCV2019_workshops/ICCV2019_AIM.py)
- [UG2+ 2019](http://openaccess.thecvf.com/CVPR2019_workshops/CVPR2019_UG2_Prize_Challenge.py)
- [Vision for All Seasons Bad Weather and Nighttime 2019](http://openaccess.thecvf.com/CVPR2019_workshops/CVPR2019_Vision_for_All_Seasons_Bad_Weather_and_Nighttime.py)

## Denoising

(keywords: denoise, noise, denoising)

### CVPR19

- Toward Convolutional Blind Denoising of Real Photographs
  - Shi Guo, Zifei Yan, Kai Zhang, Wangmeng Zuo, Lei Zhang
- Noise2Void - Learning Denoising From Single Noisy Images
  - Alexander Krull, Tim-Oliver Buchholz, Florian Jug
- FOCNet: A Fractional Optimal Control Network for Image Denoising
  - Xixi Jia, Sanyang Liu, Xiangchu Feng, Lei Zhang
- Unprocessing Images for Learned Raw Denoising
  - Tim Brooks, Ben Mildenhall, Tianfan Xue, Jiawen Chen, Dillon Sharlet, Jonathan T. Barron
- Model-Blind Video Denoising via Frame-To-Frame Training
  - Thibaud Ehret, Axel Davy, Jean-Michel Morel, Gabriele Facciolo, Pablo Arias
  
### ICML19

- Noise2Self: Blind Denoising by Self-Supervision
  - Joshua Batson, Loic Royer

### ICCV19

- Fully Convolutional Pixel Adaptive Image Denoiser
  - Sungmin Cha, Taesup Moon
- CIIDefence: Defeating Adversarial Attacks by Fusing Class-Specific Image Inpainting and Image Denoising
  - Puneet Gupta, Esa Rahtu
- Joint Demosaicking and Denoising by Fine-Tuning of Bursts of Raw Images
  - Thibaud Ehret, Axel Davy, Pablo Arias, Gabriele Facciolo
- Self-Supervised Deep Depth Denoising
  - Vladimiros Sterzentsenko, Leonidas Saroglou, Anargyros Chatzitofis, Spyridon Thermos, Nikolaos Zioulis, Alexandros Doumanoglou, Dimitrios Zarpalas, Petros Daras
- Self-Guided Network for Fast Image Denoising
  - Shuhang Gu, Yawei Li, Luc Van Gool, Radu Timofte
- Real Image Denoising With Feature Attention
  - Saeed Anwar, Nick Barnes
- NOTE-RCNN: NOise Tolerant Ensemble RCNN for Semi-Supervised Object Detection
  - Jiyang Gao, Jiang Wang, Shengyang Dai, Li-Jia Li, Ram Nevatia
- Noise Flow: Noise Modeling With Conditional Normalizing Flows
  - Abdelrahman Abdelhamed, Marcus A. Brubaker, Michael S. Brown
- Enhancing Low Light Videos by Exploring High Sensitivity Camera Noise
  - Wei Wang, Xin Chen, Cheng Yang, Xiang Li, Xuemei Hu, Tao Yue


### ICIP19

- Enhancing denoised image via fusion with a noisy image
- FULL-REFERENCE METRIC ADAPTIVE IMAGE DENOISING
- IMAGE DENOISING WITH GRAPH-CONVOLUTIONAL NEURAL NETWORKS
- ADAPTIVELY TUNING A CONVOLUTIONAL NEURAL NETWORK BY GATING PROCESS FOR IMAGE DENOISING
- DVDnet: A Fast Network for Deep Video Denoising
- MUTUAL NOISE ESTIMATION ALGORITHM FOR VIDEO DENOISING
- COLOR IMAGE DENOISING USING QUATERNION ADAPTIVE NON-LOCAL COUPLED MEANS
- MULTI-KERNEL PREDICTION NETWORKS FOR DENOISING OF BURST IMAGES
- Simultaneous Nonlocal Self-Similarity Prior for Image Denoising
- EDCNN: A NOVEL NETWORK FOR IMAGE DENOISING
- A NON-LOCAL CNN FOR VIDEO DENOISING
- ACCELERATING REDUNDANT DCT FILTERING FOR DEBLURRING AND DENOISING
- NONLOCALITY-REINFORCED CONVOLUTIONAL NEURAL NETWORKS FOR IMAGE DENOISING

### ICME19

- RESIDUAL DILATED NETWORK WITH ATTENTION FOR IMAGE BLIND DENOISING

### arxiv

- NLH: A Blind Pixel-level Non-local Method for Real-world Image Denoising
  - Yingkun Hou, Jun Xu, Mingxia Liu, Guanghai Liu, Li Liu, Fan Zhu, Ling Shao
- Unsupervised Image Noise Modeling with Self-Consistent GAN
  - Hanshu Yan, Vincent Tan, Wenhan Yang, Jiashi Feng
- Robust and interpretable blind image denoising via bias-free convolutional neural networks
  - Sreyas Mohan, Zahra Kadkhodaie, Eero P. Simoncelli, Carlos Fernandez-Granda
- Learning Deep Image Priors for Blind Image Denoising
  - Xianxu Hou, Hongming Luo, Jingxin Liu, Bolei Xu, Ke Sun, Yuanhao Gong, Bozhi Liu, Guoping Qiu
- Image Denoising with Graph-Convolutional Neural Networks
  - Diego Valsesia, Giulia Fracastoro, Enrico Magli
- GAN2GAN: Generative Noise Learning for Blind Image Denoising with Single Noisy Images
  - Sungmin Cha, Taeeon Park, Taesup Moon
- Segmentation-Aware Image Denoising without Knowing True Segmentation
  - Sicheng Wang, Bihan Wen, Junru Wu, Dacheng Tao, Zhangyang Wang
- Joint demosaicing and denoising by overfitting of bursts of raw images
  - Thibaud Ehret, Axel Davy, Pablo Arias, Gabriele Facciolo
- Learning Raw Image Denoising with Bayer Pattern Unification and Bayer Preserving Augmentation
  - Jiaming Liu, Chi-Hao Wu, Yuzhi Wang, Qin Xu, Yuqian Zhou, Haibin Huang, Chuan Wang, Shaofan Cai, Yifan Ding, Haoqiang Fan, Jue Wang
- Efficient Blind Deblurring under High Noise Levels
  - Jérémy Anger, Mauricio Delbracio, Gabriele Facciolo
- Generating Training Data for Denoising Real RGB Images via Camera Pipeline Simulation
  - Ronnachai Jaroensri Camille Biscarrat Miika Aittala Fredo Durand
- Real Image Denoising with Feature Attention
  - Saeed Anwar, Nick Barnes
- Learning Deformable Kernels for Image and Video Denoising
  - Xiangyu Xu, Muchen Li, Wenxiu Sun


## Inpainting

(keywords: inpainting, completion)

### CVPR19

- Learning Pyramid-Context Encoder Network for High-Quality Image Inpainting
  - Yanhong Zeng, Jianlong Fu, Hongyang Chao, Baining Guo
- Deep Flow-Guided Video Inpainting
  - Rui Xu, Xiaoxiao Li, Bolei Zhou, Chen Change Loy
- Deep Video Inpainting
  - Dahun Kim, Sanghyun Woo, Joon-Young Lee, In So Kweon
- Foreground-Aware Image Inpainting
  - Wei Xiong, Jiahui Yu, Zhe Lin, Jimei Yang, Xin Lu, Connelly Barnes, Jiebo Luo
- PEPSI : Fast Image Inpainting With Parallel Decoding Network
  - Min-cheol Sagong, Yong-goo Shin, Seung-wook Kim, Seung Park, Sung-jea Ko
- Coordinate-Based Texture Inpainting for Pose-Guided Human Image Generation
  - Artur Grigorev, Artem Sevastopolsky, Alexander Vakhitov, Victor Lempitsky

### IJCAI19

- Coarse-to-Fine Image Inpainting via Region-wise Convolutions and Non-Local Correlation
  - Yuqing Ma, Xianglong Liu, Shihao Bai, Lei Wang, Dailan He, Aishan Liu
- Generative Image Inpainting with Submanifold Alignment
  - Ang Li, Jianzhong Qi, Rui Zhang, Xingjun Ma, Ramamohanarao Kotagiri
- MUSICAL: Multi-Scale Image Contextual Attention Learning for Inpainting
  - Ning Wang, Jingyuan Li, Lefei Zhang, Bo Du

### AAAI19

- CISI-net: Explicit latent content inference and imitated style rendering for image inpainting
  - Jing Xiao, liang liao, Qiegen Liu, Ruimin Hu
-  Video Inpainting by Jointly Learning Temporal Structure and Spatial Details
  - Chuan Wang, Haibin Huang, Xiaoguang Han, Jue Wang

### ICCV19

- Coherent Semantic Attention for Image Inpainting
  - Hongyu Liu, Bin Jiang, Yi Xiao, Chao Yang
- StructureFlow: Image Inpainting via Structure-Aware Appearance Flow
  - Yurui Ren, Xiaoming Yu, Ruonan Zhang, Thomas H. Li, Shan Liu, Ge Li
- Vision-Infused Deep Audio Inpainting
  - Hang Zhou, Ziwei Liu, Xudong Xu, Ping Luo, Xiaogang Wang
- An Internal Learning Approach to Video Inpainting
  - Haotian Zhang, Long Mai, Ning Xu, Zhaowen Wang, John Collomosse, Hailin Jin
- Copy-and-Paste Networks for Deep Video Inpainting
  - Sungho Lee, Seoung Wug Oh, DaeYeun Won, Seon Joo Kim
- Free-Form Image Inpainting With Gated Convolution
  - Jiahui Yu, Zhe Lin, Jimei Yang, Xiaohui Shen, Xin Lu, Thomas S. Huang
- FiNet: Compatible and Diverse Fashion Image Inpainting
  - Xintong Han, Zuxuan Wu, Weilin Huang, Matthew R. Scott, Larry S. Davis
- Progressive Reconstruction of Visual Structure for Image Inpainting
  - Jingyuan Li, Fengxiang He, Lefei Zhang, Bo Du, Dacheng Tao
- Human Motion Prediction via Spatio-Temporal Inpainting
  - Alejandro Hernandez, Jurgen Gall, Francesc Moreno-Noguer
- Localization of Deep Inpainting Using High-Pass Fully Convolutional Network
  - Haodong Li, Jiwu Huang
- Image Inpainting With Learnable Bidirectional Attention Maps
  - Chaohao Xie, Shaohui Liu, Chao Li, Ming-Ming Cheng, Wangmeng Zuo, Xiao Liu, Shilei Wen, Errui Ding
- Free-Form Video Inpainting With 3D Gated Convolution and Temporal PatchGAN
  - Ya-Liang Chang, Zhe Yu Liu, Kuan-Ying Lee, Winston Hsu

### BMVC19

- Base-Detail Image Inpainting
- Learnable Gated Temporal Shift Module for Free-form Video Inpainting

### ACM MM19

- Progressive Image Inpainting with Full-Resolution Residual Network
- GAIN: Gradient Augmented Inpainting Network for Irregular Holes
- Single-shot Semantic Image Inpainting with Densely Connected Generative
- Deep Fusion Network for Image Completion

### ICIP19

- FASTER UNSUPERVISED SEMANTIC INPAINTING: A GAN BASED APPROACH
- IMAGE INPAINTING FOR RANDOM AREAS USING DENSE CONTEXT FEATURES
- WEIGHTED SCHATTEN P-NORM MINIMIZATION WITH LOCAL AND NONLOCAL CONSTRAINTS FOR NOISY IMAGE COMPLETION


### arxiv

- Coherent Semantic Attention for Image Inpainting
  - Hongyu Liu, Bin Jiang, Yi Xiao, Chao Yang
- PEPSI++: Fast and Lightweight Network for Image Inpainting
  - Yong-Goo Shin, Min-Cheol Sagong, Yoon-Jae Yeo, Seung-Wook Kim, Sung-Jea Ko
- Deep Flow-Guided Video Inpainting
  - Rui Xu, Xiaoxiao Li, Bolei Zhou, Chen Change Loy
- Learning Pyramid-Context Encoder Network for High-Quality Image Inpainting
  - Yanhong Zeng, Jianlong Fu, Hongyang Chao, Baining Guo
- Compatible and Diverse Fashion Image Inpainting
  - Xintong Han, Zuxuan Wu, Weilin Huang, Matthew R. Scott, Larry S. Davis
- Deep Hyperspectral Prior: Denoising, Inpainting, Super-Resolution
  - Oleksii Sidorov, Jon Yngve Hardeberg
- EdgeConnect: Generative Image Inpainting with Adversarial Edge Learning
  - Kamyar Nazeri, Eric Ng, Tony Joseph, Faisal Z. Qureshi, Mehran Ebrahimi

## Lowlight Enhancement

(keywords: lowlight, underexposed, illumination, contrast enhancement, low light, dark)

### CVPR19

- Underexposed Photo Enhancement Using Deep Illumination Estimation
  - Ruixing Wang, Qing Zhang, Chi-Wing Fu, Xiaoyong Shen, Wei-Shi Zheng, Jiaya Jia

### ICCV19

- A Dataset of Multi-Illumination Images in the Wild
  - Lukas Murmann, Michael Gharbi, Miika Aittala, Fredo Durand
- No Fear of the Dark: Image Retrieval Under Varying Illumination Conditions
  - Tomas Jenicek, Ondrej Chum
- Enhancing Low Light Videos by Exploring High Sensitivity Camera Noise
  - Wei Wang, Xin Chen, Cheng Yang, Xiang Li, Xuemei Hu, Tao Yue
- Seeing Motion in the Dark
  - Chen Chen, Qifeng Chen, Minh N. Do, Vladlen Koltun
- Learning to See Moving Objects in the Dark
  - Haiyang Jiang, Yinqiang Zheng


### BMVC19

- BIRD: Learning Binary and Illumination Robust Descriptor for Face Recognition

### ACM MM19

- Progressive Retinex: Mutually Reinforced Illumination-Noise Perception Network for Low-Light Image Enhancement
- Adaptive Feature Fusion via Graph Neural Network for Person Re-identification Illumination-Invariant Person Re-Identification
- Kindling the Darkness: A Practical Low-light Image Enhancer

### ICIP19

- WHAT'S THERE IN THE DARK
- LLRNET: A MULTISCALE SUBBAND LEARNING APPROACH FOR LOW LIGHT IMAGE RESTORATION

### arxiv

- [Kindling the Darkness: A Practical Low-light Image Enhancer](https://arxiv.org/pdf/1905.04161v1.pdf)
  - Yonghua Zhang, Jiawan Zhang, and Xiaojie Guo
- [EnlightenGAN: Deep Light Enhancement without Paired Supervision](https://arxiv.org/pdf/1906.06972.pdf)
  - Yifan Jiang, Xinyu Gong, Ding Liu, Yu Cheng, Chen Fang, Xiaohui Shen, Jianchao Yang, Pan Zhou, Zhangyang Wang
- [Low-light Image Enhancement Algorithm Based on Retinex and Generative Adversarial Network](https://arxiv.org/abs/1906.06027)
  - Yangming Shi, Xiaopo Wu, Ming Zhu
- [LED2Net: Deep Illumination-aware Dehazing with Low-light and Detail Enhancement](https://arxiv.org/abs/1906.05119)
  - Guisik Kim, Junseok Kwon
- [A Noise-aware Enhancement Method for Underexposed Images](https://arxiv.org/abs/1904.10961)
  - Chien-Cheng Chien, Yuma Kinoshita, Hitoshi Kiya
- [End-to-End Denoising of Dark Burst Images Using Recurrent Fully Convolutional Networks](https://arxiv.org/abs/1904.07483)
  - Di Zhao, Lan Ma, Songnan Li, Dahai Yu
- [A Retinex-based Image Enhancement Scheme with Noise Aware Shadow-up Function](https://arxiv.org/abs/1811.03280)
  - Chien Cheng Chien, Yuma Kinoshita, Sayaka Shiota, Hitoshi Kiya

## Dehazing

(keywords: dehazing, haze)

### CVPR19

- Enhanced Pix2pix Dehazing Network
  - Yanyun Qu, Yizi Chen, Jingying Huang, Yuan Xie
- PMS-Net: Robust Haze Removal Based on Patch Map for Single Images
  - Wei-Ting Chen, Jian-Jiun Ding, Sy-Yen Kuo

### IJCAI19

- Dual-Path in Dual-Path Network for Single Image Dehazing
  - Aiping Yang, Haixin Wang, Zhong Ji, Yanwei Pang, Ling Shao

### ICCV19
- Deep Multi-Model Fusion for Single-Image Dehazing
  - Zijun Deng, Lei Zhu, Xiaowei Hu, Chi-Wing Fu, Xuemiao Xu, Qing Zhang, Jing Qin, Pheng-Ann Heng
- Learning Deep Priors for Image Dehazing
  - Yang Liu, Jinshan Pan, Jimmy Ren, Zhixun Su
- LAP-Net: Level-Aware Progressive Network for Image Dehazing
  - Yunan Li, Qiguang Miao, Wanli Ouyang, Zhenxin Ma, Huijuan Fang, Chao Dong, Yining Quan
- GridDehazeNet: Attention-Based Multi-Scale Network for Image Dehazing
  - Xiaohong Liu, Yongrui Ma, Zhihao Shi, Jun Chen

### ICIP19

- WAVELET U-NET AND THE CHROMATIC ADAPTATION TRANSFORM FOR SINGLE IMAGE DEHAZING
- Towards Unsupervised Single Image Dehazing with Deep Learning
- Convolutional AutoEncoder for Single Image Dehazing
- SEQUENTIALLY REFINED SPATIAL AND CHANNEL-WISE FEATURE AGGREGATION IN ENCODER-DECODER NETWORK FOR SINGLE IMAGE DEHAZING
- DENSE-HAZE: A BENCHMARK FOR IMAGE DEHAZING WITH DENSE-HAZE AND HAZE-FREE IMAGES
- VARIATIONAL REGULARIZED TRANSMISSION REFINEMENT FOR IMAGE DEHAZING
- Feature Aggregation Convolution Network For Haze Removal

### arxiv

- FAMED-Net: A Fast and Accurate Multi-scale End-to-end Dehazing Network
  - Jing Zhang, Dacheng Tao
- Joint haze image synthesis and dehazing with mmd-vae losses
  - Zongliang Li, Chi Zhang, Gaofeng Meng, Yuehu Liu
- Weighted Dark Channel Dehazing
  - Zhu Mingzhu, He Bingwei, Liu Jiantao
- Multiple Linear Regression Haze-removal Model Based on Dark Channel Prior
  - Binghan Li, Wenrui Zhang, Mi Lu
- Feature Forwarding for Efficient Single Image Dehazing
  - Peter Morales, Tzofi Klinghoffer, Seung Jae Lee
- Fast Single Image Dehazing via Multilevel Wavelet Transform based Optimization
  - Jiaxi He, Frank Z. Xing, Ran Yang, Cishen Zhang
- A Light Dual-Task Neural Network for Haze Removal
  - Yu Zhang, Xinchao Wang, Xiaojun Bi, Dacheng Tao
- Dense Haze: A benchmark for image dehazing with dense-haze and haze-free images
  - Codruta O. Ancuti, Cosmin Ancuti, Mateu Sbert, Radu Timofte
- Learning of Image Dehazing Models for Segmentation Tasks
  - Sébastien de Blois, Ihsen Hedhli, Christian Gagné
- Variational Regularized Transmission Refinement for Image Dehazing
  - Qiaoling Shu, Chuansheng Wu, Zhe Xiao, Ryan Wen Liu
- Night Time Haze and Glow Removal using Deep Dilated Convolutional Network
  - Shiba Kuanar, K.R. Rao, Dwarikanath Mahapatra, Monalisa Bilas
- Unsupervised Single Image Dehazing Using Dark Channel Prior Loss
  - Alona Golts, Daniel Freedman, Michael Elad
- Image Dehazing via Joint Estimation of Transmittance Map and Environmental Illumination
  - Sanchayan Santra, Ranjan Mondal, Pranoy Panda, Nishant Mohanty, Shubham Bhuyan
- Reconstruction Loss Minimized FCN for Single Image Dehazing
  - Shirsendu Sukanta Halder, Sanchayan Santra, Bhabatosh Chanda
- Single Image Haze Removal Using Conditional Wasserstein Generative Adversarial Networks
  - Joshua Peter Ebenezer, Bijaylaxmi Das, Sudipta Mukhopadhyay


## Derain 

(keywords: rain, deraining)

### CVPR19

- Heavy Rain Image Restoration: Integrating Physics Model and Conditional Adversarial Learning
  - Ruoteng Li, Loong-Fah Cheong, Robby T. Tan
- Semi-Supervised Transfer Learning for Image Rain Removal
  - Wei Wei, Deyu Meng, Qian Zhao, Zongben Xu, Ying Wu
- Depth-Attentional Features for Single-Image Rain Removal
  - Xiaowei Hu, Chi-Wing Fu, Lei Zhu, Pheng-Ann Heng
- Spatial Attentive Single-Image Deraining With a High Quality Real Rain Dataset
  - Tianyu Wang, Xin Yang, Ke Xu, Shaozhe Chen, Qiang Zhang, Rynson W.H. Lau
- Frame-Consistent Recurrent Video Deraining With Dual-Level Flow
  - Wenhan Yang, Jiaying Liu, Jiashi Feng
- Single Image Deraining: A Comprehensive Benchmark Analysis
  - Siyuan Li, Iago Breno Araujo, Wenqi Ren, Zhangyang Wang, Eric K. Tokuda, Roberto Hirata Junior, Roberto Cesar-Junior, Jiawan Zhang, Xiaojie Guo, Xiaochun Cao
- Progressive Image Deraining Networks: A Better and Simpler Baseline
  - Dongwei Ren, Wangmeng Zuo, Qinghua Hu, Pengfei Zhu, Deyu Meng

### AAAI19

- RR-GAN: Single Image Rain Removal Without Paired Information
  - Hongyuan Zh, Xi Peng, Joey Tianyi Zhou, Songfan Yang, Vijay Chandrasekhar, Liyuan Li, Joo-Hwee Lim

### ICCV19

- RainFlow: Optical Flow Under Rain Streaks and Rain Veiling Effect
  - Ruoteng Li, Robby T. Tan, Loong-Fah Cheong, Angelica I. Aviles-Rivero, Qingnan Fan, Carola-Bibiane Schonlieb
- Physics-Based Rendering for Improving Robustness to Rain
  - Shirsendu Sukanta Halder, Jean-Francois Lalonde, Raoul de Charette


### BMVC19

- Residual Multiscale Based Single Image Deraining

### ACM MM19

- Single Image Deraining via Recurrent Hierarchy Enhancement Network
- Gradual Network for Single Image De-raining
- DTDN: Dual-task De-raining Network

### ICIP19

- DUAL RECURSIVE NETWORK FOR FAST IMAGE DERAINING
- OND SYNTHETIC DATA: A BLIND DERAINING QUALITY ASSESSMENT METRIC TOWARDS AUTHENTIC RAIN IMAGE
- Denoising Adversarial Networks for Rain Removal and Reflection Removal
- RAIN STREAKS REMOVAL FOR SINGLE IMAGE VIA DIRECTIONAL TOTAL VARIATION REGULARIZATION
- Single-image rain removal via multi-scale cascading image generation
- UNSUPERVISED SINGLE IMAGE DERAINING WITH SELF-SUPERVISED CONSTRAINTS
- SELF-REFINING DEEP SYMMETRY ENHANCED NETWORK FOR RAIN REMOVAL
- DUAL-DOMAIN SINGLE IMAGE DE-RAINING USING CONDITIONAL GENERATIVE ADVERSARIAL NETWORK

### ICME19

- REMOVING RAIN IN VIDEOS: A LARGE-SCALE DATABASE AND A TWO-STREAM CONVLSTM AP- PROACH

### arxiv

- Morphological Networks for Image De-raining
  - Ranjan Mondal, Pulak Purkait, Sanchayan Santra, Bhabatosh Chanda
- A Deep Tree-Structured Fusion Model for Single Image Deraining
  - Xueyang Fu, Qi Qi, Yue Huang, Xinghao Ding, Feng Wu, John Paisley
- Unsupervised Single Image Deraining with Self-supervised Constraints
  - Xin Jin, Zhibo Chen, Jianxin Lin, Zhikai Chen, Wei Zhou
- Deep Single Image Deraining Via Estimating Transmission and Atmospheric Light in rainy Scenes
  - Yinglong Wang, Qinfeng Shi, Ehsan Abbasnejad, Chao Ma, Xiaoping Ma, Bing Zeng
- An Effective Two-Branch Model-Based Deep Network for Single Image Deraining
  - Yinglong Wang, Dong Gong, Jie Yang, Qinfeng Shi, Anton van den Hengel, Dehua Xie, Bing Zeng
- Rain O'er Me: Synthesizing real rain to derain with data distillation
  - Huangxing Lin, Yanlong Li, Xinghao Ding, Weihong Zeng, Yue Huang, John Paisley
- Directional Regularized Tensor Modeling for Video Rain Streaks Removal
  - Zhaoyang Sun, Shengwu Xiong, Ryan Wen Liu
- Gated Context Aggregation Network for Image Dehazing and Deraining
  - Dongdong Chen, Mingming He, Qingnan Fan, Jing Liao, Liheng Zhang, Dongdong Hou, Lu Yuan, Gang Hua

## Demoireing

(keywords: demoireing, moire)

## Reflection removal

(keywords: reflection, deglare)

### CVPR19

- Reflection Removal Using a Dual-Pixel Sensor
- Single Image Reflection Removal Beyond Linearity
- Fast Single Image Reflection Suppression via Convex Optimization
- Single Image Reflection Removal Exploiting Misaligned Training Data and Network Enhancements

### ICIP19

- Denoising Adversarial Networks for Rain Removal and Reflection Removal
- Multi-Modal Reflection Removal Using Convolutional Neural Networks

## Image Restoration

### ICLR

- Residual Non-local Attention Networks for Image Restoration
  - Yulun Zhang, Kunpeng Li, Kai Li, Bineng Zhong, Yun Fu
- Dynamically Unfolding Recurrent Restorer: A Moving Endpoint Control Method for Image Restoration
  - Xiaoshuai Zhang, Yiping Lu, Jiaying Liu, Bin Dong

### CVPR19

- Dual Residual Networks Leveraging the Potential of Paired Operations for Image Restoration
  - Xing Liu, Masanori Suganuma, Zhun Sun, Takayuki Okatani
- Attention-Based Adaptive Selection of Operations for Image Restoration in the Presence of Unknown Combined Distortions
  - Masanori Suganuma, Xing Liu, Takayuki Okatani
- Modulating Image Restoration With Continual Levels via Adaptive Feature Modification Layers
  - Jingwen He, Chao Dong, Yu Qiao

### ICCV19

- CFSNet: Toward a Controllable Feature Space for Image Restoration
  - Wei Wang, Ruiming Guo, Yapeng Tian, Wenming Yang
- Fast Image Restoration With Multi-Bin Trainable Linear Units
  - Shuhang Gu, Wen Li, Luc Van Gool, Radu Timofte
- Restoration of Non-Rigidly Distorted Underwater Images Using a Combination of Compressive Sensing and Local Polynomial Image Representations
  - Jerin Geo James, Pranay Agrawal, Ajit Rajwade

### arxiv

- Space-variant Generalized Gaussian Regularization for Image Restoration
  - Alessandro Lanza, Serena Morigi, Monica Pragliola, Fiorella Sgallari
- Image-Adaptive GAN based Reconstruction
  - Shady Abu Hussein, Tom Tirer, Raja Giryes
- Path-Restore: Learning Network Path Selection for Image Restoration
  - Ke Yu, Xintao Wang, Chao Dong, Xiaoou Tang, Chen Change Loy
- Deep Likelihood Network for Image Restoration with Multiple Degradations
  - Yiwen Guo, Wangmeng Zuo, Changshui Zhang, Yurong Chen
- Image Restoration by Combined Order Regularization with Optimal Spatial Adaptation
  - Sanjay Viswanath, Simon de Beco, Maxime Dahan, Muthuvel Arigovindan

### ICIP19

- HIGH-DIMENSIONAL EMBEDDING DENOISING AUTOENCODING PRIOR FOR COLOR IMAGE RESTORATION
- JOINT IMAGE RESTORATION AND MATCHING BASED ON HIERARCHICAL SPARSE REPRESENTATION
- UNDERWATER IMAGE SYNTHESIS FROM RGB-D IMAGES AND ITS APPLICATION TO DEEP UNDERWATER IMAGE RESTORATION
- 

## Super Resolution

### CVPR19

- Deep Plug-And-Play Super-Resolution for Arbitrary Blur Kernels
  - Kai Zhang, Wangmeng Zuo, Lei Zhang
- Meta-SR: A Magnification-Arbitrary Network for Super-Resolution
  - Xuecai Hu, Haoyuan Mu, Xiangyu Zhang, Zilei Wang, Tieniu Tan, Jian Sun
- Blind Super-Resolution With Iterative Kernel Correction
  - Jinjin Gu, Hannan Lu, Wangmeng Zuo, Chao Dong
- Camera Lens Super-Resolution
  - Chang Chen, Zhiwei Xiong, Xinmei Tian, Zheng-Jun Zha, Feng Wu
- Towards Real Scene Super-Resolution With Raw Images
  - Xiangyu Xu, Yongrui Ma, Wenxiu Sun
- ODE-Inspired Network Design for Single Image Super-Resolution
  - Xiangyu He, Zitao Mo, Peisong Wang, Yang Liu, Mingyuan Yang, Jian Cheng
- Feedback Network for Image Super-Resolution
  - Zhen Li, Jinglei Yang, Zheng Liu, Xiaomin Yang, Gwanggil Jeon, Wei Wu
- Recurrent Back-Projection Network for Video Super-Resolution
  - Muhammad Haris, Gregory Shakhnarovich, Norimichi Ukita
- Image Super-Resolution by Neural Texture Transfer
  - Zhifei Zhang, Zhaowen Wang, Zhe Lin, Hairong Qi
- Natural and Realistic Single Image Super-Resolution With Explicit Natural Manifold Discrimination
  - Jae Woong Soh, Gu Yong Park, Junho Jo, Nam Ik Cho
- Fast Spatio-Temporal Residual Network for Video Super-Resolution
  - Sheng Li, Fengxiang He, Bo Du, Lefei Zhang, Yonghao Xu, Dacheng Tao
- Residual Networks for Light Field Image Super-Resolution
  - Shuo Zhang, Youfang Lin, Hao Sheng
- Second-Order Attention Network for Single Image Super-Resolution
  - Tao Dai, Jianrui Cai, Yongbing Zhang, Shu-Tao Xia, Lei Zhang
- Hyperspectral Image Super-Resolution With Optimized RGB Guidance
  - Ying Fu, Tao Zhang, Yinqiang Zheng, Debing Zhang, Hua Huang

### ICCV19

- Embedded Block Residual Network: A Recursive Restoration Model for Single-Image Super-Resolution
  - Yajun Qiu, Ruxin Wang, Dapeng Tao, Jun Cheng
- Evaluating Robustness of Deep Image Super-Resolution Against Adversarial Attacks
  - Jun-Ho Choi, Huan Zhang, Jun-Hyuk Kim, Cho-Jui Hsieh, Jong-Seok Lee
- Kernel Modeling Super-Resolution on Real Low-Resolution Images
  - Ruofan Zhou, Sabine Susstrunk
- SROBB: Targeted Perceptual Loss for Single Image Super-Resolution
  - Mohammad Saeed Rad, Behzad Bozorgtabar, Urs-Viktor Marti, Max Basler, Hazim Kemal Ekenel, Jean-Philippe Thiran
- Wavelet Domain Style Transfer for an Effective Perception-Distortion Tradeoff in Single Image Super-Resolution
  - Xin Deng, Ren Yang, Mai Xu, Pier Luigi Dragotti
- Toward Real-World Single Image Super-Resolution: A New Benchmark and a New Model
  - Jianrui Cai, Hui Zeng, Hongwei Yong, Zisheng Cao, Lei Zhang
- RankSRGAN: Generative Adversarial Networks With Ranker for Image Super-Resolution
  - Wenlong Zhang, Yihao Liu, Chao Dong, Yu Qiao
- Progressive Fusion Video Super-Resolution Network via Exploiting Non-Local Spatio-Temporal Correlations
  - Peng Yi, Zhongyuan Wang, Kui Jiang, Junjun Jiang, Jiayi Ma
- Deep SR-ITM: Joint Learning of Super-Resolution and Inverse Tone-Mapping for 4K UHD HDR Applications
  - Soo Ye Kim, Jihyong Oh, Munchurl Kim
- Embedded Block Residual Network: A Recursive Restoration Model for Single-Image Super-Resolution
  - Yajun Qiu, Ruxin Wang, Dapeng Tao, Jun Cheng
- Perceptual Deep Depth Super-Resolution
  - Oleg Voynov, Alexey Artemov, Vage Egiazarian, Alexander Notchenko, Gleb Bobrovskikh, Evgeny Burnaev, Denis Zorin
- Two-Stream Action Recognition-Oriented Video Super-Resolution
  - Haochen Zhang, Dong Liu, Zhiwei Xiong
- Guided Super-Resolution As Pixel-to-Pixel Transformation
  - Riccardo de Lutio, Stefano D'Aronco, Jan Dirk Wegner, Konrad Schindler
- Better to Follow, Follow to Be Better: Towards Precise Supervision of Feature Super-Resolution for Small Object Detection
  - Junhyug Noh, Wonho Bae, Wonhee Lee, Jinhwan Seo, Gunhee Kim

### BMVC19

- Joint Multi-view Texture Super-resolution and Intrinsic Decomposition
- Gated Multiple Feedback Network for Image Super-Resolution
- Wide Activation for Efficient Image and Video Super-Resolution
- Progressive Face Super-Resolution via Attention to Facial Landmark
- Single Image Super-Resolution via CNN Architectures and TV-TV Minimization

### ACM MM19

- FGLmser: A Flexible GAN-Lmser for Super-Resolution
- Super Resolution Using Dual Path Connections

### ICIP19

- IMAGE SUPER-RESOLUTION USING CNN OPTIMISED BY SELF-FEATURE LOSS
- Learning a cascade regression for no-reference super-resolution image quality assessment
- MULTI-LEVEL RESIDUAL UP-PROJECTION ACTIVATION NETWORK FOR IMAGE SUPER-RESOLUTION
- LEARNING QUATERNION GRAPH FOR COLOR FACE IMAGE SUPER-RESOLUTION
- NON-LOCAL HIERARCHICAL RESIDUAL NETWORK FOR SINGLE IMAGE SUPER-RESOLUTION
- Guided CycleGAN via Semi-Dual Optimal Transport for Photo-Realistic Face Super-resolution
- JITTERED EXPOSURES FOR LIGHT FIELD SUPER-RESOLUTION
- FAST AND LIGHTWEIGHT IMAGE SUPER-RESOLUTION BASED ON DENSE RESIDUALS TWO-CHANNEL NETWORK
- LEARNING SPATIAL AND SPECTRAL FEATURES VIA 2D-1D GENERATIVE ADVERSARIAL NETWORK FOR HYPERSPECTRAL IMAGE SUPER-RESOLUTION
- FAST SUPER-RESOLUTION IN MRI IMAGES USING PHASE STRETCH TRANSFORM, ANCHORED POINT REGRESSION AND ZERO-DATA LEARNING
- PRED: A PARALLEL NETWORK FOR HANDLING MULTIPLE DEGRADATIONS VIA SINGLE MODEL IN SINGLE IMAGE SUPER-RESOLUTION
- GAN-BASED VIDEO SUPER-RESOLUTION WITH DIRECT REGULARIZED INVERSION OF THE LOW-RESOLUTION FORMATION MODEL
- LEARNED MULTIMODAL CONVOLUTIONAL SPARSE CODING FOR GUIDED IMAGE SUPER-RESOLUTION
- MULTI-FRAME SUPER RESOLUTION WITH DEEP RESIDUAL LEARNING ON FLOW REGISTERED NON-INTEGER PIXEL IMAGES
- SINGLE IMAGE SUPER-RESOLUTION VIA CASCADED PARALLEL MULTISIZE RECEPTIVE FIELD
- IMAGE SUPER-RESOLUTION USING COMPLEX DENSE BLOCK ON GENERATIVE ADVERSARIAL NETWORKS
- IMPROVING SUPER RESOLUTION METHODS VIA INCREMENTAL RESIDUAL LEARNING
- LEARNING SUPER-RESOLUTION COHERENT FACIAL FEATURES USING NONLINEAR MULTISET PLS FOR LOW-RESOLUTION FACE RECOGNITION

### ICME19

- GAN-BASED MULTI-LEVEL MAPPING NETWORK FOR SATELLITE IMAGERY SUPER-RESOLUTION
- RECURSIVE MULTI-STAGE UPSCALING NETWORK WITH DISCRIMINATIVE FUSION FOR SUPER-RESOLUTION
- IMPROVING IMAGE SUPER-RESOLUTION VIA FEATURE RE-BALANCING FUSION
- DIFFICULTY-AWARE IMAGE SUPER RESOLUTION VIA DEEP ADAPTIVE DUAL-NETWORK
- DENSE-CONNECTED RESIDUAL NETWORK FOR VIDEO SUPER-RESOLUTION
- RESIDUAL MAGNIFIER: A DENSE INFORMATION FLOW NETWORK FOR SUPER RESOLUTION
- JOINTLY SOLVING DEBLURRING AND SUPER-RESOLUTION PROBLEMS WITH DUAL SUPER- VISED NETWORK

### arxiv

- Densely Residual Laplacian Super-Resolution
  - Saeed Anwar, Nick Barnes
- Trinity of Pixel Enhancement: a Joint Solution for Demosaicking, Denoising and Super-Resolution
  - Guocheng Qian, Jinjin Gu, Jimmy S. Ren, Chao Dong, Furong Zhao, Juan Lin
- Exemplar Guided Face Image Super-Resolution without Facial Landmarks
  - Berk Dogan, Shuhang Gu, Radu Timofte
- Suppressing Model Overfitting for Image Super-Resolution Networks
  - Ruicheng Feng, Jinjin Gu, Yu Qiao, Chao Dong
- Hybrid Function Sparse Representation towards Image Super Resolution
  - Junyi Bian, Baojun Lin, Ke Zhang
- Ensemble Super-Resolution with A Reference Dataset
  - Junjun Jiang, Yi Yu, Zheng Wang, Suhua Tang, Ruimin Hu, Jiayi Ma
- Adapting Image Super-Resolution State-of-the-arts and Learning Multi-model Ensemble for Video Super-Resolution
  - Chao Li, Dongliang He, Xiao Liu, Yukang Ding, Shilei Wen
- Joint High Dynamic Range Imaging and Super-Resolution from a Single Image
  - Jae Woong Soh, Jae Sung Park, Nam Ik Cho
- Super-resolution based generative adversarial network using visual perceptual loss function
  - Xuan Zhu, Yue Cheng, Rongzhi Wang
- Multi-scale deep neural networks for real image super-resolution
  - Shangqi Gao, Xiahai Zhuang
- Adaptive Transform Domain Image Super-resolution Via Orthogonally Regularized Deep Networks
  - Tiantong Guo, Hojjat S. Mousavi, Vishal Monga
- Label Super Resolution with Inter-Instance Loss
  - Maozheng Zhao, Le Hou, Han Le, Dimitris Samaras, Nebojsa Jojic, Danielle Fassler, Tahsin Kurc, Rajarsi Gupta, Kolya Malkin, Shahira Abousamra, Shroyer Kenneth, Joel Saltz
- Fast Spatio-Temporal Residual Network for Video Super-Resolution
  - Sheng Li, Fengxiang He, Bo Du, Lefei Zhang, Yonghao Xu, Dacheng Tao
- Lightweight Image Super-Resolution with Adaptive Weighted Learning Network
  - Chaofeng Wang, Zheng Li, Jun Shi
- The dual approach to non-negative super-resolution: impact on primal reconstruction accuracy
  - Stephane Chretien, Andrew Thompson, Bogdan Toader
- Guided Super-Resolution as a Learned Pixel-to-Pixel Transformation
  - Riccardo de Lutio, Stefano D'Aronco, Jan Dirk Wegner, Konrad Schindler
- Toward Real-World Single Image Super-Resolution: A New Benchmark and A New Model
  - Jianrui Cai, Hui Zeng, Hongwei Yong, Zisheng Cao, Lei Zhang
- SRDGAN: learning the noise prior for Super Resolution with Dual Generative Adversarial Networks
  - Jingwei Guan, Cheng Pan, Songnan Li, Dahai Yu
- A Matrix-in-matrix Neural Network for Image Super Resolution
  - Hailong Ma, Xiangxiang Chu, Bo Zhang, Shaohua Wan, Bo Zhang
- Robust Super-Resolution GAN, with Manifold-based and Perception Loss
  - Uddeshya Upadhyay, Suyash P. Awate

## Deblur

### CVPR19

- Blind Image Deblurring With Local Maximum Gradient Prior
  - Liang Chen, Faming Fang, Tingting Wang, Guixu Zhang
- Dynamic Scene Deblurring With Parameter Selective Sharing and Nested Skip Connections
  - Hongyun Gao, Xin Tao, Xiaoyong Shen, Jiaya Jia
- Deep Stacked Hierarchical Multi-Patch Network for Image Deblurring
  - Hongguang Zhang, Yuchao Dai, Hongdong Li, Piotr Koniusz
- Phase-Only Image Based Kernel Estimation for Single Image Blind Deblurring
  - Liyuan Pan, Richard Hartley, Miaomiao Liu, Yuchao Dai
- Recurrent Neural Networks With Intra-Frame Iterations for Video Deblurring
  - Seungjun Nah, Sanghyun Son, Kyoung Mu Lee

### ICCV19

- FAB: A Robust Facial Landmark Detection Framework for Motion-Blurred Videos
  - Keqiang Sun, Wayne Wu, Tinghao Liu, Shuo Yang, Quan Wang, Qiang Zhou, Zuochang Ye, Chen Qian
- Human-Aware Motion Deblurring
  - Ziyi Shen, Wenguan Wang, Xiankai Lu, Jianbing Shen, Haibin Ling, Tingfa Xu, Ling Shao
- Unconstrained Motion Deblurring for Dual-Lens Cameras
  - M. R. Mahesh Mohan, Sharath Girish, A. N. Rajagopalan

### ACM MM19

- Tell Me Where It is Still Blurry: Adversarial Blurred Region Mining and Refining

### ICIP19

- ADVERSARIAL REPRESENTATION LEARNING FOR DYNAMIC SCENE DEBLURRING: A SIMPLE, FAST AND ROBUST APPROACH
- UPDCNN: A NEW SCHEME FOR IMAGE UPSAMPLING AND DEBLURRING USING A DEEP CONVOLUTIONAL NEURAL NETWORK
- LEARNED IMAGE DEBLURRING BY UNFOLDING A PROXIMAL INTERIOR POINT ALGORITHM
- EFFICIENT MOTION DEBLURRING WITH FEATURE TRANSFORMATION AND SPATIAL ATTENTION
- Joint Demosaicking and Blind Deblurring Using Deep Convolutional Neural Network
- ACCELERATING REDUNDANT DCT FILTERING FOR DEBLURRING AND DENOISING

### ICME19

- JOINTLY SOLVING DEBLURRING AND SUPER-RESOLUTION PROBLEMS WITH DUAL SUPER- VISED NETWORK
- SCALE-AWARE DEEP NETWORK WITH HOLE CONVOLUTION FOR BLIND MOTION DEBLURRING

### arxiv

- Blind Image Deblurring Using Patch-Wise Minimal Pixels Regularization
  - Fei Wen, Rendong Ying, Peilin Liu, Trieu-Kien Truong
- Single Image Blind Deblurring Using Multi-Scale Latent Structure Prior
  - Yuanchao Bai, Huizhu Jia, Ming Jiang, Xianming Liu, Xiaodong Xie, Wen Gao
- Efficient Blind Deblurring under High Noise Levels
  - Jérémy Anger, Mauricio Delbracio, Gabriele Facciolo
- Coupled Learning for Facial Deblur
  - Dayong Tian, Dacheng Tao
- Deep Stacked Hierarchical Multi-patch Network for Image Deblurring
  - Hongguang Zhang, Yuchao Dai, Hongdong Li, Piotr Koniusz
- Fast and Full-Resolution Light Field Deblurring using a Deep Neural Network
  - Jonathan Samuel Lumentut, Tae Hyun Kim, Ravi Ramamoorthi, In Kyu Park
- Kernel-Free Image Deblurring with a Pair of Blurred/Noisy Images
  - Chunzhi Gu, Xuequan Lu, Ying He, Chao Zhang
- Down-Scaling with Learned Kernels in Multi-Scale Deep Neural Networks for Non-Uniform Single Image Deblurring
  - Dongwon Park, Jisoo Kim, Se Young Chun
- Single Image Deblurring and Camera Motion Estimation with Depth Map
  - Liyuan Pan, Yuchao Dai, Miaomiao Liu
- An Algorithm Unrolling Approach to Deep Image Deblurring
  - Yuelong Li, Mohammad Tofighi, Vishal Monga, Yonina C. Eldar
- Deep Algorithm Unrolling for Blind Image Deblurring
  - Yuelong Li, Mohammad Tofighi, Junyi Geng, Vishal Monga, Yonina C. Eldar
