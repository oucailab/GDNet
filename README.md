


# 🚀 Synthetic Aperture Radar Image Change Detection Based on Global Dynamic Context-Aware Network, IEEE JSTARS 2026

<br>
<p align="center">
  🖐😭🤚 🌟 If this work is useful to you, please give this repository a Star! 🌟 🖐😭🤚
</p>

# 🔥 Overview

<div align="center">
    <img src="https://gaopursuit.oss-cn-beijing.aliyuncs.com/img/2026/ScreenShot_2026-06-21_130443_575.jpg" width="850" alt="Overview">
</div>

<br>

Convolutional neural networks (CNNs) have been extensively and successfully applied to the task of synthetic aper ture radar (SAR) image change detection. However, conventional convolutional layers are inherently limited by their local receptive fields, which mainly capture spatially localized patterns while neglecting the global context that is often crucial for accurately distinguishing subtle or large-scale changes in SAR imagery. Moreover, developing robust and stable detection models in this domain remains particularly challenging due to the scarcity of annotated training samples, which frequently lead to overfitting and unstable convergence during training. To address these limitations, we propose a novel Global Dynamic Context-Aware Network (GDNet) specifically tailored for SAR image change detection. At the core of our approach lies a novel global dynamic convolution module, which adaptively modulates convolution kernel weights according to the global semantic information extracted from the input features. By dynamically incorporating long-range dependencies, this mechanism enables the network to integrate both local detail and global context, thus improving its ability to detect diverse change patterns. In addition, we intro duce a carefully designed two-stage Mixup strategy for model training. Unlike conventional single-stage Mixup, our two-stage design generates more diverse and informative training samples, effectively regularizing the model and yielding more stable and reliable classification results even under limited data scenarios. Extensive experiments on three SAR datasets demonstrate the superiority of the proposed GDNet compared to other state-of the-art methods. These findings highlight the potential of global dynamic modeling and advanced data augmentation strategies for advancing SAR image interpretation.

dataset: https://drive.google.com/drive/folders/1xXbcqJzfzBnMZbkIdcq0cIR5ElEsqQyz?usp=sharing
# 📟 Contact

If you have any other questions, feel free to contact me at gaofeng@ouc.edu.cn .  
