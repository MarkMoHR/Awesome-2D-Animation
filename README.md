# Awesome-2D-Animation

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A collection of tools, datasets and papers about 2D animation.

> Feel free to create a PR or an issue.  (Pull Request is preferred)

**Outline**

- [1. Software](#1-software)
- [2. Dataset](#2-dataset)
- [3. Inbetweening / Interpolation](#3-inbetweening--interpolation)
- [4. Animation](#4-animation)


## 1. Software

| software | software | software | software |
| --- | --- | --- | --- |
| [Blender](https://www.blender.org/) | [OpenToonz](http://opentoonz.github.io/e/) | [Harmony](https://www.toonboom.com/products/harmony) | [TVPaint](https://www.tvpaint.com/) |
| [Adobe Animate](https://www.adobe.com/products/animate.html) | [Live2D](https://www.live2d.com/en/) | [Cartoon Animator](https://www.reallusion.com/cartoon-animator/) | [CACANi](https://cacani.sg/) |

## 2. Dataset

| Name | Paper | Source | Code/Project Link | 
| --- | --- | --- | --- | 
| [CreativeFlow+](https://www.cs.toronto.edu/creativeflow/) | [Creative Flow+ Dataset](https://www.cs.toronto.edu/creativeflow/files/2596.pdf) | CVPR 2019 | [[code]](https://github.com/creativefloworg/creativeflow) |
| [ATD-12K](https://github.com/lisiyao21/AnimeInterp) | [Deep animation video interpolation in the wild](https://arxiv.org/abs/2104.02495) | CVPR 2021 | [[code]](https://github.com/lisiyao21/AnimeInterp) |
| [AnimeRun](https://lisiyao21.github.io/projects/AnimeRun) | [AnimeRun: 2D Animation Correspondence from Open Source 3D Movies](https://lisiyao21.github.io/projects/AnimeRun) | NeurIPS 2022 | [[code]](https://github.com/lisiyao21/AnimeRun) |
| [AnimeCeleb](https://github.com/kangyeolk/AnimeCeleb) | [AnimeCeleb: Large-Scale Animation CelebHeads Dataset for Head Reenactment](https://arxiv.org/abs/2111.07640) | ECCV 2022 | [[code]](https://github.com/kangyeolk/AnimeCeleb) |
| [Sakuga-42M](https://zhenglinpan.github.io/sakuga_dataset_webpage/) | [Sakuga-42M Dataset: Scaling Up Cartoon Research](https://arxiv.org/abs/2405.07425) | arxiv 24.05 | [[project]](https://zhenglinpan.github.io/sakuga_dataset_webpage/) |
| [Anita](https://github.com/zhenglinpan/AnitaDataset) | [Anita Dataset - An Industrial Animation Dataset](https://zhenglinpan.github.io/AnitaDataset_homepage/) | online 2024 | [[code]](https://github.com/zhenglinpan/AnitaDataset) |


## 3. Inbetweening / Interpolation

| Paper | Source | Representation | Code/Project Link |
| --- | --- | :--: | --- |
| [BetweenIT: An Interactive Tool for Tight Inbetweening](https://onlinelibrary.wiley.com/doi/full/10.1111/j.1467-8659.2009.01630.x) | CGF 2010 | stroke |  |
| [Context-Aware Computer Aided Inbetweening](https://ieeexplore.ieee.org/abstract/document/7831370) | TVCG 2017 | stroke |  |
| [FTP-SC: Fuzzy Topology Preserving Stroke Correspondence](https://dcgi.fel.cvut.cz/home/sykorad/Yang18-SCA.pdf) | SCA 2018 | stroke | [[webpage]](https://dcgi.fel.cvut.cz/home/sykorad/FTP-SC.html) [[video]](https://youtu.be/3oZfCAkYJQk) |
| [Cacani: 2d animation and inbetween software](https://cacani.sg/?v=1c2903397d88) | / | stroke | [[software]](https://cacani.sg/?v=1c2903397d88) |
| [Stroke-Based Drawing and Inbetweening with Boundary Strokes](https://onlinelibrary.wiley.com/doi/full/10.1111/cgf.14433) | CGF 2021 | stroke |  |
| [Joint Stroke Tracing and Correspondence for 2D Animation](https://dl.acm.org/doi/10.1145/3649890) | TOG 2024 | stroke | [[code]](https://github.com/MarkMoHR/JoSTC) [[webpage]](https://markmohr.github.io/JoSTC/) |
|    |
| [Deep Geometrized Cartoon Line Inbetweening](https://openaccess.thecvf.com/content/ICCV2023/papers/Siyao_Deep_Geometrized_Cartoon_Line_Inbetweening_ICCV_2023_paper.pdf) | ICCV 2023 | vertex/point | [[code]](https://github.com/lisiyao21/AnimeInbet) |
| [Thin-Plate Spline-based Interpolation for Animation Line Inbetweening](https://arxiv.org/abs/2408.09131) | arxiv 24.08 | vertex/point | [[code]](https://github.com/Tian-one/tps-inbetween) |
|    |
| [Optical Flow Based Line Drawing Frame Interpolation Using Distance Transform to Support Inbetweenings](https://ieeexplore.ieee.org/abstract/document/8803506) | ICIP 2019 | raster |  |
| [Bridging the Gap: Sketch-Aware Interpolation Network for High-Quality Animation Sketch Inbetweening](https://openreview.net/forum?id=7GPsuT0vyh) | ACM MM 2024 | raster |  |
| [ToonCrafter: Generative Cartoon Interpolation](https://arxiv.org/abs/2405.17933) | SIGGRAPH Asia 2024 | raster | [[code]](https://github.com/ToonCrafter/ToonCrafter) [[webpage]](https://doubiiu.github.io/projects/ToonCrafter/) |
| [Skeleton-Driven Inbetweening of Bitmap Character Drawings](http://www-labs.iro.umontreal.ca/~bmpix/inbetweening/inbetweening.pdf) | SIGGRAPH Asia 2024 | raster | [[code]](https://github.com/kbrodt/inbetweening) [[webpage]](http://www-labs.iro.umontreal.ca/~bmpix/inbetweening/) |

## 4. Animation

| Paper | Source | Representation | Code/Project Link  |
| --- | --- | :--: | --- |
| [Autocomplete Hand-drawn Animations](http://junxnui.github.io/research/siga15_autocomplete_handdrawn_animations.pdf) | SIGGRAPH Asia 2015 | stroke | [[webpage]](https://iis-lab.org/research/autocomplete-animations/) [[video]](https://youtu.be/w0YmWiy6sA4) |
| [ToonSynth: Example-Based Synthesis of Hand-Colored Cartoon Animations](https://dcgi.fel.cvut.cz/home/sykorad/Dvoroznak18-SIG.pdf) | SIGGRAPH 2018 | image | [[webpage]](https://dcgi.fel.cvut.cz/home/sykorad/toonsynth.html) |
| [Live Sketch: Video-driven Dynamic Deformation of Static Drawings](http://sweb.cityu.edu.hk/hongbofu/doc/livesketch_CHI2018.pdf) | CHI 2018 | vector | [[video]](https://youtu.be/6DjQR5k286E) |
| [Animating Portrait Line Drawings from a Single Face Photo and a Speech Signal](https://dl.acm.org/doi/abs/10.1145/3528233.3530720) | SIGGRAPH 2022 | image | [[code]](https://github.com/AnimatePortrait/AnimatePortrait) |
| [A Method for Animating Children’s Drawings of the Human Figure](https://arxiv.org/abs/2303.12741) | TOG 2023 | image | [[code]](https://github.com/facebookresearch/AnimatedDrawings) [[project]](https://people.csail.mit.edu/liyifei/publication/children-animated-drawings/) [[demo]](https://sketch.metademolab.com/canvas) |
| [Non-linear Rough 2D Animation using Transient Embeddings](https://onlinelibrary.wiley.com/doi/full/10.1111/cgf.14771) | CGF 2023 | stroke |  |
| [Sketch Video Synthesis](https://arxiv.org/abs/2311.15306) | EG 2024 | stroke | [[code]](https://github.com/yudianzheng/SketchVideo) [[project]](https://sketchvideo.github.io/) |
| [Breathing Life Into Sketches Using Text-to-Video Priors](https://arxiv.org/abs/2311.13608) | CVPR 2024 | stroke | [[code]](https://github.com/yael-vinker/live_sketch) [[project]](https://livesketch.github.io/) |
| [AniClipart: Clipart Animation with Text-to-Video Priors](https://arxiv.org/abs/2404.12347) | arxiv 24.04 | image | [[project]](https://aniclipart.github.io/) |
| [Dynamic Typography: Bringing Text to Life via Video Diffusion Prior](https://arxiv.org/abs/2404.11614) | arxiv 24.04 | curve | [[project]](https://animate-your-word.github.io/demo/) [[code]](https://github.com/zliucz/animate-your-word) |
| [DrawingSpinUp: 3D Animation from Single Character Drawings](https://lordliang.github.io/DrawingSpinUp/) | SIGGRAPH Asia 2024 | image | [[project]](https://lordliang.github.io/DrawingSpinUp/) [[code]](https://github.com/LordLiang/DrawingSpinUp) |

