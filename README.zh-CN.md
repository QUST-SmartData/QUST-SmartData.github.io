<div align=center>

[English](README.en-US.md) | [简体中文](README.zh-CN.md)

</div>


# <div align=center>SmartData</div>

<div align=center><img src ="logo.jpg"/></div>

<br/>

<div align=center>

欢迎来到我们的GitHub团队主页！

团队致力于推动地质和医学等领域的图像分析研究，通过深度学习和计算机视觉技术解决实际问题。
</div>



## 研究方向
我们专注于以下研究方向: 

- 🖼️ 计算机视觉
- 🧠 深度学习
- 🤖 机器学习
- 🌍 地质学图像分析
- 🏥 医学图像分析
- ⚙️ AI技术的工业界应用


## 团队成员


<div align="center">

| <img src="team-members/Xin%20Wang.jpg" width="100"/> |
|:-----------------------------------------------------:|
| **Xin Wang**  <br> 王鑫于2013年获得中国石油大学博士学位。现任中国青岛科技大学信息科学与技术学院副教授。2017年至2020年，他担任青岛市孔隙尺度成像实验室主任，2018年至2020年间，他还担任山东科学院国际问题研究生院博士生导师。他曾是伦敦帝国理工学院、赫里奥特瓦特大学和俄罗斯科学院远东分院的访问科学家。2016年和2017年，他参加了与俄罗斯和日本的国家联合科学考察队。他的研究方向包括二维和三维图像处理、计算机视觉和人工智能。   |

<br>

| <img src="team-members/Zhaoyan Zhong.jpg" width="100"/> | <img src="team-members/Qijie Huang.jpg" width="100"/> | <img src="team-members/Xiangxin Zhao.jpg" width="100"/>  |
|:-------------------------------------------------------:|:-------------------------------------------------------:|:-------------------------------------------------------:|
| **Zhaoyan Zhong** <br> 电测井图像修复 | **Qijie Huang** <br> 矿物分割 | **Xiangxin Zhao** <br> 地质裂缝分割 |

<br>


| <img src="team-members/Xintao Mu.jpg" width="100"/>  | <img src="team-members/Yanxia Liu.jpg" width="100"/> | <img src="team-members/Yingqi Zhang.jpg" width="100"/> | <img src="team-members/Liguo Niu.jpg" width="100"/>  | <img src="team-members/Xuefeng Gui.jpg" width="100"/>  | <img src="team-members/Shuyang Fan.jpg" width="100"/> |
|:-----------------------------------------------------:|:-----------------------------------------------------:|:-----------------------------------------------------:|:-----------------------------------------------------:|:-----------------------------------------------------:|:-----------------------------------------------------:|
| **Xintao Mu** <br> 多模态医学图像修复 | **Yanxia Liu** <br> 3D岩心重建 | **Yingqi Zhang** <br> 3D岩心重建 | **Liguo Niu** <br> 2D岩心超分辨 | **Xuefeng Gui** <br> 工业缺陷检测 | **Shuyang Fan** <br> 多孔介质生成 |


<br>

<img src="team-members/teams.jpg" width="600"/>

<br>




<br>

<img src="team-members/welcome.png" width="600"/>

24级研究生

| <img src="team-members/Jia Wang.jpg" width="100"/> | <img src="team-members/Jiawei Li.jpg" width="100"/> | <img src="team-members/Jialu Chen.jpg" width="100"/> | <img src="team-members/Lidong Zhou.jpg" width="100"/> | <img src="team-members/Yang Li.jpg" width="100"/> |
|:-----------------------------------------------------:|:-----------------------------------------------------:|:-----------------------------------------------------:|:-----------------------------------------------------:|:-----------------------------------------------------:|
| **Jia Wang** | **Jiawei Li** | **Jialu Chen** | **Lidong Zhou** | **Yang Li** |

<br>

访问学生

| <img src="team-members/Ruixi Jing.jpg" width="100"/> | <img src="team-members/Fuzhi Wan.jpg" width="100"/> |
|:-----------------------------------------------------:|:-----------------------------------------------------:|
| **Ruixi Jing** | **Fuzhi Wan** |


<br>

团队活动照片

<img src="team-activities/In Aspen.jpg" width="600"/>
<img src="team-activities/In HWU,Edingburg.jpg" width="600"/>
<img src="team-activities/in NTNU,Trondheim.jpg" width="600"/>
<img src="team-activities/with Martin in ICL.jpg" width="600"/>
<img src="team-activities/帝国理工时期.jpg" width="600"/>
<img src="team-activities/聚餐1.jpg" width="600"/>
<img src="team-activities/聚餐2.jpg" width="600"/>

<br>

</div>



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

- **论文地址**: [paper](https://doi.org/10.1016/j.cageo.2024.105812)



#### [ADA-PGGAN](https://github.com/QUST-SmartData/ADA-PGGAN)

- **论文方向**: 3D岩心重建

- **论文标题**: *For Any Two Arbitrary Slices from One Digital Rock , Its Twins Can be Fast Stably Reconstructed: A Novel Integrated Model of RVION with ADA-PGGAN*

- **论文简介**: 我们基于生成模型GAN提出了一种新颖的特征分布学习和自适应数据增强框架，成功地在数据稀缺环境中重建高质量的大规模 3D 数字岩石，并通过多种指标验证了其准确性和一致性。

- **论文期刊**: `COMPUTERS & GEOSCIENCES, 中科院SCI 2 区`

- **论文状态**: `Accepted`



#### [DigitalRockConstruction](https://github.com/QUST-SmartData/DigitalRockConstruction)

- **论文方向**: 3D岩心重建

- **论文标题**: *Multi-scale Reconstruction of 3D Digital Rock by Fusing Critical Information of Fine Scale with Framework of Large Scale: A Novel Approach*

- **论文简介**: 我们提出了一种新的生成模型框架，通过两个网络整合粗尺度和精细尺度信息，有效地建模多孔介质的多尺度结构，提升了数字岩石的重建效率和实用性。

- **论文期刊**: `COMPUTERS & GEOSCIENCES, 中科院SCI 2 区`

- **论文状态**: `With the Editor`



#### [DTSS](https://github.com/QUST-SmartData/DTSS)

- **论文方向**: 3D岩心矿物分割

- **论文标题**: *A Novel Workflow of  Segmentation for Finer Mineral Distingished: AttentionGAN-Swin-Transformer Fused Network*

- **论文简介**: 我们提出的 DTSS 工作流结合了 AttentionGAN 和 Swin Transformer，通过有效的域转换和图像分割，实现了对复杂岩石图像中矿物特征的精准识别。

- **论文期刊**: `Marine and Petroleum Geology, 中科院SCI 2 区 (TOP)`

- **论文状态**: `Waiting for submission`



#### [UDAFractureSeg](https://github.com/QUST-SmartData/UDAFractureSeg)

- **论文方向**: 2D岩心裂缝分割

- **论文标题**: *Unsupervised Domain Adaptation Based Fracture Segmentation Method for Core CT Images*

- **论文简介**: 我们提出了一种基于无监督域适应的页岩裂缝自适应分割方法，结合风格迁移和协作学习，提高了在不同地质来源的岩心 CT 图像中裂缝分割的准确性和鲁棒性。

- **论文期刊**: `Expert Systems With Applications, 中科院SCI 1 区 (TOP)`

- **论文地址**: [paper](https://doi.org/10.1016/j.eswa.2024.125857)



#### [FractureSeg3D](https://github.com/QUST-SmartData/FractureSeg3D)

- **论文方向**: 3D岩心裂缝分割

- **论文标题**: *Connectivity-Aware 3D Fracture Segmentation Method for Core CT Images*

- **论文简介**: 我们提出了一种新的 3D 岩心 CT 图像裂缝分割方法，利用 3D 多层 Transformer 网络捕获远程依赖和空间连续性特征，并结合动态权重和多尺度上下文感知融合，显著提升了对裂缝空间结构连通性的识别效果。

- **论文期刊**: `Engineering Applications of Artificial Intelligence, 中科院SCI 2 区 (TOP)`

- **论文状态**: `With the Editor`



#### [SemSR](https://github.com/QUST-SmartData/SemSR)

- **论文方向**: 2D岩心超分辨

- **论文标题**: *A Super-resolution Framework with Semantic Guidance for Restoring Pore-Solid Interface Roughness to Enhance the Accuracy of Digital Rock Transport Properties*

- **论文简介**: 我们提出了一种基于生成对抗网络的超分辨率方法，结合语义共享机制和模糊噪声，以改善孔壁特征的恢复，克服传统方法在处理低分辨率图像时的局限性，从而提高模型在复杂地质特征下的泛化能力。

- **论文期刊**: `Engineering Applications of Artificial Intelligence, 中科院SCI 2 区 (TOP)`

- **论文状态**: `Under Review`


#### [MLDM](https://github.com/QUST-SmartData/)

- **论文方向**: 多孔介质微结构生成

- **论文标题**: *Generation of Porous Micro-structure Based on Diffusion Model*

- **论文简介**: 我们提出了一种改进的扩散模型网络，通过分阶段进行结构重建和结构生成，利用自编码器的降维能力和扩散模型丰富的生成能力，降低扩散建模多样本的分辨率的同时，生成丰富的多孔结构。

- **论文期刊**: `pending`

- **论文状态**: `Manuscript Drafting`



#### [SurfaceDefectDetectionYolov8](https://github.com/QUST-SmartData/SurfaceDefectDetectionYolov8)

- **论文方向**: 工业缺陷检测

- **论文标题**: *Surface defect detection method based on Deep-Learning*

- **论文简介**: 在小目标检测过程中，针对由不同生成机制导致的相似缺陷问题，本文引入了一种融合空间注意力（SA）和坐标注意力（CA）的机制。我们设计了一个新的聚合与重分配网络模型，以解决小目标特征丢失的问题。同时，针对小目标检测中的边界损失问题，提出了一种新的DOS损失函数，以确保小目标位置偏差的平滑性，从而综合提升小目标检测效果。

- **论文期刊**: `pending`

- **论文状态**: `Manuscript Drafting`



### 医学相关研究
该分类包含与医学图像处理相关的项目，专注于提高医学图像分析的准确性和效率。

#### [CXRClassification](https://github.com/QUST-SmartData/CXRClassification)

- **论文方向**: 医学图像多标签疾病分类

- **论文标题**: *Multi-label Chest X-ray Image Classification Based on Long-range Dependencies Capture and Label Relationships Learning*

- **论文简介**: 我们提出了一种结合大核卷积和图卷积网络的 CNN 方法，通过解剖分割和标签共现关系，提升了胸部 X 射线图像的疾病诊断准确性。

- **论文期刊**: `Biomedical Signal Processing and Control, 中科院SCI 2 区`

- **论文地址**: [paper](https://doi.org/10.1016/j.bspc.2024.107018)




#### [FSTI-GAN](https://github.com/QUST-SmartData/FSTI-GAN)


- **论文方向**: 多模态医学图像修复

- **论文标题**: *FSTI-GAN: Fusion of Structural and Textural Information (FSTI) in Generative Adversarial Network (GAN) to Improve Medical Image Inpainting*

- **论文简介**: 我们提出了一种改进的双流并行嵌入网络，通过分阶段进行结构重建和纹理重建，利用FSTI Block实现结构和纹理信息的全局一致性，增强上下文推理能力，从而提高图像的修复质量，有效解决不良结构和纹理信息对修复结果的影响。

- **论文期刊**: `IEEE Transactions on Medical Imaging, 中科院SCI 1 区 (TOP)`

- **论文状态**: `Waiting for submission`



#### [CLECC](https://github.com/QUST-SmartData/)


- **论文方向**: 医学超声图像分类

- **论文标题**: *Application of a course learning strategy based on structural prior and Ebbinghaus forgetting curve for ultrasound gallbladder lesion classification*

- **论文简介**: 在超声图像中，由于胆囊组织与周围软组织在纹理特征上的高度相似性，传统的深度学习模型在胆囊病变的分类任务中面临挑战。为了解决这一问题，本文提出了一种结合结构先验和艾宾浩斯遗忘曲线的课程学习训练策略。从人类视觉敏锐度的发展启发，我们使用相对总变差（RTV）方法提取图像的结构先验，替代传统的高斯模糊处理，更有效地分离纹理和结构信息，引导模型关注关键的解剖结构特征。同时，基于艾宾浩斯遗忘曲线设计了课程学习策略，优化模型的学习过程，提升其对关键特征的记忆和判别能力。实验结果表明，该方法在提高胆囊病变分类的准确率和鲁棒性方面取得了显著的效果，为超声图像的自动诊断提供了有力支持。

- **论文期刊**: `IEEE Transactions on Medical Imaging, 中科院SCI 1 区 (TOP)`

- **论文状态**: `Waiting for submission`


### 工业界应用
该分类包含与AI模型相关的工业界应用项目，专注于过程自动化、创新驱动解决方案和客户体验增强。

#### [基于AI的市政设计软件辅助系统](https://github.com/QUST-SmartData/AICAD)

- **项目介绍**: 
本项目旨在于现有市政设计软件基础上，引入人工智能技术，以实现市政设计任务中的智能绘图功能，从而提高市政设计的效率和精准度。项目包括进行详细的需求分析、引入适用的AI技术、对AI模型的研究和训练、软件的开发与集成、以及项目总结和成果验收。

- **功能目标**: 
  - 路口识别与智能分图: 通过AI技术精准识别软件设计图中的关键道路路口，设计合理高效的分图方案，实现图纸划分。
  - 图框批量化替换：自动批量替换图纸图框，简化人工处理流程。
  - 文本输入自动化：自动化处理文本输入工作，减少人工操作耗时。
  - 批量化打印：实现设计图纸的批量打印，进一步提高工作效率。

- **成果展示**：

  ![成果展示](https://github.com/QUST-SmartData/AICAD/blob/main/img/1.png)




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

如有问题或合作意向，请联系团队负责人 [王鑫（03774@qust.edu.cn）](mailto:03774@qust.edu.cn) 。

<br>

<img src ="QRCode.png" width="300"/>