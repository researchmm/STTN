# STTN for Video Inpainting
![teaser](https://github.com/researchmm/STTN/blob/master/docs/teaser.png?raw=true)

### [Paper](https://arxiv.org/abs/2007.10247) | [Demo](https://www.youtube.com/watch?v=tgiWGdr1SnE&feature=youtu.be) | [Video](https://drive.google.com/file/d/19eKm4AJhIbJAbvXyA-HTQHFdia7XcN6H/view?usp=sharing) | [Slides](https://drive.google.com/file/d/1y09-SLcTadqpuDDLSzFdtr3ymGbjrmyi/view?usp=sharing) |[BibTex](https://github.com/researchmm/STTN#citation)

Learning Joint Spatial-Temporal Transformations for Video Inpainting<br>

[Yanhong Zeng](https://sites.google.com/view/1900zyh),  [Jianlong Fu](https://jianlong-fu.github.io/), and [Hongyang Chao](https://scholar.google.com/citations?user=qnbpG6gAAAAJ&hl).<br>
In ECCV 2020.

<!-- ---------------------------------------------- -->
## Introduction 
High-quality video inpainting that completes missing regions in video frames is a promising yet challenging task. 

In this paper, we propose to learn a joint Spatial-Temporal Transformer Network (STTN) for video inpainting. Specifically, we simultaneously fill missing regions in all input frames by self-attention, and propose to optimize STTN by a spatial-temporal adversarial loss. 

To show the superiority of the proposed model, we conduct both quantitative and qualitative evaluations by using standard stationary masks and more realistic moving object masks.

![STTN](https://github.com/researchmm/STTN/blob/master/docs/sttn.png?raw=true)


<!-- ---------------------------------------------- -->
## Citation
If any part of our paper and repository is helpful to your work, please generously cite with:
```
@inproceedings{yan2020sttn,
  author = {Zeng, Yanhong and Fu, Jianlong and Chao, Hongyang,
  title = {Learning Joint Spatial-Temporal
Transformations for Video Inpainting},
  booktitle = {The Proceedings of the European Conference on Computer Vision (ECCV)},
  year = {2020}
}
```