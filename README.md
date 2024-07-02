# Awesome Diffusion Models in High-Resolution Synthesis [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
Collection of recent diffusion-based high-resolution (e.g., $>1024^2$) image and video synthesis works. Questions and discussions are most welcome! Upcoming works will be updated on a regular basis, feel free to contact me to add... :thumbsup:

## Papers and Codes

- [📍 Image and Video Generation](#papers-and-codes)
  - [Tuning-Free Algorithms](#-tuning-free-algorithms)
  - [Fine-Tuning Algorithms](#-fine-tuning-algorithms)
  - [Training from Scratch Algorithms](#-training-from-scratch-algorithms)
  - [Super Resolution Algorithms](#-super-resolution-algorithms)
  - [Datasets](#datasets)
  - [Metrics](#metrics)

### 🔅 Tuning-Free Algorithms

+ **ResMaster: Mastering High-Resolution Image Generation via Structural and Fine-Grained Guidance** (24 June 2024)<details><summary>Shuwei Shi, Wenbo Li, Yuechen Zhang, et al.</summary> Shuwei Shi, Wenbo Li, Yuechen Zhang, Jingwen He, Biao Gong, Yinqiang Zheng</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.16476)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://sites.google.com/view/minedreamer/main)
[![Code](https://img.shields.io/github/stars/Shuweis/ResMaster.svg?style=social&label=Star)](https://github.com/Shuweis/ResMaster)

+ **DiffuseHigh: Training-free Progressive High-Resolution Image Synthesis through Structure Guidance** (26 June 2024)<details><summary>Linjiang Huang, Rongyao Fang, Aiping Zhang, et al.</summary> Linjiang Huang, Rongyao Fang, Aiping Zhang, Guanglu Song, Si Liu, Yu Liu, Hongsheng Li</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.18459)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://yhyun225.github.io)
[![Code](https://img.shields.io/github/stars/yhyun225/DiffuseHigh.svg?style=social&label=Star)](https://github.com/yhyun225/DiffuseHigh)

+ **FouriScale: A Frequency Perspective on Training-Free High-Resolution Image Synthesis** (19 Mar 2024)<details><summary>Linjiang Huang, Rongyao Fang, Aiping Zhang, et al.</summary> Linjiang Huang, Rongyao Fang, Aiping Zhang, Guanglu Song, Si Liu, Yu Liu, Hongsheng Li</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.12963)
[![Code](https://img.shields.io/github/stars/LeonHLJ/FouriScale.svg?style=social&label=Star)](https://github.com/LeonHLJ/FouriScale)

+ **`ECCV‘24` Make a Cheap Scaling: A Self-Cascade Diffusion Model for Higher-Resolution Adaptation** (16 Feb 2024)<details><summary> Lanqing Guo, Yingqing He, Haoxin Chen, et al.</summary> Lanqing Guo, Yingqing He, Haoxin Chen, Menghan Xia, Xiaodong Cun, Yufei Wang, Siyu Huang, Yong Zhang, Xintao Wang, Qifeng Chen, Ying Shan, Bihan Wen</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.10491)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://guolanqing.github.io/Self-Cascade/)
[![Code](https://img.shields.io/github/stars/GuoLanqing/Self-Cascade.svg?style=social&label=Star)](https://github.com/GuoLanqing/Self-Cascade/)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=9ced6e814457eae83f5415364e266143defc81d1)](https://www.semanticscholar.org/paper/MultiDiffusion%3A-Fusing-Diffusion-Paths-for-Image-Bar-Tal-Yariv/9ced6e814457eae83f5415364e266143defc81d1)

+ **`CVPR‘24` DemoFusion: Democratising High-Resolution Image Generation With No $$$** (15 Dec 2023)<details><summary> Ruoyi Du, Dongliang Chang, Timothy Hospedales, et al.</summary> Ruoyi Du, Dongliang Chang, Timothy Hospedales, Yi-Zhe Song, Zhanyu Ma</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.07702)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ruoyidu.github.io/demofusion/demofusion.html)
[![Code](https://img.shields.io/github/stars/PRIS-CV/DemoFusion.svg?style=social&label=Star)](https://github.com/PRIS-CV/DemoFusion)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=9ced6e814457eae83f5415364e266143defc81d1)](https://www.semanticscholar.org/paper/MultiDiffusion%3A-Fusing-Diffusion-Paths-for-Image-Bar-Tal-Yariv/9ced6e814457eae83f5415364e266143defc81d1)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://replicate.com/lucataco/demofusion)


+ **`CVPR‘24` Chenyang Si, Ziqi Huang, Yuming Jiang, Ziwei Liu** (20 Sep 2023)<details><summary> Chenyang Si, Ziqi Huang, Yuming Jiang, et al.</summary> Chenyang Si, Ziqi Huang, Yuming Jiang, Ziwei Liu</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.11497)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://chenyangsi.top/FreeU/)
[![Code](https://img.shields.io/github/stars/ChenyangSi/FreeU.svg?style=social&label=Star)](https://github.com/ChenyangSi/FreeU)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=9ced6e814457eae83f5415364e266143defc81d1)](https://www.semanticscholar.org/paper/MultiDiffusion%3A-Fusing-Diffusion-Paths-for-Image-Bar-Tal-Yariv/9ced6e814457eae83f5415364e266143defc81d1)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/ChenyangSi/FreeU)

+ **`ICLR‘24` ScaleCrafter: Tuning-Free Higher-Resolution Visual Generation with Diffusion Models** (11 Oct 2023)<details><summary> Yingqing He, Shaoshu Yang, Haoxin Chen, et al.</summary> Yingqing He, Shaoshu Yang, Haoxin Chen, Xiaodong Cun, Menghan Xia, Yong Zhang, Xintao Wang, Ran He, Qifeng Chen, Ying Shan</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.07702)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://yingqinghe.github.io/scalecrafter/)
[![Code](https://img.shields.io/github/stars/YingqingHe/ScaleCrafter.svg?style=social&label=Star)](https://github.com/YingqingHe/ScaleCrafter)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=9ced6e814457eae83f5415364e266143defc81d1)](https://www.semanticscholar.org/paper/MultiDiffusion%3A-Fusing-Diffusion-Paths-for-Image-Bar-Tal-Yariv/9ced6e814457eae83f5415364e266143defc81d1)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://replicate.com/cjwbw/scalecrafter)


+ **`NeurIPS’23` Training-free Diffusion Model Adaptation for Variable-Sized Text-to-Image Synthesis** (26 Oct 2023)<details><summary>Zhiyu Jin, Xuli Shen, Bin Li, et al.</summary> Zhiyu Jin, Xuli Shen, Bin Li, Xiangyang Xue</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.08645)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=166b8c2ee52794c46615c5c52d0390d896b79794)](https://www.semanticscholar.org/paper/Training-free-Diffusion-Model-Adaptation-for-Jin-Shen/166b8c2ee52794c46615c5c52d0390d896b79794)


+ **`ICML‘23` MultiDiffusion: Fusing Diffusion Paths for Controlled Image Generation** (16 Feb 2023)<details><summary>Omer Bar-Tal, Lior Yariv, Yaron Lipman, et al.</summary> Omer Bar-Tal, Lior Yariv, Yaron Lipman, Tali Dekel</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.08113)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://multidiffusion.github.io)
[![Code](https://img.shields.io/github/stars/omerbt/MultiDiffusion.svg?style=social&label=Star)](https://github.com/omerbt/MultiDiffusion)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=9ced6e814457eae83f5415364e266143defc81d1)](https://www.semanticscholar.org/paper/MultiDiffusion%3A-Fusing-Diffusion-Paths-for-Image-Bar-Tal-Yariv/9ced6e814457eae83f5415364e266143defc81d1)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/weizmannscience/MultiDiffusion)


+ **HiDiffusion: Unlocking High-Resolution Creativity and Efficiency in Low-Resolution Trained Diffusion Models** (29 Nov 2023)<details><summary>Shen Zhang, Zhaowei Chen, Zhenyu Zhao, et al.</summary> Shen Zhang, Zhaowei Chen, Zhenyu Zhao, Yuhao Chen, Yao Tang, Jiajun Liang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17528)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://hidiffusion.github.io)
[![Code](https://img.shields.io/github/stars/megvii-research/HiDiffusion.svg?style=social&label=Star)](https://github.com/megvii-research/HiDiffusion)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://colab.research.google.com/drive/1EiBn9lSnPZTU4cikRRaBBexs429M-qty?usp=drive_link)
  

### 🔅 Fine-Tuning Algorithms



+ **`ECCV‘24` Make a Cheap Scaling: A Self-Cascade Diffusion Model for Higher-Resolution Adaptation** (16 Feb 2024)<details><summary> Lanqing Guo, Yingqing He, Haoxin Chen, et al.</summary> Lanqing Guo, Yingqing He, Haoxin Chen, Menghan Xia, Xiaodong Cun, Yufei Wang, Siyu Huang, Yong Zhang, Xintao Wang, Qifeng Chen, Ying Shan, Bihan Wen</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.10491)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://guolanqing.github.io/Self-Cascade/)
[![Code](https://img.shields.io/github/stars/GuoLanqing/Self-Cascade.svg?style=social&label=Star)](https://github.com/GuoLanqing/Self-Cascade/)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=9ced6e814457eae83f5415364e266143defc81d1)](https://www.semanticscholar.org/paper/MultiDiffusion%3A-Fusing-Diffusion-Paths-for-Image-Bar-Tal-Yariv/9ced6e814457eae83f5415364e266143defc81d1)

+ **`ICLR‘24` PixArt-α: Fast Training of Diffusion Transformer for Photorealistic Text-to-Image Synthesis** (13 Apr 2023)<details><summary>Enze Xie, Lewei Yao, Han Shi, Zhili Liu, et al.</summary> Enze Xie, Lewei Yao, Han Shi, Zhili Liu, Daquan Zhou, Zhaoqiang Liu, Jiawei Li, Zhenguo Li</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.00426)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://pixart-alpha.github.io)
[![Code](https://img.shields.io/github/stars/PixArt-alpha/PixArt-alpha.svg?style=social&label=Star)](https://github.com/PixArt-alpha/PixArt-alpha)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=9ced6e814457eae83f5415364e266143defc81d1)](https://www.semanticscholar.org/paper/MultiDiffusion%3A-Fusing-Diffusion-Paths-for-Image-Bar-Tal-Yariv/9ced6e814457eae83f5415364e266143defc81d1)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/PixArt-alpha/PixArt-alpha)


+ **`ICCV‘23` DiffFit: Unlocking Transferability of Large Diffusion Models via Simple Parameter-Efficient Fine-Tuning** (13 Apr 2023)<details><summary>Enze Xie, Lewei Yao, Han Shi, Zhili Liu, et al.</summary> Enze Xie, Lewei Yao, Han Shi, Zhili Liu, Daquan Zhou, Zhaoqiang Liu, Jiawei Li, Zhenguo Li</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.06648)
[![Code](https://img.shields.io/github/stars/mkshing/DiffFit-pytorch.svg?style=social&label=Star)](https://github.com/mkshing/DiffFit-pytorch)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=9ced6e814457eae83f5415364e266143defc81d1)](https://www.semanticscholar.org/paper/MultiDiffusion%3A-Fusing-Diffusion-Paths-for-Image-Bar-Tal-Yariv/9ced6e814457eae83f5415364e266143defc81d1)


+ **`AAAI‘24` Any-Size-Diffusion: Toward Efficient Text-Driven Synthesis for Any-Size HD Images** (31 Aug 2023)<details><summary>Enze Xie, Lewei Yao, Han Shi, Zhili Liu, et al.</summary> Qingping Zheng, Yuanfan Guo, Jiankang Deng, Jianhua Han, Ying Li, Songcen Xu, Hang Xu</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.16582)
[![Code](https://img.shields.io/github/stars/ProAirVerse/Any-Size-Diffusion.svg?style=social&label=Star)](https://github.com/ProAirVerse/Any-Size-Diffusion)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=9ced6e814457eae83f5415364e266143defc81d1)](https://www.semanticscholar.org/paper/MultiDiffusion%3A-Fusing-Diffusion-Paths-for-Image-Bar-Tal-Yariv/9ced6e814457eae83f5415364e266143defc81d1)



### 🔅 Training from Scratch Algorithms

**Cascaded Model**

+ **`ICLR'24` Relay Diffusion: Unifying diffusion process across resolutions for image synthesis** (4 Sep 2023)<details><summary>David Junhao Zhang, Jay Zhangjie Wu, Jia-Wei Liu, et al.</summary> David Junhao Zhang, Jay Zhangjie Wu, Jia-Wei Liu, Rui Zhao, Lingmin Ran, Yuchao Gu, Difei Gao, Mike Zheng Shou</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.03350)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://showlab.github.io/Show-1/)
[![Code](https://img.shields.io/github/stars/THUDM/RelayDiffusion.svg?style=social&label=Star)](https://github.com/THUDM/RelayDiffusion)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/PixArt-alpha/PixArt-alpha](https://replicate.com/cjwbw/lavie))

+ **Show-1: Marrying Pixel and Latent Diffusion Models for Text-to-Video Generation** (27 Sep 2023)<details><summary>David Junhao Zhang, Jay Zhangjie Wu, Jia-Wei Liu, et al.</summary> David Junhao Zhang, Jay Zhangjie Wu, Jia-Wei Liu, Rui Zhao, Lingmin Ran, Yuchao Gu, Difei Gao, Mike Zheng Shou</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.15818)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://showlab.github.io/Show-1/)
[![Code](https://img.shields.io/github/stars/showlab/Show-1.svg?style=social&label=Star)](https://github.com/showlab/Show-1)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/PixArt-alpha/PixArt-alpha](https://replicate.com/cjwbw/show-1))


+ **LaVie: High-Quality Video Generation with Cascaded Latent Diffusion Models** (26 Sep 2023)<details><summary>Yaohui Wang, Xinyuan Chen, Xin Ma, et al.</summary> Yaohui Wang, Xinyuan Chen, Xin Ma, Shangchen Zhou, Ziqi Huang, Yi Wang, Ceyuan Yang, Yinan He, Jiashuo Yu, Peiqing Yang, Yuwei Guo, Tianxing Wu, Chenyang Si, Yuming Jiang, Cunjian Chen, Chen Change Loy, Bo Dai, Dahua Lin, Yu Qiao, Ziwei Liu</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.15103)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://vchitect.github.io/LaVie-project/)
[![Code](https://img.shields.io/github/stars/Vchitect/LaVie.svg?style=social&label=Star)](https://github.com/Vchitect/LaVie)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/PixArt-alpha/PixArt-alpha](https://replicate.com/cjwbw/lavie))

+ **`JMLR‘22` [CDM] Cascaded Diffusion Models for High Fidelity Image Generation** (30 May 2021)<details><summary>Jonathan Ho, Chitwan Saharia, William Chan, et al.</summary> Jonathan Ho, Chitwan Saharia, William Chan, David J. Fleet, Mohammad Norouzi, Tim Salimans</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2106.15282)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://cascaded-diffusion.github.io/)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=9ced6e814457eae83f5415364e266143defc81d1)](https://www.semanticscholar.org/paper/MultiDiffusion%3A-Fusing-Diffusion-Paths-for-Image-Bar-Tal-Yariv/9ced6e814457eae83f5415364e266143defc81d1)

  


**End-to-End Model**

+ **`ICML‘24` Scalable High-Resolution Pixel-Space Image Synthesis with Hourglass Diffusion Transformers** (21 Jan 2024)<details><summary>Katherine Crowson, Stefan Andreas Baumann, Alex Birch, et al. </summary> Katherine Crowson, Stefan Andreas Baumann, Alex Birch, Tanishq Mathew Abraham, Daniel Z. Kaplan, Enrico Shippole</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2401.11605)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://crowsonkb.github.io/hourglass-diffusion-transformers/)
[![Code](https://img.shields.io/github/stars/crowsonkb/k-diffusion.svg?style=social&label=Star)](https://github.com/crowsonkb/k-diffusion)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=9ced6e814457eae83f5415364e266143defc81d1)](https://www.semanticscholar.org/paper/MultiDiffusion%3A-Fusing-Diffusion-Paths-for-Image-Bar-Tal-Yariv/9ced6e814457eae83f5415364e266143defc81d1)

+ **`ICML‘24` FiT: Flexible Vision Transformer for Diffusion Model** (19 Feb 2024)<details><summary>Zeyu Lu, Zidong Wang, Di Huang, et al. </summary> Zeyu Lu, Zidong Wang, Di Huang, Chengyue Wu, Xihui Liu, Wanli Ouyang, Lei Bai</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.12376)
[![Code](https://img.shields.io/github/stars/whlzy/FiT.svg?style=social&label=Star)](https://github.com/whlzy/FiT)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=9ced6e814457eae83f5415364e266143defc81d1)](https://www.semanticscholar.org/paper/MultiDiffusion%3A-Fusing-Diffusion-Paths-for-Image-Bar-Tal-Yariv/9ced6e814457eae83f5415364e266143defc81d1)

+ **`ICLR‘24` SDXL: Improving Latent Diffusion Models for High-Resolution Image Synthesis** (4 Jul 2023)<details><summary>Dustin Podell, Zion English, Kyle Lacey, et al. </summary> Dustin Podell, Zion English, Kyle Lacey, Andreas Blattmann, Tim Dockhorn, Jonas Müller, Joe Penna, Robin Rombach</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.01952)
[![Code](https://img.shields.io/github/stars/Stability-AI/generative-models.svg?style=social&label=Star)](https://github.com/Stability-AI/generative-models)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=9ced6e814457eae83f5415364e266143defc81d1)](https://www.semanticscholar.org/paper/MultiDiffusion%3A-Fusing-Diffusion-Paths-for-Image-Bar-Tal-Yariv/9ced6e814457eae83f5415364e266143defc81d1)

+ **`ICLR‘24` [Patch-DM] Patched Denoising Diffusion Models For High-Resolution Image Synthesis** (2 Aug 2023)<details><summary>Zheng Ding, Mengqi Zhang, Jiajun Wu, et al. </summary> Zheng Ding, Mengqi Zhang, Jiajun Wu, Zhuowen Tu</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.01316)
[![Code](https://img.shields.io/github/stars/mlpc-ucsd/Patch-DM.svg?style=social&label=Star)](https://github.com/mlpc-ucsd/Patch-DM)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=9ced6e814457eae83f5415364e266143defc81d1)](https://www.semanticscholar.org/paper/MultiDiffusion%3A-Fusing-Diffusion-Paths-for-Image-Bar-Tal-Yariv/9ced6e814457eae83f5415364e266143defc81d1)

+ **`ICLR‘24` Matryoshka Diffusion Models** (23 Oct 2023)<details><summary>Jiatao Gu, Shuangfei Zhai, Yizhe Zhang, et al. </summary>Jiatao Gu, Shuangfei Zhai, Yizhe Zhang, Josh Susskind, Navdeep Jaitly</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.15111)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=9ced6e814457eae83f5415364e266143defc81d1)](https://www.semanticscholar.org/paper/MultiDiffusion%3A-Fusing-Diffusion-Paths-for-Image-Bar-Tal-Yariv/9ced6e814457eae83f5415364e266143defc81d1)

+ **`ICLR‘24` ∞-Diff: Infinite Resolution Diffusion with Subsampled Mollified States** (31 Mar 2023)<details><summary>Sam Bond-Taylor, Chris G. Willcocks</summary> Sam Bond-Taylor, Chris G. Willcocks</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.18242)
[![Code](https://img.shields.io/github/stars/samb-t/infty-diff.svg?style=social&label=Star)](https://github.com/samb-t/infty-diff)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=9ced6e814457eae83f5415364e266143defc81d1)](https://www.semanticscholar.org/paper/MultiDiffusion%3A-Fusing-Diffusion-Paths-for-Image-Bar-Tal-Yariv/9ced6e814457eae83f5415364e266143defc81d1)

+ **On the Importance of Noise Scheduling for Diffusion Models** (26 Jan 2023)<details><summary>Ting Chen</summary> Ting Chen</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.10972)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=9ced6e814457eae83f5415364e266143defc81d1)](https://www.semanticscholar.org/paper/MultiDiffusion%3A-Fusing-Diffusion-Paths-for-Image-Bar-Tal-Yariv/9ced6e814457eae83f5415364e266143defc81d1)


+ **`ICML‘23` Simple diffusion: End-to-end diffusion for high resolution images** (26 Jan 2023)<details><summary>Emiel Hoogeboom, Jonathan Heek, et al.</summary> Emiel Hoogeboom, Jonathan Heek, Tim Salimans</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.11093)
[![Code](https://img.shields.io/github/stars/patil-suraj/simple-diffusion.svg?style=social&label=Star)](https://github.com/patil-suraj/simple-diffusion)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=9ced6e814457eae83f5415364e266143defc81d1)](https://www.semanticscholar.org/paper/MultiDiffusion%3A-Fusing-Diffusion-Paths-for-Image-Bar-Tal-Yariv/9ced6e814457eae83f5415364e266143defc81d1)


  


### 🔅 Super Resolution Algorithms


+ **[PromptSR] Image Super-Resolution with Text Prompt Diffusion** (24 Nov 2023)<details><summary>Zheng Chen, Yulun Zhang, Jinjin Gu, et al.</summary> Zheng Chen, Yulun Zhang, Jinjin Gu, Xin Yuan, Linghe Kong, Guihai Chen, Xiaokang Yang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.07015)
[![Code](https://img.shields.io/github/stars/zhengchen1999/PromptSR.svg?style=social&label=Star)](https://github.com/zhengchen1999/PromptSR)


+ **TIP: Text-Driven Image Processing with Semantic and Restoration Instructions** (18 Dec 2023)<details><summary>Chenyang Qi, Zhengzhong Tu, Keren Ye, et al.</summary> Chenyang Qi, Zhengzhong Tu, Keren Ye, Mauricio Delbracio, Peyman Milanfar, Qifeng Chen, Hossein Talebi</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.07015)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://chenyangqiqi.github.io/tip/)

+ **`CVPR‘24` [SUPIR] Scaling Up to Excellence: Practicing Model Scaling for Photo-Realistic Image Restoration In the Wild** (24 Jan 2024)<details><summary>Fanghua, Yu, Jinjin Gu, Zheyuan Li, et al.</summary> Fanghua, Yu, Jinjin Gu, Zheyuan Li, Jinfan Hu, Xiangtao Kong, Xintao Wang, Jingwen He, Yu Qiao, Chao Dong</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.13627)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://supir.xpixel.group)
[![Code](https://img.shields.io/github/stars/Fanghua-Yu/SUPIR.svg?style=social&label=Star)](https://github.com/Fanghua-Yu/SUPIR)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=9ced6e814457eae83f5415364e266143defc81d1)](https://www.semanticscholar.org/paper/MultiDiffusion%3A-Fusing-Diffusion-Paths-for-Image-Bar-Tal-Yariv/9ced6e814457eae83f5415364e266143defc81d1)


+ **`IJCV‘24` [StableSR] Exploiting Diffusion Prior for Real-World Image Super-Resolution** (11 May 2023)<details><summary>Jianyi Wang, Zongsheng Yue, Shangchen Zhou, et al.</summary> Jianyi Wang, Zongsheng Yue, Shangchen Zhou, Kelvin C.K. Chan, Chen Change Loy</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.07015)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://iceclear.github.io/projects/stablesr/)
[![Code](https://img.shields.io/github/stars/IceClear/StableSR.svg?style=social&label=Star)](https://github.com/IceClear/StableSR)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=9ced6e814457eae83f5415364e266143defc81d1)](https://www.semanticscholar.org/paper/MultiDiffusion%3A-Fusing-Diffusion-Paths-for-Image-Bar-Tal-Yariv/9ced6e814457eae83f5415364e266143defc81d1)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/Iceclear/StableSR)




## Metrics

* FID / KID (Fre ́chet Inception Distance) [[Ref]](https://en.wikipedia.org/wiki/Fréchet_inception_distance)
* IS (Inception Score) [[Ref]](https://proceedings.neurips.cc/paper/2016/file/8a3363abe792db2d8761d6403605aeb7-Paper.pdf)
* patch-FID (pFID) / patch-KID (pKID): use cropped local patches [[Ref]](https://arxiv.org/abs/2204.07156)
* sFID / sKID: use the features before the global average pooling [[Ref]](https://arxiv.org/abs/2103.03841)

