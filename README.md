Awesome-I2I-papers
===

### Survey Paper
* **Image-to-Image Translation: Methods and Applications** (2021)   
[[paper]](https://arxiv.org/pdf/2101.08629.pdf)

### Evaluation Metric
* **IS** (2016)   
Proposed as a evaluation metric for GAN. Ideal generative model should have both high distinctivity and diversity. IS score is calcuated as KL divergence between conditional label distribution and marginal label distribution. Advised to use samples at least 50k.   [[paper]](https://proceedings.neurips.cc/paper/2016/file/8a3363abe792db2d8761d6403605aeb7-Paper.pdf) 

* **FID** (2017)   
Proposed as replacement of IS score to evaluate generative model. Compare statistics of   Inception_v3's activation statistics. Advised to use samples more than 10k for stability.     
[[paper]](https://arxiv.org/pdf/1706.08500.pdf) [[github]](https://github.com/mseitzer/pytorch-fid)

* **LPIPS** (2018)   
Proposed as assessing similarity of two images by inner embedding of DNN. 
[[paper]](https://arxiv.org/abs/1801.03924) [[github]](https://github.com/richzhang/PerceptualSimilarity)

### Style transfer

### Inpainting

### Super-resolution

### Semantic manipulation
