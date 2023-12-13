<div align="center">
<!-- <h1>NVEdit</h1> -->
<h3>Neural Video Fields Editing</h3>

[Shuzhou Yang](https://ysz2022.github.io/)<sup>1,2</sup>, [Chong Mou](https://scholar.google.com/citations?user=SYQoDk0AAAAJ&hl=zh-CN&oi=ao)<sup>1</sup>, [Jiwen Yu](https://vvictoryuki.github.io/website/)<sup>1</sup>, Yuhan Wang<sup>1,2</sup>, [Xiandong Meng](https://orcid.org/0000-0002-1295-769X)<sup>2</sup>, [Jian Zhang](https://jianzhang.tech/)<sup>1*</sup>

<sup>1</sup> SECE, Peking University, <sup>2</sup> Peng Cheng Laboratory

[![arXiv](https://img.shields.io/badge/arXiv-<Coming_Soon>-<COLOR>.svg)](https://github.com/Ysz2022/NVEdit)
[![Home Page](https://img.shields.io/badge/Project_Page-<Gallery>-blue.svg)](https://nvedit.github.io/)

</div>

## Introduction

![](./asserts/method.png)

Diffusion models have revolutionized text-driven video editing. However, applying these methods to real-world editing encounters two significant challenges: (1) the rapid increase in graphics memory demand as the number of frames grows, and (2) the inter-frame inconsistency in edited videos. To this end, we propose **NVEdit**, a novel text-driven video editing framework designed to mitigate memory overhead and improve consistent editing for real-world long videos. Specifically, we construct a neural video field, powered by tri-plane and sparse grid, to enable encoding long videos with hundreds of frames in a memory-efficient manner. Next, we update the video field through off-the-shelf Text-to-Image (T2I) models to impart text-driven editing effects. A progressive optimization strategy is developed to preserve original temporal priors. Importantly, both the neural video field and T2I model are adaptable and replaceable, thus inspiring future research. Experiments demonstrate that our approach successfully edits hundreds of frames with impressive inter-frame consistency.

## Results
![](./asserts/intro.png)

**NVEdit** enables various editing options, including shape variation, scene change, and style transfer, while preserving the motion and semantic layout of the original scene. Due to its efficient encoding rate, long videos with hundreds of frames even be edited well. More results can be found in our [**Home Page**](https://nvedit.github.io/).

## Code

Our code is coming soon……
