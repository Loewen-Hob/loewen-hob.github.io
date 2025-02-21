---
layout: post
title: "论文阅读进度"
subtitle: "一些不同部分的论文阅读进度"
date: 2025-02-20
author: "hob"
header-img: "img/post-bg-2015.jpg"
tags: ['paper reading']
top: True
---
# 近期安排与想法
- 0221记录
    - 学习COT到底是啥，ECI要修改的模块也是COT，generation这也有COT，知乎看看吧。
    - 周末把MDM代码调通学懂。
    - 精读motionllm的paper。
    - 精读deepseek的这三个工作paper。
    - 思考motion understand（maybe reasoning）+generation的框架怎么实现（边读论文边想吧）
    - 先把PPAT代码调通，然后思考怎么把cot模块迁移到iLIF的循环模块中。

# 生成式
## 3D motion generation
### 2020-2024部分论文
- [x] [DDPM](./read_paper/2025-02-17-motion-generation-DDPM.md) ｜ [苏神的blog](https://spaces.ac.cn/archives/9164)
- [x] [DDIM](./read_paper/2025-02-20-motion-generation-DDIM.md) ｜ [苏神的blog](https://spaces.ac.cn/archives/9181)
- [x] [CFG](./read_paper/2025-02-20-motion-generation-cfg.md) ｜ [参考笔记](https://zhuanlan.zhihu.com/p/703579064)
- [x] [Flow Match](./read_paper/2025-02-20-motion-generation-fm.md) ｜ [参考笔记](https://www.dongaigc.com/a/flow-matching-emerging-generative-model)
- [x] [MotionDiffuse]() ｜ [paper](https://arxiv.org/abs/2208.15001) ｜ [code](https://github.com/mingyuan-zhang/MotionDiffuse) ｜ [参考笔记](https://zhuanlan.zhihu.com/p/641606603)
- [x] [MDM](./read_paper/) ｜ [paper](https://arxiv.org/abs/2209.14916) ｜ [code](https://github.com/GuyTevet/motion-diffusion-model)
    - 待办    
        - 需调通代码，了解每一步的实现逻辑
- [x] [MLD]() ｜ [paper](https://arxiv.org/abs/2212.04048) ｜ [code](https://github.com/chenfengye/motion-latent-diffusion)
- [x] [MotionGPT]() ｜ [paper](https://arxiv.org/abs/2306.14795) ｜ [code](https://github.com/OpenMotionLab/MotionGPT)
- [x] [T2M-GPT]() ｜ [paper](https://arxiv.org/abs/2301.06052) ｜ [code](https://mael-zys.github.io/T2M-GPT/)
- [x] [Momask]() ｜ [paper](https://arxiv.org/abs/2312.00063) ｜ [code](https://github.com/EricGuo5513/momask-codes)
- [x] [InstructMotion]() ｜ [paper](https://arxiv.org/abs/2405.15541v1) ｜
- [ ] [ControlMM]() ｜ [paper](https://arxiv.org/abs/2410.10780) ｜ [page](https://exitudio.github.io/ControlMM-page/)

### 近期论文
- [ ] [Free-T2M]() ｜ [paper](https://arxiv.org/abs/2501.18232) ｜ [code](https://github.com/Hxxxz0/Free-T2m)
- [ ] [RMDM]() ｜ [paper](https://arxiv.org/abs/2501.19160) ｜
- [ ] [MDA]() ｜ [paper](https://arxiv.org/abs/2501.18729) ｜ [code](https://github.com/anthony-mendil/MoDiffAE)

### 精读系列
- [ ] [motionllm]() ｜ [paper](https://arxiv.org/abs/2405.20340) ｜ [code](https://github.com/IDEA-Research/MotionLLM)
- [ ] [Janus]() ｜ [paper](https://arxiv.org/abs/2410.13848) ｜ [code](https://github.com/deepseek-ai/Janus)
- [ ] [JanusFlow]() ｜ [paper](https://arxiv.org/abs/2411.07975) ｜ [code](https://github.com/deepseek-ai/Janus)
- [ ] [Janus-Pro]() ｜ [paper](https://github.com/deepseek-ai/Janus/blob/main/janus_pro_tech_report.pdf) ｜ [code](https://github.com/deepseek-ai/Janus)
- [ ] [Image-Generation-CoT]() ｜ [paper](https://arxiv.org/abs/2501.13926) ｜ [code](https://github.com/ZiyuGuo99/Image-Generation-CoT)

# NLP
## 事件因果识别
- [x] [iLIF](https://ckwauwjtrt.feishu.cn/docx/XzcFdvSx1oEMMUxPizdcPTL0nvc) ｜ [paper](https://arxiv.org/abs/2405.20608) ｜ [code](https://github.com/LchengC/iLIF)
- [ ] [PPAT]() ｜ [paper](https://www.ijcai.org/proceedings/2023/0572.pdf) ｜ [code](https://github.com/HITsz-TMG/PPAT)
    - 需将COT部分迁移到iLIF的ECI模块