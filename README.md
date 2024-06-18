# Awesome Federated Learning for LLMs
This is a collection of research papers for Federated Learning for Large Language Models (FedLLM). The repository will be continuously updated to track the frontier of FedLLM.

<img src="mindmap.png" align="center" alt="drawing" width="600"/>

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

- [PrE-Text: Training Language Models on Private Federated Data in the Age of LLMs](https://arxiv.org/abs/2406.02958) [ICML 2024]
  - *authors*: Charlie Hou, Akshat Shrivastava, Hongyuan Zhan, Rylan Conway, Trang Le, Adithya Sagar, Giulia Fanti, Daniel Lazar
  - *datasets*: C4
  - *models*: DistilGPT2 
  - code and slide
  - 
- [Analysis of Privacy Leakage in Federated Large Language Models](https://arxiv.org/abs/2403.04784) [AISTATS 2024]
  - *authors*: Minh N. Vu, Truc Nguyen, Tre' R. Jeter, My T. Thai
  - *datasets*: IMDB review, Yelp review, Twitter-emotion, and Finance
  - *models*: BERT, RoBERTa , distilBERT, GPT1, GPT2
  - code and slide
    
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

- [Pre-Training and Personalized Fine-Tuning via Over-the-Air Federated Meta-Learning: Convergence-Generalization Trade-Offs](https://arxiv.org/abs/2406.11569) [Arxiv 2024]
  - *authors*: Haifeng Wen, Hong Xing, Osvaldo Simeone
  - *datasets*:  
  - *models*:  
 
- [Save It All: Enabling Full Parameter Tuning for Federated Large Language Models via Cycle Black Gradient Descent](https://arxiv.org/abs/2406.11187) [Arxiv 2024]
  - *authors*: Lin Wang, Zhichao Wang, Xiaoying Tang
  - *datasets*:  GLUE
  - *models*:   GPT2-small, BLOOM, RoBERTa-base, ChatGLM3-6B and LLaMA2-7B

- [Thinking Forward: Memory-Efficient Federated Finetuning of Language Models](https://arxiv.org/abs/2405.15551) [Arxiv 2024]
  - *authors*: Kunjal Panchal, Nisarg Parikh, Sunav Choudhary, Lijun Zhang, Yuriy Brun, Hui Guan
  - *datasets*:  AG News, SST2, Yelp, SQuADv2,...
  - *models*:   Llama2-7B
  -     
- [Personalized Wireless Federated Learning for Large Language Models](https://arxiv.org/abs/2404.13238) [Arxiv 2024]
  - *authors*: Feibo Jiang, Li Dong, Siwei Tu, Yubo Peng, Kezhi Wang, Kun Yang, Cunhua Pan, Dusit Niyato
  - *datasets*:  
  - *models*:  GPT-2
 
- [Automated Federated Pipeline for Parameter-Efficient Fine-Tuning of Large Language Models](https://arxiv.org/abs/2404.06448) [Arxiv 2024]
  - *authors*: Zihan Fang, Zheng Lin, Zhe Chen, Xianhao Chen, Yue Gao, Yuguang Fang
  - *datasets*: 20NEWS, E2E
  - *models*:  Bert and GPT-2

- [Dual-Personalizing Adapter for Federated Foundation Models](https://arxiv.org/abs/2403.19211) [Arxiv 2024]
  - *authors*: Yiyuan Yang, Guodong Long, Tao Shen, Jing Jiang, Michael Blumenstein
  - *datasets*: Flan  
  - *models*:  LLaMA-7B
  - 
- [FedRDMA: Communication-Efficient Cross-Silo Federated LLM via Chunked RDMA Transmission](https://arxiv.org/abs/2403.00881) [Arxiv 2024]
  - *authors*: Zeling Zhang, Dongqi Cai, Yiran Zhang, Mengwei Xu, Shangguang Wang, Ao Zhou
  - *datasets*: AdvertiseGen 
  - *models*:  GPT2

- [Privacy-Aware Semantic Cache for Large Language Models](https://arxiv.org/abs/2403.02694) [Arxiv 2024]
  - *authors*: Waris Gill, Mohamed Elidrisi, Pallavi Kalapatapu, Ali Anwar, Muhammad Ali Gulzar 
  - *datasets*: GPTCache dataset
  - *models*:  Llama 2, MPNet, Albert
 
- [Analysis of Privacy Leakage in Federated Large Language Models](https://arxiv.org/abs/2403.04784) [Arxiv 2024]
  - *authors*: Minh N. Vu, Truc Nguyen, Tre' R. Jeter, My T. Thai.
  - *datasets*: IMDB, Yelp
  - *models*:  RoBERTa, DistilBERT, GPT, GPT2
    
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

- [Asynchronous Local-SGD Training for Language Modeling](https://arxiv.org/abs/2401.09135) [ArXiv 2024]
  - *authors*: Bo Liu, Rachita Chhaparia, Arthur Douillard, Satyen Kale, Andrei A. Rusu, Jiajun Shen, Arthur Szlam, Marc'Aurelio Ranzato.
  - *datasets*:  C4 dataset.
  - *models*:  150M Model
    
<a id="item-22"></a>
### 2023

- [DiLoCo: Distributed Low-Communication Training of Language Models](https://arxiv.org/abs/2311.08105) [ArXiv 2023]
  - *authors*: Arthur Douillard, Qixuan Feng, Andrei A. Rusu, Rachita Chhaparia, Yani Donchev, Adhiguna Kuncoro, Marc'Aurelio Ranzato, Arthur Szlam, Jiajun Shen.
  - *datasets*:  C4 dataset.
  - *models*:  150M Model

- [Federated Generative Learning with Foundation Models](https://openreview.net/forum?id=U0P622bfUN) [OpenReview 2023]
  - *authors*: Jie Zhang, Xiao hua Qi, Shengyuan Pang, Siyuan Pan, Xiaobing Tu, Pengfei Wan, Bo Zhao.
  - *datasets*: ImageNet and DomainNet .
  - *models*:  

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

- [Prompt Public Large Language Models to Synthesize Data for Private On-device Applications](https://arxiv.org/abs/2404.04360) [Arxiv 2024]
  - *authors*: Shanshan Wu, Zheng Xu, Yanxiang Zhang, Yuanbo Zhang, Daniel Ramage
  - *datasets*: LLM-mix-166G
  - *models*:  
 
- [FedPrompt: Communication-Efficient and Privacy Preserving Prompt Tuning in Federated Learning](https://arxiv.org/abs/2208.12268) [ICASSP 2023]
  - *authors*: Haodong Zhao, Wei Du, Fangqi Li, Peixuan Li, Gongshen Liu
    
- [Visual Prompt Based Personalized Federated Learning](https://arxiv.org/abs/2303.08678) [TMLR 2023]
  - *authors*: Guanghao Li, Wansen Wu, Yan Sun, Li Shen, Baoyuan Wu, Dacheng Tao
    
- [Prompt Federated Learning for Weather Forecasting: Toward Foundation Models on Meteorological Data](https://arxiv.org/abs/2301.09152) [IJCAI 2023]
  - *authors*: Shengchao Chen, Guodong Long, Tao Shen, Jing Jiang
    
- [Large Language Models Empowered Autonomous Edge AI for Connected Intelligence](https://arxiv.org/abs/2307.02779) [IEEE Communication Magazine]
  - *authors*: Yifei Shen, Jiawei Shao, Xinjie Zhang, Zehong Lin, Hao Pan, Dongsheng Li, Jun Zhang, Khaled B. Letaief.
