<div align="center">

<h2>Diffusion-Based Adversarial Sample Generation for Improved Stealthiness and Controllability</h2>

**[Haotian Xue <sup>1](https://xavihart.github.io/), [Alexandre Araujo <sup>2](https://www.alexandrearaujo.com/), [Bin Hu <sup>3](https://binhu7.github.io/), and [Yongxin Chen <sup>1](https://yongxin.ae.gatech.edu/)**


<sup>1</sup> GaTech, <sup>2</sup> NYU, <sup>3</sup> UIUC

</div>


## Introduction

Diff-PGD utilizes strong prior knowledge of Diffusion Model to generate adversarial samples with higher steathiness and controllability. Diff-PGD has the following edges:
- Higher steathiness and controllability 
- Easy to apply to different scenarios (e.g. global, region, style-based, physical world)
- Higher transferability and anti-purification power



## Abstract

>Neural networks are known to be susceptible to adversarial samples: small variations of natural examples crafted to deliberately
mislead the models. While they can be easily generated using gradient-based techniques in digital and physical scenarios, they often differ greatly from the actual data distribution of natural images, resulting in a trade-off between strength and stealthiness. In this paper, we propose a novel framework dubbed Diffusion-Based Projected Gradient Descent (Diff-PGD) for generating realistic adversarial samples. By exploiting a gradient guided by a diffusion model, Diff-PGD ensures that adversarial samples remain close to the original data distribution while maintaining their effectiveness. Moreover, our framework can be easily customized for specific tasks such as digital attacks, physical-world attacks, and style-based attacks. Compared with existing methods for generating natural-style adversarial samples, our framework enables the separation of optimizing adversarial loss from other surrogate losses (e.g., content/smoothness/style loss), making it more stable and controllable. Finally, we demonstrate that the samples generated using Diff-PGD have better transferability and anti-purification power than traditional gradient-based methods.



## News
 - The code will be released soon!


## TODO
- [ ] Paper is out

- [ ] Code for global attack

- [ ] Code for style-based attack

- [ ] Code for physical-world attack

- [ ] Publish pip version




