# Awesome-Federated-LLM-Learning
This is a collection of research papers for Federated Learning for Large Language Models (FedLLM). And the repository will be continuously updated to track the frontier of FedLLM.


## Table of Contents
- [Published Papers](#item-1)
  - [2024](#item-11)
  - [2023](#item-12)
  - [2022](#item-13)
  - [2021](#item-14)
- [Preprints](#item-2)
  - [2024](#item-21)
  - [2023](#item-22)
  - [2022](#item-23)
- [Applications](#item-3)


<a id="item-1"></a>
## Published Papers

In this section, we will list recent FedLLM papers accepted by top tier AI/ML/Networking conferences and journals.
```
format:
- [title](paper link) [Venue]
  - authors
  - datasets
  - models
  - [code](code link) [slide](slide link) 
```
<a id="item-11"></a>
### 2024

- [Improving LoRA in Privacy-preserving Federated Learning](https://openreview.net/forum?id=NLPzL6HWNl) [ICLR 2024]
  - *authors*: Youbang Sun, Zitao Li, Yaliang Li, Bolin Ding .
  - *datasets*: MNLI, SST2, QNLI , QQP and GSM-8K
  - *models*: RoBERTa, LLaMA 7B
  - code and slide
    
<a id="item-12"></a>
### 2023

- [Federated Learning of Large Language Models with Parameter-Efficient Prompt Tuning and Adaptive Optimization](http://arxiv.org/abs/2310.15080) [EMNLP 2023]
  - *authors*: Tianshi Che, Ji Liu, Yang Zhou, Jiaxiang Ren, Jiwen Zhou, Victor S. Sheng, Huaiyu Dai, Dejing Dou.
  - *datasets*: QNLI, SST-2, CoLA, MRPC, RTE, and BoolQ, MPQA, Subj, TREC, and MR 
  - *models*: RoBERTa, GPT2, LLaMA 7B
  - [code](https://github.com/llm-eff/FedPepTAO) and slide

- [FedPETuning: When Federated Learning Meets the Parameter-Efficient Tuning Methods of Pre-trained Language Models](https://aclanthology.org/2023.findings-acl.632/) [ACL 2023]
  - *authors*: Zhuo Zhang, Yuanhang Yang, Yong Dai, Qifan Wang, Yue Yu, Lizhen Qu, Zenglin Xu.
  - *datasets*: RTE, MRPC, SST-2, QNLI, QQP, MNLI 
  - *models*: RoBERTa
  - [code](https://github.com/SMILELab-FL/FedPETuning) and slide
 
- [Petals: Collaborative Inference and Fine-tuning of Large Models](https://aclanthology.org/2023.acl-demo.54.pdf) [ACL 2023]
  - *authors*: Alexander Borzunov, Dmitry Baranchuk, Tim Dettmers, Maksim Riabinin, Younes Belkada, Artem Chumachenko, Pavel Samygin, Colin Raffel.
  - *datasets*: Synthetic
  - *models*: BLOOM-176B
  - [code](https://github.com/bigscience-workshop/petals) [video](https://www.youtube.com/watch?v=F4muLI-0hTE)


 
<a id="item-13"></a>
### 2022


<a id="item-2"></a>
## Preprints

In this section, we will list high-quality FedLLM preprints that have been uploaded to open-access repositories like ArXiv.

<a id="item-21"></a>
### 2024

- [Federated Fine-tuning of Large Language Models under Heterogeneous Language Tasks and Client Resources](https://arxiv.org/pdf/2402.11505.pdf) [ArXiv 2024]
  - *authors*: Jiamu Bai, Daoyuan Chen, Bingchen Qian, Liuyi Yao, Yaliang Li.
  - *datasets*:  AllenAI natural instruction dataset v2.
  - *models*: LLaMA-1.3B 
  - [code](https://github.com/alibaba/FederatedScope/tree/FlexLoRA) and slide
    
- [OpenFedLLM: Training Large Language Models on Decentralized Private Data via Federated Learning](https://arxiv.org/abs/2402.06954) [ArXiv 2024]
  - *authors*: Rui Ye, Wenhao Wang, Jingyi Chai, Dihan Li, Zexi Li, Yinda Xu, Yaxin Du, Yanfeng Wang, Siheng Chen.
  - *datasets*: Alpaca, Alpaca-GPT4, FinGPT, MedAlpaca, CodeMathInstruct, UltraFeedback, HH-RLHF 
  - *models*: LLaMA-7B
  - [code](https://github.com/rui-ye/OpenFedLLM) and slide
    
- [On the Convergence of Zeroth-Order Federated Tuning for Large Language Models](https://arxiv.org/abs/2402.05926) [ArXiv 2024]
  - *authors*: Zhenqing Ling, Daoyuan Chen, Liuyi Yao, Yaliang Li, Ying Shen.
  - *datasets*: Databricks-dolly-15k, GSM8K, CodeAlpaca, Alpaca
  - *models*: LLaMA-3B
  - [code](https://github.com/alibaba/FederatedScope/tree/FedMeZO) and slide

- [Federated Full-Parameter Tuning of Billion-Sized Language Models with Communication Cost under 18 Kilobytes](https://arxiv.org/abs/2312.06353) [ArXiv 2024]
  - *authors*: Zhen Qin, Daoyuan Chen, Bingchen Qian, Bolin Ding, Yaliang Li, Shuiguang Deng.
  - *datasets*: Natural Instructions and Dolly-15K.
  - *models*: DataJuicer-1.3B, LLaMA-3B.
  - [code](https://github.com/alibaba/FederatedScope/tree/FedKSeed) and slide

- [Towards Building the Federated GPT: Federated Instruction Tuning](https://arxiv.org/abs/2305.05644) [ArXiv 2024]
  - *authors*: Jianyi Zhang, Saeed Vahidian, Martin Kuo, Chunyuan Li, Ruiyi Zhang, Tong Yu, Yufan Zhou, Guoyin Wang, Yiran Chen.
  - *datasets*: Dolly-15K.
  - *models*: Shepherd-7B.
  - [code](https://github.com/JayZhang42/FederatedGPT-Shepherd) and slide
    
<a id="item-22"></a>
### 2023
- [FederatedScope-LLM: A Comprehensive Package for Fine-tuning Large Language Models in Federated Learning](https://arxiv.org/abs/2309.00363) [ArXiv 2023]
  - *authors*: Weirui Kuang, Bingchen Qian, Zitao Li, Daoyuan Chen, Dawei Gao, Xuchen Pan, Yuexiang Xie, Yaliang Li, Bolin Ding, Jingren Zhou.
  - *datasets*: Databricks-dolly-15k, GSM8K.
  - *models*:  LLaMA-7B
  - [code](https://github.com/alibaba/FederatedScope/tree/llm) and slide

- [FATE-LLM: A Industrial Grade Federated Learning Framework for Large Language Models](https://arxiv.org/abs/2310.10049) [ArXiv 2023]
  - *authors*: Tao Fan, Yan Kang, Guoqiang Ma, Weijing Chen, Wenbin Wei, Lixin Fan, Qiang Yang.
  - *datasets*: AdvertiseGen.
  - *models*: BERT, GPTs, ChatGLM-6B, LLaMA, BLOOM, Baichuan
  - [code](https://github.com/FederatedAI/FATE-LLM) and slide

<a id="item-23"></a>
### 2022

<a id="item-3"></a>
## Applications

- [Large Language Models Empowered Autonomous Edge AI for Connected Intelligence](https://arxiv.org/abs/2307.02779) [IEEE Communication Magazine]
  - *authors*: Yifei Shen, Jiawei Shao, Xinjie Zhang, Zehong Lin, Hao Pan, Dongsheng Li, Jun Zhang, Khaled B. Letaief.
