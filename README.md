# MME: A Comprehensive Evaluation Benchmark for Multimodal Large Language Models

<img src="./images/dataset.png" width="96%" height="96%">

> Multimodal Large Language Model (MLLM) relies on the powerful LLM to perform multimodal tasks, showing amazing emergent abilities in recent studies, such as writing poems based on an image. However, it is difficult for these case studies to fully reflect the performance of MLLM, lacking a comprehensive evaluation. In this paper, we fill in this blank, presenting the first MLLM Evaluation benchmark MME. It measures both perception and cognition abilities on a total of 14 subtasks. In order to avoid data leakage that may arise from direct use of public datasets for evaluation, the annotations of instruction-answer pairs are all manually designed. The concise instruction design allows us to fairly compare MLLMs, instead of struggling in prompt engineering. Besides, with such an instruction, we can also easily carry out quantitative statistics. A total of 39 advanced MLLMs are comprehensively evaluated on our MME, which not only suggests that existing MLLMs still have a large room for improvement, but also reveals the potential directions for the subsequent model optimization.




## Our MLLM works

🔥🔥🔥 **A Survey on Multimodal Large Language Models**  
**[Project Page](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models)** | **[Paper](https://arxiv.org/pdf/2306.13549.pdf)**

A curated list of Multimodal Large Language Models (MLLMs), including multimodal instruction tuning, multimodal in-context learning, multimodal chain-of-thought, llm-aided visual reasoning, foundation models, datasets, and others. This list will be updated in real time. :sparkles:

Welcome to add WeChat ID (wmd_ustc) to join our MLLM communication group! :star2:

---

🔥🔥🔥 **MME: A Comprehensive Evaluation Benchmark for Multimodal Large Language Models**  
**[Project Page [This Page]](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models/tree/Evaluation)** | **[Paper](https://arxiv.org/pdf/2306.13394.pdf)**

Leaderboards of **39** advanced MLLMs, including 32 published and 7 private models. The former consists of [**BLIP-2**](https://arxiv.org/pdf/2301.12597.pdf), [**InstructBLIP**](https://arxiv.org/pdf/2305.06500.pdf), [**LLaVA**](https://arxiv.org/pdf/2304.08485.pdf), [**MiniGPT-4**](https://arxiv.org/pdf/2304.10592.pdf), [**mPLUG-Owl**](https://arxiv.org/pdf/2304.14178.pdf), [**LLaMA-Adapter V2**](https://arxiv.org/pdf/2304.15010.pdf), [**ImageBind_LLM**](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main), [**Otter**](https://arxiv.org/pdf/2305.03726.pdf), [**VisualGLM-6B**](https://github.com/THUDM/VisualGLM-6B), [**Multimodal-GPT**](https://arxiv.org/pdf/2305.04790.pdf), [**PandaGPT**](https://arxiv.org/pdf/2305.16355.pdf), [**VPGTrans**](https://arxiv.org/pdf/2305.01278.pdf), [**LaVIN**](https://arxiv.org/pdf/2305.15023.pdf), [**Lynx**](https://arxiv.org/pdf/2307.02469.pdf), [**LRV-Instruction**](https://arxiv.org/pdf/2306.14565.pdf), [**Cheetor**](https://arxiv.org/pdf/2308.04152.pdf), [**MMICL**](https://github.com/HaozheZhao/MIC), [**GIT2**](https://arxiv.org/pdf/2205.14100.pdf), [**BLIVA**](https://arxiv.org/pdf/2308.09936.pdf), [**Qwen-VL-Chat**](https://arxiv.org/pdf/2308.12966.pdf), [**InternLM-XComposer-VL**](https://arxiv.org/pdf/2309.15112.pdf), [**Muffin**](https://github.com/thunlp/Muffin), [**WeMM**](https://github.com/scenarios/WeMM), [**SPHINX**](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX), [**InfMLLM**](https://github.com/mightyzau/InfMLLM), [**mPLUG-Owl2**](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2), [**LVIS-INSTRUCT4V**](https://arxiv.org/pdf/2311.07574.pdf), [**DataOptim**](https://github.com/BAAI-DCAI/DataOptim), [**ShareGPT4V**](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V), [**BELLE-VL**](https://huggingface.co/BELLE-2/BELLE-VL), [**TransCore-M**](https://github.com/PCIResearch/TransCore-M), and [**Monkey-Chat**](https://github.com/Yuliang-Liu/Monkey).
The latter consists of [**GPT-4V**](https://cdn.openai.com/papers/GPTV_System_Card.pdf), [**Skywork-MM**](https://github.com/will-singularity/Skywork-MM/tree/main), [**Octopus**](https://github.com/gray311/UnifiedMultimodalInstructionTuning), [**Lion**](https://github.com/mynameischaos/Lion), [**CVLM**](https://github.com/buptlihang/CVLM), [**Kanva**](https://github.com/llp1992/Kanva), and [**AGILMM**](https://github.com/AIResearchEnthusiast/AGILMM).

If you want to add your model in our leaderboards, please feel free to email bradyfu24@gmail.com. We will update the leaderboards in time. :sparkles:

<details><summary>Download MME :star2::star2: </summary>

The benchmark dataset is collected by Xiamen University for academic research only. You can email guilinli@stu.xmu.edu.cn to obtain the dataset, according to the following requirement. 

**Requirement**: A real-name system is encouraged for better academic communication. Your email suffix needs to match your affiliation, such as xx@stu.xmu.edu.cn and Xiamen University. Otherwise, you need to explain why. Please include the information bellow when sending your application email.

```
Name: (tell us who you are.)
Affiliation: (the name/url of your university or company)
Job Title: (e.g., professor, PhD, and researcher)
Email: (your email address)
How to use: (only for non-commercial use)
```

</details>

---

🔥🔥🔥 **Woodpecker: Hallucination Correction for Multimodal Large Language Models** 

<p align="center">
    <img src="./images/woodpecker_icon.png" width="28%" height="28%">
</p>

**[Paper](https://arxiv.org/pdf/2310.16045.pdf)** | **[Online Demo](https://f252626b321420bfb1.gradio.live/)** | **[Source Code![Star](https://img.shields.io/github/stars/BradyFU/Woodpecker.svg?style=social&label=Star)](https://github.com/BradyFU/Woodpecker)**

This is the first work to correct hallucinations in MLLMs.

---

<br> **📑 If you find our projects helpful to your research, please consider citing:** <br>

```
@article{yin2023survey,
  title={A Survey on Multimodal Large Language Models},
  author={Yin, Shukang and Fu, Chaoyou and Zhao, Sirui and Li, Ke and Sun, Xing and Xu, Tong and Chen, Enhong},
  journal={arXiv preprint arXiv:2306.13549},
  year={2023}
}

@article{fu2023mme,
  title={MME: A Comprehensive Evaluation Benchmark for Multimodal Large Language Models},
  author={Fu, Chaoyou and Chen, Peixian and Shen, Yunhang and Qin, Yulei and Zhang, Mengdan and Lin, Xu and Yang, Jinrui and Zheng, Xiawu and Li, Ke and Sun, Xing and Wu, Yunsheng and Ji, Rongrong},
  journal={arXiv preprint arXiv:2306.13394},
  year={2023}
}

@article{yin2023woodpecker,
  title={Woodpecker: Hallucination Correction for Multimodal Large Language Models},
  author={Yin, Shukang and Fu, Chaoyou and Zhao, Sirui and Xu, Tong and Wang, Hao and Sui, Dianbo and Shen, Yunhang and Li, Ke and Sun, Xing and Chen, Enhong},
  journal={arXiv preprint arXiv:2310.16045},
  year={2023}
}
```

---

# News 🚀
**[2023-11]** 

**[2023-12]** 

1. [12-12] Thanks to [**Yuliang Liu**](https://github.com/Yuliang-Liu), [**Monkey-Chat**](https://github.com/Yuliang-Liu/Monkey) takes part in MME. 🔥🔥
2. [12-12] Thanks to [**Junkun Yuan**](https://scholar.google.com.hk/citations?hl=zh-CN&user=j3iFVPsAAAAJ&view_op=list_works&sortby=pubdate), we welcome a new member [**AGILMM**](https://github.com/AIResearchEnthusiast/AGILMM). 🔥🔥
4. [12-01] Thanks to [**Cheng Wen**](https://scholar.google.com/citations?user=9MLB3s8AAAAJ&hl=zh-CN), [**BELLE-VL**](https://huggingface.co/BELLE-2/BELLE-VL) is added to our leaderboards. 🔥🔥
5. [12-01] Thanks to [**PCI Research**](https://www.pcitech.com/), [**TransCore-M**](https://github.com/PCIResearch/TransCore-M) joins MME. 🔥🔥


**[2023-11]** 

1. [11-24] Thanks to [**Xiaoyi Dong**](https://scholar.google.com/citations?user=FscToE0AAAAJ&hl=en), we add [**ShareGPT4V**](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) to our leaderboards. 🔥🔥
2. [11-24] Thanks to [**Muyang He**](https://scholar.google.com/citations?hl=en&user=Q0Xn7i4AAAAJ), [**DataOptim**](https://github.com/BAAI-DCAI/DataOptim) joins MME. 🔥🔥
3. [11-24] Thanks to [**Zifei Shan**](https://scholar.google.com/citations?user=DGIdpTwAAAAJ&hl=en&oi=ao), [**Kanva**](https://github.com/llp1992/Kanva) is added. 🔥🔥
4. [11-21] Thanks to [**Junke Wang**](https://scholar.google.com.hk/citations?user=qQuxuo0AAAAJ&hl=zh-CN&oi=ao), [**LVIS-INSTRUCT4V**](https://arxiv.org/pdf/2311.07574.pdf) is added to our MME. 🔥🔥
5. [11-18] Thanks to [**Zhenbo Luo**](https://dblp.org/pid/152/8206.html), our leaderboards welcome a new member [**CVLM**](https://github.com/buptlihang/CVLM). 🔥🔥
6. [11-10] Thanks to [**Qinghao Ye**](https://scholar.google.com.hk/citations?user=ZYOhaGwAAAAJ&hl=zh-CN&oi=ao), we get a new model [**mPLUG-Owl2**](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) in our leaderboards. 🔥🔥
7. [11-10] Thanks to [**Zhibin Wang**](https://scholar.google.com/citations?hl=zh-CN&user=YHzKee8AAAAJ), [**InfMLLM**](https://github.com/mightyzau/InfMLLM) joins our leaderboards (update in 2023-12-12). 🔥🔥

**[2023-10]** 

1. [10-29] Thanks to [**Jiaming Han**](https://scholar.google.com/citations?hl=en&user=vgcxKEcAAAAJ&view_op=list_works), [**SPHINX**](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) is added to our leaderboards. 
2. [10-23] Thanks to [**Zihan Wang**](https://github.com/hanhanHANS), he manually evaluate the performance of [**GPT-4V**](https://cdn.openai.com/papers/GPTV_System_Card.pdf) on our benchmark. Note that GPT-4V refuses to answer questions that involve individuals, resulting in a zero score in the Celebrity subtask. 
3. [10-13] Thanks to [**Yizhou Zhou**](https://scholar.google.com/citations?user=dHBNmSkAAAAJ&hl=en&oi=sra), [**WeMM**](https://github.com/scenarios/WeMM) joins our leaderboards (The results are renewed on 2023-11-10 by updating the model). 
4. [10-13] Thanks to [**Cui Junbo**](https://github.com/thunlp/Muffin), we add [**Muffin**](https://github.com/thunlp/Muffin) to our leaderboards. 
5. [10-13] Thanks to [**Jiaming Han**](https://scholar.google.com/citations?hl=en&user=vgcxKEcAAAAJ&view_op=list_works), the results of [**LLaMA-Adapter V2**](https://github.com/OpenGVLab/LLaMA-Adapter) have been updated. 
6. [10-04] Thanks to [**Haotian Liu**](https://hliu.cc/), the results of [**LLaVA**](https://github.com/haotian-liu/LLaVA) have been updated. 

**[2023-09]** 

1. [09-28] Thanks to [**Huasong Zhong**](https://github.com/mynameischaos), [**Lion**](https://github.com/mynameischaos/Lion) is added.
2. [09-27] Thanks to [**Xiaoyi Dong**](https://scholar.google.com/citations?user=FscToE0AAAAJ&hl=en), [**InternLM-XComposer-VL**](https://github.com/InternLM/InternLM-XComposer) joins our leaderboards.
3. [09-05] Thanks to [**Jinze Bai**](https://github.com/jinze1994), our leaderboards usher in [**Qwen-VL-Chat**](https://github.com/QwenLM/Qwen-VL).
4. [09-01] Thanks to [**Skywork Multi-Modal Group**](https://github.com/will-singularity), [**Skywork-MM**](https://github.com/will-singularity/Skywork-MM/tree/main) takes part in our leaderboards.

**[2023-08]** 

1. [08-28] Thanks to [**UCSD MLPC**](https://github.com/mlpc-ucsd), we welcome [**BLIVA**](https://github.com/mlpc-ucsd/BLIVA) to join our leaderboards. 
2. [08-28] Thanks to [**Jianfeng Wang**](https://scholar.google.com.hk/citations?user=vJWEw_8AAAAJ&hl=zh-CN&oi=sra), [**GIT2**](https://github.com/microsoft/GenerativeImage2Text) is added to our leaderboards. 
3. [08-28] Thanks to [**Yike Yuan**](https://github.com/yyk-wew) and [**Songyang Zhang**](https://github.com/tonysy), the results of [**MiniGPT4**](https://arxiv.org/pdf/2304.10592.pdf) have been revised. 
4. [08-21] Thanks to [**Haozhe Zhao**](https://github.com/HaozheZhao), [**MMICL**](https://github.com/HaozheZhao/MIC) joins our leaderboards (The results are renewed on 2023-09-17 by upgrading the checkpoint.). 
5. [08-13] Thanks to [**Zhejiang University DCD Lab**](https://github.com/DCDmllm), our leaderboards incorporate a new member [**Cheetor**](https://github.com/DCDmllm/Cheetah). 
6. [08-08] Thanks to [**Fuxiao Liu**](https://github.com/FuxiaoLiu), we add [**LRV-Instruction**](https://github.com/FuxiaoLiu/LRV-Instruction) to our leaderboards. 

**[2023-07]** 

1. [07-28] Thanks to [**Yingzi Ma**](https://gray311.github.io/), his work [**Octopus**](https://github.com/gray311/UnifiedMultimodalInstructionTuning) has been updated to our leaderboards.
2. [07-15] Thanks to [**Jiani Zheng**](https://github.com/Garlicisnotmyfavor), our leaderboards welcome a new member [**Lynx**](https://github.com/bytedance/lynx-llm).
3. [07-12] Thanks to [**Ao Zhang**](https://github.com/waxnkw), his work [**VPGTrans**](https://github.com/VPGTrans/VPGTrans) has been added in our leaderboards.
4. [07-09] Thanks to [**Bo Li**](https://github.com/Luodian), we have updated the evaluation of his work [**Otter**](https://github.com/Luodian/Otter). It uses the latest model [**OTTER-Image-MPT7B**](https://huggingface.co/luodian/OTTER-Image-MPT7B) that incoporates OpenFlamingv2 and enhances instruction following ability.

**[2023-06]** 

1. [06-30] Thanks to [**Renrui Zhang**](https://github.com/ZrrSkywalker), we have updated the evaluation of his two works, i.e., [**LLaMA-Adapter V2**](https://github.com/OpenGVLab/LLaMA-Adapter) and [**ImageBind_LLM**](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM). The former is re-evaluated after changing the model [**weights**](https://github.com/OpenGVLab/LLaMA-Adapter/releases/download/v.2.0.0/7fa55208379faf2dd862565284101b0e4a2a72114d6490a95e432cf9d9b6c813_BIAS-7B.pth), and the latter is a newly added MLLM.
2. [06-30] Thanks to [**Gen Luo**](https://github.com/luogen1996), we have added the evaluation of his work [**LaVIN**](https://github.com/luogen1996/LaVIN).
3. [06-30] The results of other models have also been updated, retrieving the answer from the beginning of the generated responses instead of the whole responses. [**An automated evaluation script**](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models/blob/Evaluation/tools/eval_tool.zip) for the calculation of scores has been released!

---

# Results of Private Models [[Published Version](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models/tree/Evaluation)]

The top 5 on the perception and cognition leaderboards:

<img src="./images/evaluation_chart_private_1218.png" width="80%" height="80%">

Published and private models are separated. GPT-4V is included in both as an intermediate comparison.

# Leaderboards of Private Models [[Published Version](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models/tree/Evaluation)]

<img src="./images/xmind.png" width="96%" height="96%">

---

- [Perception](#perception)
  - [Existence](#existence) | [Count](#count) | [Position](#position) | [Color](#color) | [Poster](#poster) | [Celebrity](#celebrity) | [Scene](#scene) | [Landmark](#landmark) | [Artwork](#artwork) | [OCR](#ocr)
- [Cognition](#cognition)
  - [Commonsense Reasoning](#commonsense-reasoning) | [Numerical Calculation](#numerical-calculation) | [Text Translation](#text-translation) | [Code Reasoning](#code-reasoning)

---

## Perception

Sum of the scores of all perception subtasks, including existence, count, position, color, poster, celebrity, scene, landmark, artwork, and OCR. The full score of each subtask is 200, and that of all perception is 2000.

| Rank |                            Model                             |                           Version                            |    Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :---------: |
|  🏅️   | **[AGILMM](https://github.com/AIResearchEnthusiast/AGILMM)** | **[Bloom-7B](https://github.com/AIResearchEnthusiast/AGILMM)** | **1742.68** |
|  🥈   |        **[Kanva](https://github.com/llp1992/Kanva)**         |       **[Qwen-14B](https://github.com/llp1992/Kanva)**       | **1666.08** |
|  🥉   |     **[Honeybee](https://arxiv.org/pdf/2312.06742.pdf)**     |   **[Vicuna-13B](https://github.com/kakaobrain/honeybee)**   | **1661.13** |
|  4   |          [CVLM](https://github.com/buptlihang/CVLM)          |       [Vicuna-13B](https://github.com/buptlihang/CVLM)       |   1636.45   |
|  5   |        [Lion](https://github.com/mynameischaos/Lion)         |     [InternLM-7B](https://github.com/mynameischaos/Lion)     |   1545.80   |
|  6   | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) |   1419.08   |
|  7   | [Octopus](https://github.com/gray311/UnifiedMultimodalInstructionTuning) | [MPT7B](https://github.com/gray311/UnifiedMultimodalInstructionTuning) |   1095.75   |

### Existence

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |        **[Kanva](https://github.com/llp1992/Kanva)**         |       **[Qwen-14B](https://github.com/llp1992/Kanva)**       | **195.00** |
|  🥈   |      **[Lion](https://github.com/mynameischaos/Lion)**       |   **[InternLM-7B](https://github.com/mynameischaos/Lion)**   | **190.00** |
|  🥉   |        **[CVLM](https://github.com/buptlihang/CVLM)**        |     **[Vicuna-13B](https://github.com/buptlihang/CVLM)**     | **185.00** |
|  🥉   | **[AGILMM](https://github.com/AIResearchEnthusiast/AGILMM)** | **[Bloom-7B](https://github.com/AIResearchEnthusiast/AGILMM)** | **185.00** |
|  🥉   |     **[Honeybee](https://arxiv.org/pdf/2312.06742.pdf)**     |   **[Vicuna-13B](https://github.com/kakaobrain/honeybee)**   | **185.00** |
|  4   | [Octopus](https://github.com/gray311/UnifiedMultimodalInstructionTuning) | [MPT7B](https://github.com/gray311/UnifiedMultimodalInstructionTuning) |   180.00   |
|  4   | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) |   180.00   |

### Count

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |     **[Honeybee](https://arxiv.org/pdf/2312.06742.pdf)**     |   **[Vicuna-13B](https://github.com/kakaobrain/honeybee)**   | **170.00** |
|  🥈   |        **[Kanva](https://github.com/llp1992/Kanva)**         |       **[Qwen-14B](https://github.com/llp1992/Kanva)**       | **156.67** |
|  🥉   |      **[Lion](https://github.com/mynameischaos/Lion)**       |   **[InternLM-7B](https://github.com/mynameischaos/Lion)**   | **155.00** |
|  🥉   |        **[CVLM](https://github.com/buptlihang/CVLM)**        |     **[Vicuna-13B](https://github.com/buptlihang/CVLM)**     | **155.00** |
|  5   |   [AGILMM](https://github.com/AIResearchEnthusiast/AGILMM)   |  [Bloom-7B](https://github.com/AIResearchEnthusiast/AGILMM)  |   153.33   |
|  6   | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) |   151.67   |
|  7   | [Octopus](https://github.com/gray311/UnifiedMultimodalInstructionTuning) | [MPT7B](https://github.com/gray311/UnifiedMultimodalInstructionTuning) |   53.33    |

### Position

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |        **[Kanva](https://github.com/llp1992/Kanva)**         |       **[Qwen-14B](https://github.com/llp1992/Kanva)**       | **185.00** |
|  🥈   |        **[CVLM](https://github.com/buptlihang/CVLM)**        |     **[Vicuna-13B](https://github.com/buptlihang/CVLM)**     | **178.33** |
|  🥉   |     **[Honeybee](https://arxiv.org/pdf/2312.06742.pdf)**     |   **[Vicuna-13B](https://github.com/kakaobrain/honeybee)**   | **155.00** |
|  4   |        [Lion](https://github.com/mynameischaos/Lion)         |     [InternLM-7B](https://github.com/mynameischaos/Lion)     |   153.33   |
|  5   |   [AGILMM](https://github.com/AIResearchEnthusiast/AGILMM)   |  [Bloom-7B](https://github.com/AIResearchEnthusiast/AGILMM)  |   138.33   |
|  6   | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) |   63.33    |
|  7   | [Octopus](https://github.com/gray311/UnifiedMultimodalInstructionTuning) | [MPT7B](https://github.com/gray311/UnifiedMultimodalInstructionTuning) |   48.33    |

### Color

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |        **[CVLM](https://github.com/buptlihang/CVLM)**        |     **[Vicuna-13B](https://github.com/buptlihang/CVLM)**     | **185.00** |
|  🥈   |      **[Lion](https://github.com/mynameischaos/Lion)**       |   **[InternLM-7B](https://github.com/mynameischaos/Lion)**   | **180.00** |
|  🥈   | **[AGILMM](https://github.com/AIResearchEnthusiast/AGILMM)** | **[Bloom-7B](https://github.com/AIResearchEnthusiast/AGILMM)** | **180.00** |
|  🥈   |     **[Honeybee](https://arxiv.org/pdf/2312.06742.pdf)**     |   **[Vicuna-13B](https://github.com/kakaobrain/honeybee)**   | **180.00** |
|  🥉   |        **[Kanva](https://github.com/llp1992/Kanva)**         |       **[Qwen-14B](https://github.com/llp1992/Kanva)**       | **160.00** |
|  4   | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) |   145.00   |
|  5   | [Octopus](https://github.com/gray311/UnifiedMultimodalInstructionTuning) | [MPT7B](https://github.com/gray311/UnifiedMultimodalInstructionTuning) |   103.33   |

### Poster

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |      **[Lion](https://github.com/mynameischaos/Lion)**       |   **[InternLM-7B](https://github.com/mynameischaos/Lion)**   | **181.63** |
|  🥈   | **[Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main)** | **[Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main)** | **175.85** |
|  🥉   |     **[Honeybee](https://arxiv.org/pdf/2312.06742.pdf)**     |   **[Vicuna-13B](https://github.com/kakaobrain/honeybee)**   | **170.07** |
|  4   |   [AGILMM](https://github.com/AIResearchEnthusiast/AGILMM)   |  [Bloom-7B](https://github.com/AIResearchEnthusiast/AGILMM)  |   169.05   |
|  5   |          [CVLM](https://github.com/buptlihang/CVLM)          |       [Vicuna-13B](https://github.com/buptlihang/CVLM)       |   162.24   |
|  6   |          [Kanva](https://github.com/llp1992/Kanva)           |         [Qwen-14B](https://github.com/llp1992/Kanva)         |   140.82   |
|  7   | [Octopus](https://github.com/gray311/UnifiedMultimodalInstructionTuning) | [MPT7B](https://github.com/gray311/UnifiedMultimodalInstructionTuning) |   138.10   |

### Celebrity

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   | **[AGILMM](https://github.com/AIResearchEnthusiast/AGILMM)** | **[Bloom-7B](https://github.com/AIResearchEnthusiast/AGILMM)** | **196.47** |
|  🥈   |     **[Honeybee](https://arxiv.org/pdf/2312.06742.pdf)**     |   **[Vicuna-13B](https://github.com/kakaobrain/honeybee)**   | **177.06** |
|  🥉   | **[Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main)** | **[Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main)** | **160.29** |
|  4   |          [CVLM](https://github.com/buptlihang/CVLM)          |       [Vicuna-13B](https://github.com/buptlihang/CVLM)       |   155.88   |
|  5   |        [Lion](https://github.com/mynameischaos/Lion)         |     [InternLM-7B](https://github.com/mynameischaos/Lion)     |   150.59   |
|  6   |          [Kanva](https://github.com/llp1992/Kanva)           |         [Qwen-14B](https://github.com/llp1992/Kanva)         |   145.00   |
|  7   | [Octopus](https://github.com/gray311/UnifiedMultimodalInstructionTuning) | [MPT7B](https://github.com/gray311/UnifiedMultimodalInstructionTuning) |   129.41   |

### Scene

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   | **[AGILMM](https://github.com/AIResearchEnthusiast/AGILMM)** | **[Bloom-7B](https://github.com/AIResearchEnthusiast/AGILMM)** | **191.75** |
|  🥈   |        **[Kanva](https://github.com/llp1992/Kanva)**         |       **[Qwen-14B](https://github.com/llp1992/Kanva)**       | **179.75** |
|  🥉   |        **[CVLM](https://github.com/buptlihang/CVLM)**        |     **[Vicuna-13B](https://github.com/buptlihang/CVLM)**     | **162.75** |
|  4   |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     |   162.00   |
|  5   |        [Lion](https://github.com/mynameischaos/Lion)         |     [InternLM-7B](https://github.com/mynameischaos/Lion)     |   159.00   |
|  6   | [Octopus](https://github.com/gray311/UnifiedMultimodalInstructionTuning) | [MPT7B](https://github.com/gray311/UnifiedMultimodalInstructionTuning) |   157.25   |
|  7   | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) |   138.89   |

### Landmark

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   | **[AGILMM](https://github.com/AIResearchEnthusiast/AGILMM)** | **[Bloom-7B](https://github.com/AIResearchEnthusiast/AGILMM)** | **196.25** |
|  🥈   |        **[Kanva](https://github.com/llp1992/Kanva)**         |       **[Qwen-14B](https://github.com/llp1992/Kanva)**       | **184.34** |
|  🥉   |      **[Lion](https://github.com/mynameischaos/Lion)**       |   **[InternLM-7B](https://github.com/mynameischaos/Lion)**   | **173.00** |
|  4   |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     |   172.25   |
|  5   |          [CVLM](https://github.com/buptlihang/CVLM)          |       [Vicuna-13B](https://github.com/buptlihang/CVLM)       |   169.50   |
|  6   | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) |   127.04   |
|  7   | [Octopus](https://github.com/gray311/UnifiedMultimodalInstructionTuning) | [MPT7B](https://github.com/gray311/UnifiedMultimodalInstructionTuning) |   126.00   |

### Artwork

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   | **[AGILMM](https://github.com/AIResearchEnthusiast/AGILMM)** | **[Bloom-7B](https://github.com/AIResearchEnthusiast/AGILMM)** | **185.00** |
|  🥈   |        **[Kanva](https://github.com/llp1992/Kanva)**         |       **[Qwen-14B](https://github.com/llp1992/Kanva)**       | **167.00** |
|  🥉   |     **[Honeybee](https://arxiv.org/pdf/2312.06742.pdf)**     |   **[Vicuna-13B](https://github.com/kakaobrain/honeybee)**   | **134.75** |
|  5   |        [Lion](https://github.com/mynameischaos/Lion)         |     [InternLM-7B](https://github.com/mynameischaos/Lion)     |   130.75   |
|  6   |          [CVLM](https://github.com/buptlihang/CVLM)          |       [Vicuna-13B](https://github.com/buptlihang/CVLM)       |   127.75   |
|  7   | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) |   114.51   |
|  8   | [Octopus](https://github.com/gray311/UnifiedMultimodalInstructionTuning) | [MPT7B](https://github.com/gray311/UnifiedMultimodalInstructionTuning) |   95.00    |

### OCR

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   | **[Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main)** | **[Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main)** | **162.50** |
|  🥈   |        **[CVLM](https://github.com/buptlihang/CVLM)**        |     **[Vicuna-13B](https://github.com/buptlihang/CVLM)**     | **155.00** |
|  🥈   |     **[Honeybee](https://arxiv.org/pdf/2312.06742.pdf)**     |   **[Vicuna-13B](https://github.com/kakaobrain/honeybee)**   | **155.00** |
|  🥉   |        **[Kanva](https://github.com/llp1992/Kanva)**         |       **[Qwen-14B](https://github.com/llp1992/Kanva)**       | **152.50** |
|  5   |   [AGILMM](https://github.com/AIResearchEnthusiast/AGILMM)   |  [Bloom-7B](https://github.com/AIResearchEnthusiast/AGILMM)  |   147.50   |
|  6   |        [Lion](https://github.com/mynameischaos/Lion)         |     [InternLM-7B](https://github.com/mynameischaos/Lion)     |   72.50    |
|  7   | [Octopus](https://github.com/gray311/UnifiedMultimodalInstructionTuning) | [MPT7B](https://github.com/gray311/UnifiedMultimodalInstructionTuning) |   65.00    |

## Cognition

Sum of the scores of all cognition subtasks, including commonsense reasoning, numerical calculation, text translation, and code reasoning. The full score of each subtask is 200, and that of all cognition is 800.

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |        **[CVLM](https://github.com/buptlihang/CVLM)**        |     **[Vicuna-13B](https://github.com/buptlihang/CVLM)**     | **488.93** |
|  🥈   | **[AGILMM](https://github.com/AIResearchEnthusiast/AGILMM)** | **[Bloom-7B](https://github.com/AIResearchEnthusiast/AGILMM)** | **448.57** |
|  🥉   |      **[Lion](https://github.com/mynameischaos/Lion)**       |   **[InternLM-7B](https://github.com/mynameischaos/Lion)**   | **445.71** |
|  4   | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) |   356.43   |
|  5   |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     |   315.36   |
|  6   | [Octopus](https://github.com/gray311/UnifiedMultimodalInstructionTuning) | [MPT7B](https://github.com/gray311/UnifiedMultimodalInstructionTuning) |   312.50   |
|  7   |          [Kanva](https://github.com/llp1992/Kanva)           |         [Qwen-14B](https://github.com/llp1992/Kanva)         |   217.14   |

### Commonsense Reasoning

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   | **[AGILMM](https://github.com/AIResearchEnthusiast/AGILMM)** | **[Bloom-7B](https://github.com/AIResearchEnthusiast/AGILMM)** | **138.57** |
|  🥈   |        **[CVLM](https://github.com/buptlihang/CVLM)**        |     **[Vicuna-13B](https://github.com/buptlihang/CVLM)**     | **131.43** |
|  🥉   | **[Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main)** | **[Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main)** | **126.43** |
|  5   |        [Lion](https://github.com/mynameischaos/Lion)         |     [InternLM-7B](https://github.com/mynameischaos/Lion)     |   125.71   |
|  6   |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     |   122.86   |
|  7   | [Octopus](https://github.com/gray311/UnifiedMultimodalInstructionTuning) | [MPT7B](https://github.com/gray311/UnifiedMultimodalInstructionTuning) |   100.00   |
|  8   |          [Kanva](https://github.com/llp1992/Kanva)           |         [Qwen-14B](https://github.com/llp1992/Kanva)         |   72.14    |

### Numerical Calculation

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |        **[CVLM](https://github.com/buptlihang/CVLM)**        |     **[Vicuna-13B](https://github.com/buptlihang/CVLM)**     | **137.50** |
|  🥈   |      **[Lion](https://github.com/mynameischaos/Lion)**       |   **[InternLM-7B](https://github.com/mynameischaos/Lion)**   | **105.00** |
|  🥉   | **[Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main)** | **[Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main)** | **95.00**  |
|  5   |   [AGILMM](https://github.com/AIResearchEnthusiast/AGILMM)   |  [Bloom-7B](https://github.com/AIResearchEnthusiast/AGILMM)  |   57.50    |
|  5   |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     |   57.50    |
|  6   |          [Kanva](https://github.com/llp1992/Kanva)           |         [Qwen-14B](https://github.com/llp1992/Kanva)         |   50.00    |
|  7   | [Octopus](https://github.com/gray311/UnifiedMultimodalInstructionTuning) | [MPT7B](https://github.com/gray311/UnifiedMultimodalInstructionTuning) |   47.50    |

### Text Translation

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   | **[AGILMM](https://github.com/AIResearchEnthusiast/AGILMM)** | **[Bloom-7B](https://github.com/AIResearchEnthusiast/AGILMM)** | **192.50** |
|  🥈   |      **[Lion](https://github.com/mynameischaos/Lion)**       |   **[InternLM-7B](https://github.com/mynameischaos/Lion)**   | **147.50** |
|  🥈   |        **[CVLM](https://github.com/buptlihang/CVLM)**        |     **[Vicuna-13B](https://github.com/buptlihang/CVLM)**     | **147.50** |
|  🥉   | **[Octopus](https://github.com/gray311/UnifiedMultimodalInstructionTuning)** | **[MPT7B](https://github.com/gray311/UnifiedMultimodalInstructionTuning)** | **102.50** |
|  4   |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     |   87.50    |
|  5   | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) |   80.00    |
|  6   |          [Kanva](https://github.com/llp1992/Kanva)           |         [Qwen-14B](https://github.com/llp1992/Kanva)         |   50.00    |

### Code Reasoning

| Rank |                            Model                             |                           Version                            |   Score   |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :-------: |
|  🏅️   |        **[CVLM](https://github.com/buptlihang/CVLM)**        |     **[Vicuna-13B](https://github.com/buptlihang/CVLM)**     | **72.50** |
|  🥈   |      **[Lion](https://github.com/mynameischaos/Lion)**       |   **[InternLM-7B](https://github.com/mynameischaos/Lion)**   | **67.50** |
|  🥉   | **[Octopus](https://github.com/gray311/UnifiedMultimodalInstructionTuning)** | **[MPT7B](https://github.com/gray311/UnifiedMultimodalInstructionTuning)** | **62.50** |
|  5   |   [AGILMM](https://github.com/AIResearchEnthusiast/AGILMM)   |  [Bloom-7B](https://github.com/AIResearchEnthusiast/AGILMM)  |   60.00   |
|  6   | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) |   55.00   |
|  7   |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     |   47.50   |
|  8   |          [Kanva](https://github.com/llp1992/Kanva)           |         [Qwen-14B](https://github.com/llp1992/Kanva)         |   45.00   |
