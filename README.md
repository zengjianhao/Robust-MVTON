<div align="center">

<h1>Robust-MVTON: Learning Cross-Pose Feature Alignment and Fusion for Robust Multi-View Virtual Try-On</h1>

<div>
    <a href="https://scholar.google.com/citations?user=sshKuUMAAAAJ&hl=zh-CN" target="_blank">Nannan Zhang</a><sup>1*</sup>
    <a href="https://williamium3000.github.io/" target="_blank">Yijiang Li</a><sup>3*</sup>
    <a href="https://dongdu3.github.io/" target="_blank">Dong Du</a><sup>2†</sup>
    <a href="https://github.com/Zheng-Chong" target="_blank">Zheng Chong</a><sup>4</sup>
    <a href="https://taited.github.io/" target="_blank">Zhengwentai Sun</a><sup>1</sup>
    <a href="https://zengjianhao.github.io/" target="_blank">Jianhao Zeng</a><sup>5</sup>
    <a href="https://scholar.google.com.hk/citations?hl=zh-CN&user=tvjQ7GUAAAAJ" target="_blank">Yusheng Dai</a><sup>6</sup>
</div>

<div>
    <a href="https://xiezhy6.github.io/" target="_blank">Zhenyu Xie</a><sup>4</sup>
    Hairui Zhu<sup>1</sup>
    <a href="https://gaplab.cuhk.edu.cn/pages/people" target="_blank">Xiaoguang Han</a><sup>1†</sup>
</div>


<div>
    <sup>1</sup>CUHKSZ &emsp; <sup>2</sup>NJUST &emsp; <sup>3</sup>UCSD &emsp; <sup>4</sup>SYSU &emsp; <sup>5</sup>Westlake University &emsp; <sup>6</sup>USTC &emsp; 
</div>

[[Paper]](https://openaccess.thecvf.com/content/CVPR2025/papers/Zhang_Robust-MVTON_Learning_Cross-Pose_Feature_Alignment_and_Fusion_for_Robust_Multi-View_CVPR_2025_paper.pdf)  &emsp; [[Project]](https://zengjianhao.github.io/Robust-MVTON/)

</div>



## Abstract

> This paper tackles the emerging challenge of multi-view virtual try-on, utilizing both front- and back-view clothing images as inputs. Extending frontal try-on methods to a multi-view context is not straightforward. Simply concatenating the two input views or encoding their features for a generative model, such as a diffusion model, often fails to produce satisfactory results. The main challenge lies in effectively extracting and fusing meaningful clothing features from these input views. Existing explicit warpingbased methods, which establish direct correspondence between input and target views, tend to introduce artifacts, particularly when there is a significant disparity between the input and target views. Conversely, implicit encodingbased methods often lose spatial information about clothing, resulting in outputs that lack detail. To overcome these challenges, we propose Robust-MVTON, an end-toend method for robust and high-quality multi-view try-ons. Our approach introduces a novel cross-pose feature alignment technique to guide the fusion of clothing features and incorporates a newly designed loss function for training. With the fused multi-scale clothing features, we employ a coarse-to-fine diffusion model to generate realistic and detailed results. Extensive experiments conducted on the Deepfashion and MPV datasets affirm the superiority of our method, achieving state-of-the-art performance.

## Citing

```
@inproceedings{zhang2025robust,
    title={Robust-MVTON: Learning Cross-Pose Feature Alignment and Fusion for Robust Multi-View Virtual Try-On},
    author={Zhang, Nannan and Li, Yijiang and Du, Dong and Chong, Zheng and Sun, Zhengwentai and Zeng, Jianhao and Dai, Yusheng and Xie, Zhengyu and Zhu, Hairui and Han, Xiaoguang},
    booktitle={Proceedings of the Computer Vision and Pattern Recognition Conference},
    pages={16029--16039},
    year={2025}
}
       
```
