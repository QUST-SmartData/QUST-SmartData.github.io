# SmartData

<div align=center><img src ="logo.jpg"/></div>

欢迎来到我们的GitHub团队主页！

我们团队致力于推动地质和医学等领域的图像分析研究，通过深度学习和计算机视觉技术解决实际问题。


## 研究方向
我们专注于以下研究方向: 

- 🖼️ 计算机视觉
- 🧠 深度学习
- 🤖 机器学习
- 🌍 地质学图像分析
- 🏥 医学图像分析


## 仓库介绍

### 地质学相关研究

该分类包含与地质图像分析相关的项目，致力于利用深度学习技术提取和分析地质数据。


#### [GeoDeepGenerativePrior](https://github.com/QUST-SmartData/GeoDeepGenerativePrior)

- **论文方向**: 电测井图像修复

- **论文标题**: *Prior-Guide Adaptive Gan Method for Various Borehole Image Inpainting*

- **论文简介**: 我们提出了一种深度学习方法，利用生成对抗网络（GAN）和特征提取融合模块，增强测井图像修复的连续性和完整性，有效提取裂缝、砾石结构和细粒纹理特征，从而提升地质构造分析的准确性和鲁棒性。

- **论文期刊**: `GEOPHYSICS, 中科院SCI 2 区 (TOP)`

- **论文地址**: [paper](https://doi.org/10.1190/geo2023-0418.1)



#### [FPEM-GAN](https://github.com/QUST-SmartData/FPEM-GAN)

- **论文方向**: 电测井图像修复

- **论文标题**: *Efficient Image Inpainting of Microresistivity Logs: A DDPM-Based Pseudo-Labeling Approach with FPEM-GAN*

- **论文简介**: 我们提出了一种深度学习方法，通过伪标签训练、透视增强模块和SM-Unet鉴别器，有效修复测井图像中的缺失区域，尤其提高了高角度裂缝和细粒纹理特征的重建质量，同时降低了计算成本。

- **论文期刊**: `COMPUTERS & GEOSCIENCES, 中科院SCI 2 区`

- **论文状态**: `Minor Revision`



#### [ADA-PGGAN](https://github.com/QUST-SmartData/ADA-PGGAN)

- **论文方向**: 3D重建

- **论文标题**: *For Any Two Arbitrary Slices from One Digital Rock , Its Twins Can be Fast Stably Reconstructed: A Novel Integrated Model of RVION with ADA-PGGAN*

- **论文简介**: 我们基于生成模型GAN提出了一种新颖的特征分布学习和自适应数据增强框架，成功地在数据稀缺环境中重建高质量的大规模 3D 数字岩石，并通过多种指标验证了其准确性和一致性。

- **论文期刊**: `COMPUTERS & GEOSCIENCES, 中科院SCI 2 区`

- **论文状态**: `With the Editor`



#### [DigitalRockConstruction](https://github.com/QUST-SmartData/DigitalRockConstruction)

- **论文方向**: 3D重建

- **论文标题**: *Multi-scale Reconstruction of 3D Digital Rock by Fusing Critical Information of Fine Scale with Framework of Large Scale: A Novel Approach*

- **论文简介**: 我们提出了一种新的生成模型框架，通过两个网络整合粗尺度和精细尺度信息，有效地建模多孔介质的多尺度结构，提升了数字岩石的重建效率和实用性。

- **论文期刊**: `Applied Intelligence, 中科院SCI 2 区`

- **论文状态**: `With the Editor`



#### [DTSS](https://github.com/QUST-SmartData/DTSS)

- **论文方向**: 3D矿物分割

- **论文标题**: *A Novel Workflow of  Segmentation for Finer Mineral Distingished: AttentionGAN-Swin-Transformer Fused Network*

- **论文简介**: 我们提出的 DTSS 工作流结合了 AttentionGAN 和 Swin Transformer，通过有效的域转换和图像分割，实现了对复杂岩石图像中矿物特征的精准识别。

- **论文期刊**: `Marine and Petroleum Geology, 中科院SCI 2 区 (TOP)`

- **论文状态**: `Waiting for submission`



#### [UDAFractureSeg](https://github.com/QUST-SmartData/UDAFractureSeg)

- **论文方向**: 2D裂缝分割

- **论文标题**: *Unsupervised Domain Adaptation Based Fracture Segmentation Method for Core CT Images*

- **论文简介**: 我们提出了一种基于无监督域适应的页岩裂缝自适应分割方法，结合风格迁移和协作学习，提高了在不同地质来源的岩心 CT 图像中裂缝分割的准确性和鲁棒性。

- **论文期刊**: `Applied Intelligence, 中科院SCI 2 区`

- **论文状态**: `Submitted`



#### [FractureSeg3D](https://github.com/QUST-SmartData/FractureSeg3D)

- **论文方向**: 3D裂缝分割

- **论文标题**: *Connectivity-Aware 3D Fracture Segmentation Method for Core CT Images*

- **论文简介**: 我们提出了一种新的 3D 岩心 CT 图像裂缝分割方法，利用 3D 多层 Transformer 网络捕获远程依赖和空间连续性特征，并结合动态权重和多尺度上下文感知融合，显著提升了对裂缝空间结构连通性的识别效果。

- **论文期刊**: `Expert Systems With Applications, 中科院SCI 1 区 (TOP)`

- **论文状态**: `Required Reviews Completed`



#### [SemSR](https://github.com/QUST-SmartData/SemSR)

- **论文方向**: 2D超分辨

- **论文标题**: *A Super-resolution Framework with Semantic Guidance for Restoring Pore-Solid Interface Roughness to Enhance the Accuracy of Digital Rock Transport Properties*

- **论文简介**: 我们提出了一种基于生成对抗网络的超分辨率方法，结合语义共享机制和模糊噪声，以改善孔壁特征的恢复，克服传统方法在处理低分辨率图像时的局限性，从而提高模型在复杂地质特征下的泛化能力。

- **论文期刊**: `Engineering Applications of Artificial Intelligence, 中科院SCI 2 区 (TOP)`

- **论文状态**: `Under Review`






### 医学相关研究
该分类包含与医学图像处理相关的项目，专注于提高医学图像分析的准确性和效率。

#### [CXRClassification](https://github.com/QUST-SmartData/CXRClassification)

- **论文方向**: 多标签疾病分类

- **论文标题**: *Multi-label Chest X-ray Image Classification Based on Long-range Dependencies Capture and Label Relationships Learning*

- **论文简介**: 我们提出了一种结合大核卷积和图卷积网络的 CNN 方法，通过解剖分割和标签共现关系，提升了胸部 X 射线图像的疾病诊断准确性。

- **论文期刊**: `Biomedical Signal Processing and Control, 中科院SCI 2 区`

- **论文状态**: `Decision in Process`



#### [FSTI-GAN](https://github.com/QUST-SmartData/FSTI-GAN)


- **论文方向**: 多模态医学图像修复

- **论文标题**: *FSTI-GAN: Fusion of Structural and Textural Information (FSTI) in Generative Adversarial Network (GAN) to Improve Medical Image Inpainting*

- **论文简介**: 我们提出了一种改进的双流并行嵌入网络，通过分阶段进行结构重建和纹理重建，利用FSTI Block实现结构和纹理信息的全局一致性，增强上下文推理能力，从而提高测井图像的修复质量，有效解决不良结构和纹理信息对修复结果的影响。

- **论文期刊**: `IEEE Transactions on Medical Imaging, 中科院SCI 1 区`

- **论文状态**: `Waiting for submission`




## 语言和工具

<p>
  <img width="30%" src="https://www.vectorlogo.zone/logos/python/python-ar21.svg">
  <img width="30%" src="https://www.vectorlogo.zone/logos/numpy/numpy-ar21.svg">
  <img width="30%" src="https://www.vectorlogo.zone/logos/opencv/opencv-ar21.svg">
  
  <br />
  <img width="30%" src="https://www.vectorlogo.zone/logos/pytorch/pytorch-ar21.svg">
  <img width="30%" src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-ar21.svg">
  <img width="30%" src="https://www.vectorlogo.zone/logos/jupyter/jupyter-ar21.svg">
  <br />
  <img width="30%" src="https://www.vectorlogo.zone/logos/git-scm/git-scm-ar21.svg">
  <img width="30%" src="https://www.vectorlogo.zone/logos/github/github-ar21.svg">
  <img width="30%" src="https://www.vectorlogo.zone/logos/visualstudio_code/visualstudio_code-ar21.svg">

</p>


## 统计信息

<img width="95%" src="https://github-readme-stats.vercel.app/api?username=QUST-SmartData&theme=ambient_gradient&show_icons=true&hide_border=true">

<img width="95%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=QUST-SmartData&hide=jupyter%20notebook&show_icons=true&hide_border=true&layout=donut&theme=ambient_gradient">

## 联系我们

如有问题或合作意向，请联系团队负责人 [王鑫](mailto:lex.wangx@qust.edu.cn) 。
