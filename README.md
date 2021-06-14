# Awesome Multi-modal/Multi-source/Multi-sensor Remote Sensing Classification

⚡ **Especially focus on Hyperspectral and LiDAR images.**



## 1. Dataset

- [LCZ Data (Multispectral and SAR data)](https://github.com/danfenghong/IEEE_TGRS_MDL-RS)

  The LCZ data sets are collected from Sentinel-2 and Sentinel-1 satellites, where the former acquires the MS data with ten spectral bands and the latter is able to generate the dual-polarimetric SAR data organized as a commonly used PolSAR covariance matrix (four components). Paper: [Hong et al.2020](https://ieeexplore.ieee.org/document/9174822)

- [DFC2018 Dataset (Multispectral LiDAR and Hyperspectral Data)](https://hyperspectral.ee.uh.edu/?page_id=1075)

  ◗ Multispectral light detecting and ranging (LiDAR) data have three simultaneous different optical wavelengths. For the sake of accessibility to various users, the data are available as point cloud data and digital surface models (DSMs) at a 0.5-m ground sampling distance (GSD). 

  ◗ Hyperspectral data at a 1-m GSD cover a 380–1,050- nm spectral range with 48 contiguous bands. 

  ◗ Very-high-resolution red-green-blue imagery presents at a 5-cm GSD. All data are geo-referenced and cover a geographic area of more than 4 km^2​.  Paper: [Saux et al. 2018](https://ieeexplore.ieee.org/document/8328995)

- [MUUFL Gulfport (Hyperspectral and LiDAR Data)](https://github.com/GatorSense/MUUFLGulfport/)

  The original MUUFL Gulfport data set campus 1 scene contains 325×337 pixels across 72 bands. Due to noise, the first four and last four bands were removed, resulting in a new hyperspectral image of 64 bands. The lower right corner of the original image contains invalid area, thus only the first 220 columns were used for the ground truth mapping. The size of the cropped hyperspectral imagery is 325 × 220 × 64. The ground truth map was provided by manually labeling the pixels in the scene into the following classes in the scene: trees, mostly-grass ground surface, mixed ground surface, dirt and sand, road, water, buildings, shadow of buildings, sidewalk, yellow curb, cloth panels (targets), and unlabeled points. Paper: [Du et al.2017](https://ufdc.ufl.edu/IR00009711/00001)

- [Houston2013 (Hyperspectral and LiDAR Data)](https://hyperspectral.ee.uh.edu/?page_id=459)

  The data sets distributed for the Contest included an HSI, a LiDAR-derived digital surface model (DSM), both at the same spatial resolution (2.5 m), as well as the LiDAR point cloud. The HSI had 144 bands in the 380–1050 nm spectral region. The corresponding co-registered DSM represented the elevation in meters above sea level (per the Geoid 2012 A model). The “las” file of the LiDAR point cloud was also provided. Paper: [Debes et al.2014](https://ieeexplore.ieee.org/abstract/document/6776408)

  

## 2. Paper

#### 2.1 Survey Papers

- [Multisource and Multitemporal Data Fusion in Remote Sensing: A Comprehensive Review of the State of the Art](https://ieeexplore.ieee.org/abstract/document/8672156), IEEE GRSM 2019



#### 2.2 Deep Learning

- [Multimodal Remote Sensing Benchmark Datasets for Land Cover Classification with A Shared and Specific Feature Learning Model](https://www.sciencedirect.com/science/article/pii/S0924271621001362), ISPRS 2021 [[code]](https://github.com/danfenghong/ISPRS_S2FL)
- [Fractional Gabor Convolutional Network for Multisource Remote Sensing Data Classification](https://ieeexplore.ieee.org/document/9383794), IEEE TGRS 2021 [[code]](https://github.com/xudongzhao461/FGCN)
- [Multisource Remote Sensing Data Classification With Graph Fusion Network](https://ieeexplore.ieee.org/document/9325097), IEEE TGRS 2021
- [Deep Residual Network-based Fusion Framework for Hyperspectral and LiDAR Data](https://ieeexplore.ieee.org/abstract/document/9336235), IEEE JSTARS 2021 [[code]](https://github.com/gechiru/RNPRF-RNDFF-RNPMF)
- [Feature Correlation Analysis of Two-Branch Convolutional Networks for Multi-Source Image Classification](https://ieeexplore.ieee.org/abstract/document/9324476), IEEE IGARSS 2020
- [A Multi-Sensor Fusion Framework Based on Coupled Residual Convolutional Neural Networks](https://www.mdpi.com/2072-4292/12/12/2067), Remote Sensing 2020 [[code]](https://github.com/bobleegogogo/CResNetAUX)
- [Multilevel Structure Extraction-Based Multi-Sensor Data Fusion](https://www.mdpi.com/2072-4292/12/24/4034), Remote Sensing 2020 [[code]](https://github.com/PuhongDuan/Multilevel-Structure-Extraction-Based-Multi-Sensor-Data-Fusion)
- [SSR-NET: Spatial–Spectral Reconstruction Network for Hyperspectral and Multispectral Image Fusion](https://ieeexplore.ieee.org/abstract/document/9186332), IEEE TGRS 2020 [[code]](https://github.com/hw2hwei/SSRNET)
- [More Diverse Means Better: Multimodal Deep Learning Meets Remote-Sensing Imagery Classiﬁcation](https://ieeexplore.ieee.org/document/9174822), IEEE TGRS 2020 [[code]](https://github.com/danfenghong/IEEE_TGRS_MDL-RS)
- [Joint Classification of Hyperspectral and LiDAR Data Using Hierarchical Random Walk and Deep CNN Architecture](https://ieeexplore.ieee.org/abstract/document/9057518), IEEE TGRS 2020 [[code]](https://github.com/xudongzhao461/HRWN)
- [Learning-Shared Cross-Modality Representation Using Multispectral-LiDAR and Hyperspectral Data](https://ieeexplore.ieee.org/abstract/document/8976086), IEEE GRSL 2020
- [Deep Encoder-Decoder Networks for Classification of Hyperspectral and LiDAR Data](https://ieeexplore.ieee.org/abstract/document/9179756), IEEE GRSL 2020 [[code]](https://github.com/danfenghong/IEEE_GRSL_EndNet)
- [Classification of Hyperspectral and LiDAR Data Using Coupled CNNs](https://ieeexplore.ieee.org/abstract/document/8985546),  IEEE TGRS 2020 [[code]](https://github.com/RenlongHang/Coupled-CNNs)
- [FusAtNet: Dual Attention based SpectroSpatial Multimodal Fusion Network for Hyperspectral and LiDAR Classification](https://openaccess.thecvf.com/content_CVPRW_2020/html/w6/Mohla_FusAtNet_Dual_Attention_Based_SpectroSpatial_Multimodal_Fusion_Network_for_Hyperspectral_CVPRW_2020_paper.html), CVPRW 2020 [[code]](https://github.com/ShivamP1993/FusAtNet)
- [Feature Extraction for Classification of Hyperspectral and LiDAR Data Using Patch-to-Patch CNN](https://ieeexplore.ieee.org/abstract/document/8467496), IEEE TCYB 2018
- [Multi-Source Remote Sensing Data Classification via Fully Convolutional Networks and Post-Classification Processing](https://ieeexplore.ieee.org/document/8518295), IGARSS 2018. [First place in the 2018 IEEE GRSS Data Fusion Contest]
- [Multisource Remote Sensing Data Classiﬁcation Based on Convolutional Neural Network](https://ieeexplore.ieee.org/abstract/document/8068943), IEEE TGRS 2017 [[code]](https://github.com/Hsuxu/Two-branch-CNN-Multisource-RS-classification)
- [Deep Fusion of Remote Sensing Data for Accurate Classification](https://ieeexplore.ieee.org/abstract/document/7940007), IEEE GRSL 2017



#### 2.3 Traditional Method

- [Inverse Coefficient of Variation Feature and Multilevel Fusion Technique for Hyperspectral and LiDAR Data Classification](https://ieeexplore.ieee.org/document/8961976), IEEE JSTARS 2020
- [Combining feature fusion and decision fusion for classification of hyperspectral and LiDAR data](https://ieeexplore.ieee.org/abstract/document/6946657), IEEE IGARSS 2014



## 3. Related Repositories

- [pliang279/awesome-multimodal-ml](https://github.com/pliang279/awesome-multimodal-ml)
- [Eurus-Holmes/Awesome-Multimodal-Research](https://github.com/Eurus-Holmes/Awesome-Multimodal-Research)