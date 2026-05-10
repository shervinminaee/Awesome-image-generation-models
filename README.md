# Awesome Image Generation Models

A curated list of the most influential papers in image generation, covering diffusion models, GANs, autoregressive approaches, and flow-based methods. These are the landmark works that have shaped modern visual synthesis. If there is a paper missing here, please open an issue or submit a pull request, and I would be happy to include it in this list.

# Background

Image generation has undergone a dramatic transformation over the past decade — from early GANs to today's photorealistic diffusion and autoregressive models. The field now enables text-to-image synthesis, image editing, super-resolution, and controllable generation at unprecedented quality. This list focuses on the original model papers that have become foundational to the field.

# Table of Contents
[1. Diffusion Models — Foundations](#diffusion-foundations)
[2. Text-to-Image Diffusion Models](#text-to-image)
[3. Diffusion Model Architectures & Improvements](#diffusion-arch)
[4. Controllable Generation & Editing](#controllable)
[5. Video Generation](#video)
[6. Autoregressive & Token-Based Generation](#autoregressive)
[7. GANs — Landmark Models](#gans)
[8. Flow-Based & Other Approaches](#flow)
[9. Image Super-Resolution & Restoration](#restoration)


### 1. Diffusion Models — Foundations <a name="diffusion-foundations"></a>
* [Deep unsupervised learning using nonequilibrium thermodynamics](https://arxiv.org/abs/1503.03585) (ICML, 2015)
* [Denoising diffusion probabilistic models (DDPM)](https://arxiv.org/abs/2006.11239) (NeurIPS, 2020)
* [Score-based generative modeling through stochastic differential equations](https://arxiv.org/abs/2011.13456) (ICLR, 2021)
* [Denoising diffusion implicit models (DDIM)](https://arxiv.org/abs/2010.02502) (ICLR, 2021)
* [Diffusion models beat GANs on image synthesis (Classifier Guidance)](https://arxiv.org/abs/2105.05233) (NeurIPS, 2021)

### 2. Text-to-Image Diffusion Models <a name="text-to-image"></a>
* [High-resolution image synthesis with latent diffusion models (Stable Diffusion)](https://arxiv.org/abs/2112.10752) (CVPR, 2022)
* [DALL·E 2: Hierarchical text-conditional image generation with CLIP latents](https://arxiv.org/abs/2204.06125) (arXiv, 2022)
* [Imagen: Photorealistic text-to-image diffusion models with deep language understanding](https://arxiv.org/abs/2205.11487) (NeurIPS, 2022)
* [SDXL: Improving latent diffusion models for high-resolution image synthesis](https://arxiv.org/abs/2307.01952) (ICLR, 2024)
* [DALL·E 3: Improving image generation with better captions](https://arxiv.org/abs/2310.12036) (arXiv, 2023)
* [Stable Diffusion 3: Scaling rectified flow transformers for high-resolution image synthesis](https://arxiv.org/abs/2403.03206) (arXiv, 2024)
* [Imagen 3](https://arxiv.org/abs/2408.07009) (arXiv, 2024)

### 3. Diffusion Model Architectures & Improvements <a name="diffusion-arch"></a>
* [Scalable diffusion models with transformers (DiT)](https://arxiv.org/abs/2212.09748) (ICCV, 2023)
* [Classifier-free diffusion guidance](https://arxiv.org/abs/2207.12598) (NeurIPS Workshop, 2022)
* [Flow matching for generative modeling](https://arxiv.org/abs/2210.02747) (ICLR, 2023)
* [Consistency models](https://arxiv.org/abs/2303.01469) (ICML, 2023)
* [Progressive distillation for fast sampling of diffusion models](https://arxiv.org/abs/2202.00512) (ICLR, 2022)

### 4. Controllable Generation & Editing <a name="controllable"></a>
* [Adding conditional control to text-to-image diffusion models (ControlNet)](https://arxiv.org/abs/2302.05543) (ICCV, 2023)
* [IP-Adapter: Text compatible image prompt adapter for text-to-image diffusion models](https://arxiv.org/abs/2308.06721) (arXiv, 2023)
* [DreamBooth: Fine tuning text-to-image diffusion models for subject-driven generation](https://arxiv.org/abs/2208.12242) (CVPR, 2023)
* [An image is worth one word: Personalizing text-to-image generation using textual inversion](https://arxiv.org/abs/2208.01618) (ICLR, 2023)
* [InstructPix2Pix: Learning to follow image editing instructions](https://arxiv.org/abs/2211.09800) (CVPR, 2023)

### 5. Video Generation <a name="video"></a>
* [Sora: Video generation models as world simulators](https://openai.com/index/video-generation-models-as-world-simulators/) (OpenAI, 2024)
* [Video diffusion models](https://arxiv.org/abs/2204.03458) (NeurIPS, 2022)
* [Align your latents: High-resolution video synthesis with latent diffusion models](https://arxiv.org/abs/2304.08818) (CVPR, 2023)
* [Stable Video Diffusion: Scaling latent video diffusion models to large datasets](https://arxiv.org/abs/2311.15127) (arXiv, 2023)

### 6. Autoregressive & Token-Based Generation <a name="autoregressive"></a>
* [Zero-shot text-to-image generation (DALL·E)](https://arxiv.org/abs/2102.12092) (ICML, 2021)
* [Taming transformers for high-resolution image synthesis (VQGAN)](https://arxiv.org/abs/2012.09841) (CVPR, 2021)
* [Parti: Pathways autoregressive text-to-image model](https://arxiv.org/abs/2206.10789) (arXiv, 2022)
* [Visual autoregressive modeling: Scalable image generation via next-scale prediction (VAR)](https://arxiv.org/abs/2404.02905) (NeurIPS, 2024)

### 7. GANs — Landmark Models <a name="gans"></a>
* [Generative adversarial nets (GAN)](https://arxiv.org/abs/1406.2661) (NeurIPS, 2014)
* [A style-based generator architecture for generative adversarial networks (StyleGAN)](https://arxiv.org/abs/1812.04948) (CVPR, 2019)
* [Analyzing and improving the image quality of StyleGAN (StyleGAN2)](https://arxiv.org/abs/1912.04958) (CVPR, 2020)
* [GigaGAN: Scaling up GANs for text-to-image synthesis](https://arxiv.org/abs/2303.05511) (CVPR, 2023)

### 8. Flow-Based & Other Approaches <a name="flow"></a>
* [Glow: Generative flow with invertible 1×1 convolutions](https://arxiv.org/abs/1807.03039) (NeurIPS, 2018)
* [Rectified flow: A marginal preserving approach to optimal transport](https://arxiv.org/abs/2209.14577) (ICLR, 2023)

### 9. Image Super-Resolution & Restoration <a name="restoration"></a>
* [Image super-resolution via iterative refinement (SR3)](https://arxiv.org/abs/2104.07636) (IEEE TPAMI, 2022)
* [StableSR: Exploiting diffusion prior for real-world image super-resolution](https://arxiv.org/abs/2305.07015) (IJCV, 2024)
