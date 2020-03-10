## StyleGAN2 Distillation for Feed-forward Image Manipulation
![Title image](./imgs/title.jpg)

**Paper:** https://arxiv.org/abs/2003.03581

**TL;DR: Paired image-to-image translation, trained on synthetic data generated by StyleGAN2 outperforms existing approaches in image manipulation.**

**Abstract:** *StyleGAN2 is a state-of-the-art network in generating realistic images. Besides, it was explicitly trained to have disentangled directions in latent space, which allows efficient image manipulation by varying latent factors. Editing existing images requires embedding a given image into the latent space of StyleGAN2. Latent code optimization via backpropagation is commonly used for qualitative embedding of real world images, although it is prohibitively slow for many applications. We propose a way to distill a particular image manipulation of StyleGAN2 into image-to-image network trained in paired way. The resulting pipeline is an alternative to existing GANs, trained on unpaired data. We provide results of human faces’ transformation: gender swap, aging/rejuvenation, style transfer and image morphing. We show that the quality of generation using our method is comparable to StyleGAN2 backpropagation and current state-of-the-art methods in these particular tasks.*

## Additional material
- [**Uncurated generated examples**](https://drive.google.com/open?id=1RwMUjvYVz-1TGHjrhUn8512HsGWBSmEk)
- **synthetic dataset for gender swap:** coming soon
## Results
### Gender swap
![Gender swap](./imgs/gender.jpg)<br>
[Full-size](https://drive.google.com/open?id=1hIdu9Mdefec8LpeAybfEGu5_Lnjbx1Qa)

### Aging
![Aging](./imgs/aging.jpg)<br>
[Full-size](https://drive.google.com/open?id=1MmY8yZbu0K_CH3dX30Yz-jMkd8C9xIuo)

### Style mixing
![Style mixing](./imgs/style_mixing.jpg)<br>
[Full-size](https://drive.google.com/open?id=1bYNOXDUC84muncjtFY6visatyyICBTDE)

## Citation
```
@article{viazovetskyi2020stylegan2,
 title={StyleGAN2 Distillation for Feed-forward Image Manipulation},
 author={Yuri Viazovetskyi and Vladimir Ivashkin and Evgeny Kashin},
 journal={arXiv preprint arXiv:2003.03581},
 year={2020}
}
```