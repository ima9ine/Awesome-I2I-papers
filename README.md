Awesome-I2I-papers
===

### Survey Paper
* **Image-to-Image Translation: Methods and Applications** (2021)   
[[paper]](https://arxiv.org/pdf/2101.08629.pdf)

### Evaluation Metric
* **IS** (2016)   
Proposed as a evaluation metric for GAN. Ideal generative model should have both high distinctivity and diversity. IS score is calcuated as KL divergence between conditional label distribution and marginal label distribution. IS do not penalize in-calss-diversity. Advised to use samples at least 50k.   
[[paper]](https://proceedings.neurips.cc/paper/2016/file/8a3363abe792db2d8761d6403605aeb7-Paper.pdf) 

* **FID** (2017)   
Proposed as replacement of IS score to evaluate generative model. Compare statistics of   Inception_v3's activation statistics. Advised to use samples more than 10k for stability.     
[[paper]](https://arxiv.org/pdf/1706.08500.pdf) [[github]](https://github.com/mseitzer/pytorch-fid)

> Tradeoff between IS and FID? [paper](https://arxiv.org/abs/1809.11096) ~ truncation   
> IS, FID doubt [paper](https://arxiv.org/pdf/2001.03653.pdf) ~ memorization problem   
> looks like there is no perfect metric for generative model now.   

* **Precision/Recall**(2018/2019)
Proposed to completment of IS and FID. Both just evaluate generative model as single scalar, which is not perfect for measuring 'Fidelity' and 'Diversity'.   
[[paper]](https://arxiv.org/abs/1806.00035) [[paper2]](https://arxiv.org/abs/1904.06991)

* **Density and Coverage**(2020)   
Measures the distance between real images and generated images by introducing a manifold estimation procedure.   
[[paper]](https://arxiv.org/pdf/2002.09797.pdf)

* **LPIPS** (2018)   
Proposed as assessing similarity of two images by inner embedding of DNN. 
[[paper]](https://arxiv.org/abs/1801.03924) [[github]](https://github.com/richzhang/PerceptualSimilarity)

### Data set
 * **Open Images**  
 Open Images dataset includes 9M images annotated with 36M image-level labels, 15.8M bounding boxes, 2.8M instance segmentations, and 391k visual relationships.
 
 * **Places**
 The Places dataset is proposed for scene recognition and contains more than 2.5 million images covering more than 205 scene categories with more than 5,000 images per category.

### Style Transfer

### Inpainting

### Super-resolution

### Semantic Manipulation

### Semantic Segmentation
