# SmartData

欢迎来到我们的GitHub团队主页！

我们团队致力于推动地质和医学等领域的图像分析研究，通过深度学习和计算机视觉技术解决实际问题。


## 研究方向
我们专注于以下研究方向：

- 🖼️ 计算机视觉
- 🧠 深度学习
- 🤖 机器学习
- 🌍 地质图像分析
- 🏥 医学图像分析


## 仓库介绍

### 地质学相关研究

该分类包含与地质图像分析相关的项目，致力于利用深度学习技术提取和分析地质数据。

#### [FPEM-GAN](https://github.com/QUST-SmartData/FPEM-GAN)

- **方向**：测井图像修复

- **论文标题**: *todo*

- **简介**: todo

- <details>
    <summary>论文摘要</summary>
    todo
</details>

- **论文地址**: 在审


#### [GeoDeepGenerativePrior](https://github.com/QUST-SmartData/GeoDeepGenerativePrior)

- **方向**：测井图像修复

- **论文标题**: *todo*

- **简介**: todo

- <details>
    <summary>论文摘要</summary>
    todo
</details>

- **论文地址**: 在审


#### [ADA-PGGAN](https://github.com/QUST-SmartData/ADA-PGGAN)

- **方向**：3D重建

- **论文标题**: *Multi-scale Reconstruction of 3D Digital Rock by Fusing Critical Information of Fine Scale with Framework of Large Scale: A Novel Approach*

- **简介**: 我们基于生成模型GAN提出了一种新颖的特征分布学习和自适应数据增强框架，成功地在数据稀缺环境中重建高质量的大规模 3D 数字岩石，并通过多种指标验证了其准确性和一致性。

- <details>
    <summary>论文摘要</summary>
    Amounts of digital rock samples are crucial for studying pore properties. However, it is currently challenging due to equipment limitations or cost considerations. To address this issue, we propose sorts of reconstruction solutions under Data-Scarce Scenarios based on latent inversion predict from proposed generative model. Firstly, A novel featured distribution learning model was proposed though O-ResNet50 network training for prepared inversion. During inversion, the latent vectors predict from mentioned learning model is prepared to interpolate into latent space of given images. To stably produce high-quality images, Adaptive Data Augmentation Progressive Growing Generative Adversarial Network (ADA-PGGAN) is proposed, which includes a mechanism to supervise discriminator's overfitting and automatically adjust levels of data augmentation. Subsequently, interpolated latent vectors are input into the generator to progressively increase image resolution and reconstruct large-scale 3D digital rocks.Finally, evaluations using various metrics were conducted in both 2D and 3D on our results. The Sliced Wasserstein Distance (SWD) was used to assess our proposed data augmentation operation. The majority of SWD values remained below 0.01, with further decreases as resolution increased. Furthermore, generated images accurately exhibited core characteristics.We also evaluated our results in 3D with corresponding metrics, structural properties to indicate consistency with given samples.
</details>

- **论文地址**: 在审



#### [DigitalRockConstruction](https://github.com/QUST-SmartData/DigitalRockConstruction)

- **方向**：3D重建

- **论文标题**: *Multi-scale Reconstruction of 3D Digital Rock by Fusing Critical Information of Fine Scale with Framework of Large Scale: A Novel Approach*

- **简介**: 我们提出了一种新的生成模型框架，通过两个网络整合粗尺度和精细尺度信息，有效地建模多孔介质的多尺度结构，提升了数字岩石的重建效率和实用性。

- <details>
    <summary>论文摘要</summary>
    The digital modeling of microstructure is crucial for investigating the physical and transport properties of porous media. Multi-scale modeling of porous media can effectively characterize both coarse-scale and fine-scale information in high-resolution 3D pore structure models with a large field of view (FoV). Currently, there is a lack of comprehensive framework studies on various subscale components that can be integrated with existing scales, such as micropor, mineral-clay, microcracks, etc. To tackle this issue, we propose a novel framework that utilizes combinations of generative models. One of which focuses on predicting coarse-scale structures, while another network fills in fine-scale information to generate combinate-scale structures.
    In the first network, WGAN is selected as basic training network, inputing 3D noises into the generative network and producing images of coarse-scale as output under the supervision of an adversarial network. We make a datasets designed for the adversarial network which only contains coarse-scale images. The other generative network is built for being injected fine-scale information into the coarsescale 3D images generated through the first generator. During the process, we input two-dimensional high-resolution imageswith fine-scale information into the discriminator to generate a multi-scale images. Taking anisotropy into consideration, loss function combinations are presented to deal with. We conduct a case study on a multi-scale digital rock reconstructed of intra-grain pores into inter-grain pores through our approach. Through qualitative and quantitative comparison, it is demonstrated that our method is more practical and efficient than the latest numerical reconstruction methods.
</details>

- **论文地址**: 在审


#### [HQJGAN](https://github.com/QUST-SmartData/HQJGAN)

- **方向**：3D矿物分割

- **论文标题**: *A Novel Workflow of  Segmentation for Finer Mineral Distingished ：AttentionGAN-Swin-Transformer Fused Network*

- **简介**: 我们提出的 DTSS 工作流结合了 AttentionGAN 和 Swin Transformer，通过有效的域转换和图像分割，实现了对复杂岩石图像中矿物特征的精准识别。

- <details>
    <summary>论文摘要</summary>
    We proposed a workflow - DTSS (Domain Transformation and Semantic Segmentation): first use AttentionGAN to convert the CT image domain to the (SEM) scanning electron microscope image domain, and then use Swin Transformer to perform image segmentation. By introducing attention masks and content masks, AttentionGAN can more effectively learn the mapping relationship between the two domains, thereby generating images in the corresponding target domain.
    On the basis of domain transformation, we further use Swin-Transformer for image segmentation. Swin-Transformer is a Transformer-based model that efficiently processes image data through a self-attention mechanism. Compared with traditional convolutional neural networks (CNN), Swin-Transformer's global receptive field and stronger modeling capabilities give it significant advantages when processing complex, multi-mineral rock images. Swin-Transformer is able to capture long-range dependencies in images, which is particularly important for identifying and segmenting mineral dependencies in rocks.
</details>

- **论文地址**: 在审


#### [UDAFractureSeg](https://github.com/QUST-SmartData/UDAFractureSeg)

- **方向**：2D裂缝分割

- **论文标题**: *Unsupervised Domain Adaptation Based Fracture Segmentation Method for Core CT Images*

- **简介**: 我们提出了一种基于无监督域适应的页岩裂缝自适应分割方法，结合风格迁移和协作学习，提高了在不同地质来源的岩心 CT 图像中裂缝分割的准确性和鲁棒性。

- <details>
    <summary>论文摘要</summary>
    Segmentation of fractures in Computed Tomography (CT) images of cores is crucial in the analysis of rock physical properties. While supervised learning methods have shown significant success in fracture detection, their performance heavily depends on large labeled datasets. However, labeling images is time-consuming and prone to human error. Moreover, these methods often struggle to effectively generalize to unseen datasets due to differences among source and target images. To address this issue, this paper proposes an unsupervised domain-based adaptive segmentation method for shale fractures. The method consists of two parts: StyleFlow-based Style Transfer and Collaborative Learning based Multi-source Domain Adaptation. Firstly, an image style transfer method is introduced to align the images, reducing the difference in gray scale and noise distribution between the source and target domains. Secondly, the Collaborative Learning based Multi-source Domain Adaptation comprises three modules: a segmentation network module, a domain adaptation module, and a collaborative learning module. The segmentation network adopts a modified U-Net with a multi-scale attention mechanism introduced in the encoder part to capture fracture features at different scales in core. Channel and spatial attention mechanisms are also introduced in the decoder part to compensate for loss of spatial structure information caused by downsampling. The domain adaptive module recognizes inter-domain differences and adapts the model with discriminators and adversarial learning to reduce differences in feature or class distributions between source and target domains. The collaborative learning module further corrects unlabeled target domain data using model-generated pseudo-labels, thus improving domain adaptation accuracy. In this way, the segmentation knowledge learned from pavements can be transferred to the core CT image, which enables the adaptive segmentation of core fractures. We conducted experiments on shale datasets from two different geological sources and compared them with existing methods. The results demonstrate that the proposed method exhibits high accuracy and robustness in the segmentation of fractures.
</details>

- **论文地址**: 在审


#### [FractureSeg3D](https://github.com/QUST-SmartData/FractureSeg3D)

- **方向**：3D裂缝分割

- **论文标题**: *Connectivity-Aware 3D Fracture Segmentation Method for Core CT Images*

- **简介**: 我们提出了一种新的 3D 岩心 CT 图像裂缝分割方法，利用 3D 多层 Transformer 网络捕获远程依赖和空间连续性特征，并结合动态权重和多尺度上下文感知融合，显著提升了对裂缝空间结构连通性的识别效果。

- <details>
    <summary>论文摘要</summary>
    Accurately extracting the fracture structures from three-dimensional (3D) computed tomography (CT) images is essential for simulating and analyzing the physical properties of digital rocks. However, the heterogeneity within the rocks makes it difficult for threshold-based methods to identify blurred fracture boundaries. Furthermore, fractures have a complex spatial topological structure, resulting in existing slice-based segmentation methods ineffective in capturing spatial connectivity information. To address the above problems, a novel fracture segmentation method for 3D core CT images is proposed in this study. Firstly, we introduced a 3D multi-layer Transformer network to capture long-range dependence information and pixel spatial continuity features between adjacent layers.
    Then, we fed three axial slices into a 2D multi-layer Transformer network to extract anisotropic features from multi-views. Subsequently, these features are fed into the Gradient Boosting Decision Tree (GBDT) module, which is iteratively enhanced by weaker learners to obtain preliminary segmentation probability maps. To correct the contribution of these maps to the segmentation results, we add dynamic weights to each of them and adjust it by backpropagation of the loss function. Finally, a multi-scale context-aware fusion module fused spatial continuity features with these maps to obtain segmentation results. We compare it with other state-of-the-art methods and the experiment results demonstrate the superiority of our method in spatial structure connectivity of fracture.
</details>

- **论文地址**: 在审


#### [SemSR](https://github.com/QUST-SmartData/SemSR)

- **论文标题**: *Connectivity-Aware 3D Fracture Segmentation Method for Core CT Images*

- **简介**: 我们提出了一种基于生成对抗网络的超分辨率方法，结合语义共享机制和模糊噪声，以改善孔壁特征的恢复，克服传统方法在处理低分辨率图像时的局限性，从而提高模型在复杂地质特征下的泛化能力。

- <details>
    <summary>论文摘要</summary>
    The roughness of pore walls is a crucial factor in studying fluid flow within the pore space. Combining data from different imaging modalities and using deep learning-based super-resolution (SR) methods, a comprehensive view with intricate specific features would be obtained.The relationship between pore wall and pore space is typically representative of geological characterization, which distinguishes among different components. However, current SR methods often overlook geological component regions and incorporate various mechanisms that increase the model's weight and computational demands. To tackle these issues, we employ a Generative Adversarial Network and propose a semantic sharing mechanism to collaborate with the injection of geological characterization. In addition, matching low-resolution (LR) and high-resolution (HR) images is a major challenge. It is common practice to down-sample HR images to obtain pairs of LR images. However, the LR images obtained by these methods still contain lots of details, which weakens the model's generalization ability in real-world scenarios. Therefore, we developed a novel method that introduces intentional blurring noises and multi-sampling operations utilized during data augmentation. Finally, we compare our method with other state-of-the-art methods using proposed indicators to recover the true characteristics of the hole wall, proving the superiority of our method.
</details>

- **论文地址**: 在审


### 医学相关研究
该分类包含与医学图像处理相关的项目，专注于提高医学图像分析的准确性和效率。

#### [CXRClassification](https://github.com/QUST-SmartData/CXRClassification)
- 论文标题：*Multi-label Chest X-ray Image Classification Based on Long-range Dependencies Capture and Label Relationships Learning*

- **简介**: 我们提出了一种结合大核卷积和图卷积网络的 CNN 方法，通过解剖分割和标签共现关系，提升了胸部 X 射线图像的疾病诊断准确性。

- <details>
    <summary>论文摘要</summary>
    Diagnosing chest diseases from X-ray images using convolutional neural networks (CNNs) is an active area of research. However, existing methods mostly focus on extracting feature information from local regions for prediction, while ignoring the larger-scale image contextual information. Moreover, anatomical segmentation knowledge and co-occurrence relationships among labels, which are important for classification, are not fully utilized. To address the above problems, we proposed a method to capture long-range dependent information in chest X-ray images using a CNN with large kernel convolution. Furthermore, it captures the detailed features of the interest region through anatomical segmentation and builds the potential relationships of different diseases using a graph convolutional network (GCN). Firstly, we pre-trained UNet from a dataset with organ-level annotations for segmenting anatomical regions of interest in the images. Secondly, we build a four-stage backbone network using the large kernel attention (LKA) mechanism and superimpose anatomically segmented regions on the feature maps of each stage to obtain different scales of feature maps for the regions of interest. Thirdly, we utilized a GCN to obtain a co-occurrence matrix representing the potential relationships between all disease labels in the training dataset. Finally, we get the disease diagnosis by combining the label co-occurrence matrix and the visual feature maps. We experimentally show that our proposed method achieves excellent AUC scores of 91.5%, 84.5%, and 82.5% on three publicly available CXR datasets–NIH, Stanford CheXpert, and MIMIC-CXR-JPG, respectively.
</details>

- **论文地址**: 在审


#### [FSTI-GAN](https://github.com/QUST-SmartData/FSTI-GAN)
- 论文标题：*todo*

- **简介**: todo

- <details>
    <summary>论文摘要</summary>
    todo
</details>

- **论文地址**: 在审


## 语言和工具

<!-- Your github readme stats
You can use this api: https://github.com/anuraghazra/github-readme-stats
-->
<p>
  <!-- Your languages and tools. Be careful with the alignment. 
  You can use this sites to get logos: https://www.vectorlogo.zone or https://simpleicons.org/
  -->
  <code><img width="30%" src="https://www.vectorlogo.zone/logos/python/python-ar21.svg"></code>
  <code><img width="30%" src="https://www.vectorlogo.zone/logos/numpy/numpy-ar21.svg"></code>
  <code><img width="30%" src="https://www.vectorlogo.zone/logos/pytorch/pytorch-ar21.svg"></code>
  <br />
  <code><img width="30%" src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-ar21.svg"></code>
  <code><img width="30%" src="https://www.vectorlogo.zone/logos/jupyter/jupyter-ar21.svg"></code>
  <code><img width="30%" src="https://www.vectorlogo.zone/logos/json/json-ar21.svg"></code>
  <br />
  <code><img width="30%" src="https://www.vectorlogo.zone/logos/mysql/mysql-ar21.svg"></code>
  <code><img width="30%" src="https://www.vectorlogo.zone/logos/google_cloud/google_cloud-ar21.svg"></code>
  <code><img width="30%" src="https://www.vectorlogo.zone/logos/docker/docker-ar21.svg"></code>
  <br />
  <code><img width="30%" src="https://www.vectorlogo.zone/logos/git-scm/git-scm-ar21.svg"></code>
  <code><img width="30%" src="https://www.vectorlogo.zone/logos/github/github-ar21.svg"></code>
  <code><img width="30%" src="https://www.vectorlogo.zone/logos/visualstudio_code/visualstudio_code-ar21.svg"></code>
    

</p>


## 统计信息

<img width="95%" src="https://github-readme-stats.vercel.app/api?username=QUST-SmartData&theme=ambient_gradient&show_icons=true&hide_border=true">

<img width="95%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=QUST-SmartData&hide=jupyter%20notebook&show_icons=true&hide_border=true&layout=donut">

## 联系我们

如有问题或合作意向，请联系团队负责人 [王鑫](mailto:lex.wangx@qust.edu.cn) 。
