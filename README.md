# GANdance: Exploring Guided Sampling of Conditional GANs

> **GANdance: Exploring Guided Sampling of Conditional GANs** <br>
<a href="https://github.com/zyf0619sjtu">Yifei Zhang</a>,</span>
<a href="https://thuxmf.github.io">Mengfei Xia</a>,</span>
<a href="https://shenyujun.github.io">Yujun Shen</a>,</span>
<a href="https://scholar.google.com/citations?user=-ACBm-gAAAAJ&hl=en">Jiapeng Zhu</a>,</span>
<a href="https://ceyuan.me">Ceyuan Yang</a>,</span>
<a href="https://zkcys001.github.io/">Kecheng Zheng</a>,</span>
<a href="">Lianghua Huang</a>,</span>
<a href="">Yu Liu</a>,</span>
<a href="https://shenyujun.github.io">Yujun Shen</a>,</span>
<a href="https://ichengfan.github.io">Fan Cheng</a>,<br>





Abstract: *Guided sampling serves as a widely used inference technique in diffusion models to trade off sample fidelity and diversity. In this work, we confirm that generative adversarial networks (GANs) can also benefit from guided sampling, not even requiring to pre-prepare a classifier (i.e. classifier guidance) or learn an unconditional counterpart (i.e. classifier-free guidance) as in diffusion models. Inspired by the organized latent space in GANs, we manage to estimate the data-condition joint distribution from a well-learned conditional generator simply through vector arithmetic. With such an easy implementation, our approach, termed **GANdance**, improves the FID score of a state-of-the-art GAN model pre-trained on ImageNet 64 x 64 from 8.87 to 6.06, barely increasing the inference time. We then propose a learning-based variant of our framework to better approximate the distribution of the entire dataset, further improving the FID score to 4.37. It is noteworthy that our sampling strategy sufficiently closes the gap between GANs and one-step diffusion models (i.e. with FID 4.02) under comparable model size.*

## 📰 News

- [2024/07/08] Our paper is accepted by ECCV 2024!

## TODO List

- [ ] Release training code  and [Aurora](https://github.com/zhujiapeng/Aurora) generator on ImageNet 64x64.
- [ ] Release inference code for both training-based and training-free guided sampling.

## References

If you find the code useful for your research, please consider citing

```bib

```

## LICENSE

The project is under [MIT License](./LICENSE), and is for research purpose ONLY.
