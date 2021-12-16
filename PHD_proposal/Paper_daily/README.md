# Paper Reading



##  insights

Res2Net的想法是否可以推广至decoder，这种想法和transformer中的多头注意力机制非常相似。

res2net and resnetxt


## Memory

## ResNeSt

## Aggregated Residual Transformations for Deep Neural Networks(ResNeXt)

## Res2Net: A New Multi-scale Backbone Architecture
[知乎解析](https://www.zhihu.com/search?type=content&q=resxnet)
![](https://github.com/LuShuaie/OpenCV/blob/main/PHD_proposal/Paper_daily/images/Res2Net.png)

**Abstract**—Representing features at multiple scales is of great importance for numerous vision tasks. Recent advances in backbone convolutional neural networks (CNNs) continually demonstrate stronger multi-scale representation ability, leading to consistent performance gains on a wide range of applications. However, most existing methods represent the multi-scale features in a layer wise manner. In this paper, we propose a novel building block for CNNs, namely Res2Net, by constructing hierarchical residual-like connections within one single residual block. The Res2Net represents multi-scale features at a granular level and increases the range of receptive fields for each network layer. The proposed Res2Net block can be plugged into the state-of-the-art backbone CNN models, e.g., ResNet, ResNeXt, and DLA. We evaluate the Res2Net block on all these models and demonstrate consistent performance gains over baseline models on widely-used datasets, e.g., CIFAR-100 and ImageNet. Further ablation studies and experimental results on representative computer vision tasks, i.e., object detection, class activation mapping, and salient object detection, further verify the superiority of the Res2Net over the state-of-the-art baseline methods. The source code and trained models are available on https://mmcheng.net/res2net/.







## BSDA-Net: A Boundary Shape and Distance Aware Joint Learning Framework for Segmenting and Classifying OCTA Images

![](https://github.com/LuShuaie/OpenCV/blob/main/PHD_proposal/Paper_daily/images/BSDA-Net.png)

**Abstract.** Optical coherence tomography angiography (OCTA) is a novel non-invasive imaging technique that allows visualizations of vasculature and foveal avascular zone (FAZ) across retinal layers. Clinical researches suggest that the morphology and contour irregularity of FAZ are important biomarkers of various ocular pathologies. Therefore, precise segmentation of FAZ has great clinical interest. Also, there is no existing research reporting that FAZ features can improve the performance of deep diagnostic classification networks. In this paper, we propose a novel multi-level boundary shape and distance aware joint learning framework, named BSDA-Net, for FAZ segmentation and diagnostic classification from OCTA images. Two auxiliary branches, namely boundary heatmap regression and signed distance map reconstruction branches, are constructed in addition to the segmentation branch to improve the segmentation performance, resulting in more accurate FAZ contours and fewer outliers. Moreover, both low-level and high-level features from the aforementioned three branches, including shape, size, boundary, and signed directional distance map of FAZ, are fused hierarchically with features from the diagnostic classifier. Through extensive experiments, the proposed BSDA-Net is found to yield state-of-the-art segmentation and classification results on the OCTA-500, OCTAGON, and FAZID datasets.



## Swin Transformer: Hierarchical Vision Transformer using Shifted Windows
![swin](https://github.com/LuShuaie/OpenCV/blob/main/PHD_proposal/Paper_daily/images/swin_transformer.png)

- [ ] What is the difference between Patch Partition and Patch Merging ?
- [ ] How is the shift window implemented ?
- [ ] Masked mask is 0 or not? Why?
