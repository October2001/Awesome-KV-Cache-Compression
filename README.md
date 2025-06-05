<div align="center">
<img src="./logo.png" width=90%>
</div>

<div align="center">
   
[![LICENSE](https://img.shields.io/github/license/October2001/Awesome-KV-Cache-Compression)](https://github.com/October2001/Awesome-KV-Cache-Compression/blob/main/LICENSE)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![commit](https://img.shields.io/github/last-commit/October2001/Awesome-KV-Cache-Compression?color=blue)](https://github.com/October2001/Awesome-KV-Cache-Compression/commits/main)
[![PR](https://img.shields.io/badge/PRs-Welcome-red)](https://github.com/October2001/Awesome-KV-Cache-Compression/pulls)
[![GitHub Repo stars](https://img.shields.io/github/stars/October2001/Awesome-KV-Cache-Compression)](https://github.com/October2001/Awesome-KV-Cache-Compression)

</div>

## 📢 News
🎉 [2024-07-23] Project Beginning 🥳

## 📜 Notice

This repository is constantly updating 🤗 ...
> You can directly click on the title to jump to the corresponding PDF link location

## ⚙️ Project
1. [**kvpress.**](https://github.com/NVIDIA/kvpress) *NVIDIA.* [![GitHub Repo stars](https://img.shields.io/github/stars/NVIDIA/kvpress)](https://github.com/NVIDIA/kvpress)
* This repository implements multiple KV cache pruning methods and benchmarks using 🤗 transformers.

2. [**KVCache-Factory.**](https://github.com/Zefan-Cai/KVCache-Factory) [![GitHub Repo stars](https://img.shields.io/github/stars/Zefan-Cai/KVCache-Factory)](https://github.com/Zefan-Cai/KVCache-Factory)
* Unified KV Cache Compression Methods for Auto-Regressive Models.

## 📷 Survey

1. [**Keep the Cost Down: A Review on Methods to Optimize LLM' s KV-Cache Consumption.**](https://arxiv.org/abs/2407.18003) *Shi Luohe, Zhang Hongyi, Yao Yao, Li Zuchao, Zhao Hai.* COLM 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/zcli-charlie/Awesome-KV-Cache)](https://github.com/zcli-charlie/Awesome-KV-Cache)

2. [**Prompt Compression for Large Language Models: A Survey.**](https://arxiv.org/abs/2410.12388) *Zongqian Li, Yinhong Liu, Yixuan Su, Nigel Collier.* Arxiv 2024.
   
3. [**A Survey on Large Language Model Acceleration based on KV Cache Management.**](https://arxiv.org/abs/2412.19442) *Haoyang Li, Yiming Li, Anxin Tian, Tianhao Tang, Zhanchao Xu, Xuejia Chen, Nicole Hu, Wei Dong, Qing Li, Lei Chen.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/TreeAI-Lab/Awesome-KV-Cache-Management)](https://github.com/TreeAI-Lab/Awesome-KV-Cache-Management)


## 🔍 Method

### 1️⃣ Pruning / Evicting / Sparse

1. [**Scissorhands: Exploiting the Persistence of Importance Hypothesis for LLM KV Cache Compression at Test Time.**](https://arxiv.org/abs/2305.17118) *Zichang Liu, Aditya Desai, Fangshuo Liao, Weitao Wang, Victor Xie, Zhaozhuo Xu, Anastasios Kyrillidis, Anshumali Shrivastava.* NeurIPS 2023. 

2. [**SnapKV: LLM Knows What You are Looking for Before Generation.**](https://arxiv.org/abs/2404.14469) *Yuhong Li, Yingbing Huang, Bowen Yang, Bharat Venkitesh, Acyr Locatelli, Hanchen Ye, Tianle Cai, Patrick Lewis, Deming Chen.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/FasterDecoding/SnapKV)](https://github.com/FasterDecoding/SnapKV)

3. [**H2O: Heavy-Hitter Oracle for Efficient Generative Inference of Large Language Models.**](https://arxiv.org/abs/2306.14048) *Zhenyu Zhang, Ying Sheng, Tianyi Zhou, Tianlong Chen, Lianmin Zheng, Ruisi Cai, Zhao Song, Yuandong Tian, Christopher Ré, Clark Barrett, Zhangyang Wang, Beidi Chen.* NeurIPS 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/FMInference/H2O)](https://github.com/FMInference/H2O)

4. [**Model Tells You What to Discard: Adaptive KV Cache Compression for LLMs.**](https://arxiv.org/abs/2310.01801) *Suyu Ge, Yunan Zhang, Liyuan Liu, Minjia Zhang, Jiawei Han, Jianfeng Gao.* ICLR 2024.

5. [**PyramidInfer: Pyramid KV Cache Compression for High-throughput LLM Inference.**](https://arxiv.org/abs/2405.12532) *Dongjie Yang, XiaoDong Han, Yan Gao, Yao Hu, Shilin Zhang, Hai Zhao.* ACL 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/mutonix/pyramidinfer)](https://github.com/mutonix/pyramidinfer)

6. [**PyramidKV: Dynamic KV Cache Compression based on Pyramidal Information Funneling.**](https://arxiv.org/abs/2406.02069) *Zefan Cai, Yichi Zhang, Bofei Gao, Yuliang Liu, Tianyu Liu, Keming Lu, Wayne Xiong, Yue Dong, Baobao Chang, Junjie Hu, Wen Xiao.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Zefan-Cai/PyramidKV)](https://github.com/Zefan-Cai/PyramidKV)

7. [**Transformers are Multi-State RNNs.**](https://arxiv.org/abs/2401.06104) *Matanel Oren, Michael Hassid, Nir Yarden, Yossi Adi, Roy Schwartz.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/schwartz-lab-NLP/TOVA)](https://github.com/schwartz-lab-NLP/TOVA)

8. [**Efficient Streaming Language Models with Attention Sinks.**](https://arxiv.org/abs/2309.17453) *Guangxuan Xiao, Yuandong Tian, Beidi Chen, Song Han, Mike Lewis.* ICLR 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/mit-han-lab/streaming-llm)](https://github.com/mit-han-lab/streaming-llm)

9. [**A Simple and Effective L2 Norm-Based Strategy for KV Cache Compression.**](https://arxiv.org/abs/2406.11430) *Alessio Devoto, Yu Zhao, Simone Scardapane, Pasquale Minervini.* EMNLP 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/alessiodevoto/l2compress)](https://github.com/alessiodevoto/l2compress)

10. [**Retrieval Head Mechanistically Explains Long-Context Factuality.**](https://arxiv.org/abs/2404.15574) *Wenhao Wu, Yizhong Wang, Guangxuan Xiao, Hao Peng, Yao Fu.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/nightdessert/Retrieval_Head)](https://github.com/nightdessert/Retrieval_Head)

11. [**Efficient Sparse Attention needs Adaptive Token Release.**](https://arxiv.org/abs/2407.02328) *Chaoran Zhang, Lixin Zou, Dan Luo, Min Tang, Xiangyang Luo, Zihao Li, Chenliang Li.* ACL 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/WHUIR/ADORE)](https://github.com/WHUIR/ADORE)

12. [**Loki: Low-Rank Keys for Efficient Sparse Attention.**](https://arxiv.org/abs/2406.02542) *Prajwal Singhania, Siddharth Singh, Shwai He, Soheil Feizi, Abhinav Bhatele.* Arxiv 2024.

13. [**Get More with LESS: Synthesizing Recurrence with KV Cache Compression for Efficient LLM Inference.**](https://arxiv.org/abs/2402.09398) *Harry Dong, Xinyu Yang, Zhenyu Zhang, Zhangyang Wang, Yuejie Chi, Beidi Chen.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/hdong920/LESS)](https://github.com/hdong920/LESS)

14. [**ALISA: Accelerating Large Language Model Inference via Sparsity-Aware KV Caching.**](https://arxiv.org/abs/2403.17312) *Youpeng Zhao, Di Wu, Jun Wang.* ISCA 2024.

15. [**Keyformer: KV Cache Reduction through Key Tokens Selection for Efficient Generative Inference.**](https://arxiv.org/abs/2403.09054) *Muhammad Adnan, Akhil Arunkumar, Gaurav Jain, Prashant J. Nair, Ilya Soloveychik, Purushotham Kamath.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/d-matrix-ai/keyformer-llm)](https://github.com/d-matrix-ai/keyformer-llm)

16. [**Ada-KV: Optimizing KV Cache Eviction by Adaptive Budget Allocation for Efficient LLM Inference.**](https://arxiv.org/abs/2407.11550) *Yuan Feng, Junlin Lv, Yukun Cao, Xike Xie, S. Kevin Zhou.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/FFY0/AdaKV)](https://github.com/FFY0/AdaKV)

17. [**Attention Score is not All You Need for Token Importance Indicator in KV Cache Reduction: Value Also Matters.**](https://arxiv.org/abs/2406.12335) *Zhiyu Guo, Hidetaka Kamigaito, Taro Watanabe.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/guozhiyu/vatp)](https://github.com/guozhiyu/vatp)

18. [**On the Efficacy of Eviction Policy for Key-Value Constrained Generative Language Model Inference.**](https://arxiv.org/abs/2406.12335) *Siyu Ren, Kenny Q. Zhu.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/DRSY/EasyKV)](https://github.com/DRSY/EasyKV)

19. [**CORM: Cache Optimization with Recent Message for Large Language Model Inference.**](https://arxiv.org/abs/2404.15949) *Jincheng Dai, Zhuowei Huang, Haiyun Jiang, Chen Chen, Deng Cai, Wei Bi, Shuming Shi.* Arxiv 2024.
    
20. [**RazorAttention: Efficient KV Cache Compression Through Retrieval Heads.**](https://www.arxiv.org/abs/2407.15891) *Hanlin Tang, Yang Lin, Jing Lin, Qingsen Han, Shikuan Hong, Yiwu Yao, Gongyi Wang.* Arxiv 2024.

21. [**A2SF: Accumulative Attention Scoring with Forgetting Factor for Token Pruning in Transformer Decoder.**](https://arxiv.org/abs/2407.20485) *Hyun Rae Jo, Dong Kun Shin.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Dirac-Notation/A2SF)](https://github.com/Dirac-Notation/A2SF)

22. [**Quest: Query-Aware Sparsity for Efficient Long-Context LLM Inference.**](https://arxiv.org/abs/2406.10774) *Jiaming Tang, Yilong Zhao, Kan Zhu, Guangxuan Xiao, Baris Kasikci, Song Han.* ICML 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/mit-han-lab/Quest)](https://github.com/mit-han-lab/Quest)

23. [**LazyLLM: Dynamic Token Pruning for Efficient Long Context LLM Inference.**](https://arxiv.org/abs/2407.14057) *Qichen Fu, Minsik Cho, Thomas Merth, Sachin Mehta, Mohammad Rastegari, Mahyar Najibi.* Arxiv 2024.

24. [**NACL: A General and Effective KV Cache Eviction Framework for LLMs at Inference Time.**](https://arxiv.org/abs/2408.03675) *Yilong Chen, Guoxia Wang, Junyuan Shang, Shiyao Cui, Zhenyu Zhang, Tingwen Liu, Shuohuan Wang, Yu Sun, Dianhai Yu, Hua Wu.* ACL 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/PaddlePaddle/Research)](https://github.com/PaddlePaddle/Research/tree/master/NLP/ACL2024-NACL)

25. [**Post-Training Sparse Attention with Double Sparsity.**](https://arxiv.org/abs/2408.07092) *Shuo Yang, Ying Sheng, Joseph E. Gonzalez, Ion Stoica, Lianmin Zheng.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/andy-yang-1/DoubleSparse)](https://github.com/andy-yang-1/DoubleSparse)

26. [**Farewell to Length Extrapolation, a Training-Free Infinite Context with Finite Attention Scope.**](https://www.arxiv.org/abs/2407.15176) *Xiaoran Liu, Qipeng Guo, Yuerong Song, Zhigeng Liu, Kai Lv, Hang Yan, Linlin Li, Qun Liu, Xipeng Qiu.* Arxiv 2024.

27. [**Dynamic Memory Compression: Retrofitting LLMs for Accelerated Inference.**](https://arxiv.org/abs/2403.09636) *Piotr Nawrot, Adrian Łańcucki, Marcin Chochowski, David Tarjan, Edoardo M. Ponti.* ICML 2024.

28. [**MInference 1.0: Accelerating Pre-filling for Long-Context LLMs via Dynamic Sparse Attention.**](https://arxiv.org/abs/2407.02490) *Huiqiang Jiang, Yucheng Li, Chengruidong Zhang, Qianhui Wu, Xufang Luo, Surin Ahn, Zhenhua Han, Amir H. Abdi, Dongsheng Li, Chin-Yew Lin, Yuqing Yang, Lili Qiu.* NeurIPS 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/MInference)](https://github.com/microsoft/MInference)

29. [**Dynamic Context Pruning for Efficient and Interpretable Autoregressive Transformers.**](https://arxiv.org/abs/2305.15805) *Sotiris Anagnostidis, Dario Pavllo, Luca Biggio, Lorenzo Noci, Aurelien Lucchi, Thomas Hofmann.* NeurIPS 2023.

30. [**RetrievalAttention: Accelerating Long-Context LLM Inference via Vector Retrieval.**](https://arxiv.org/abs/2409.10516) *Di Liu, Meng Chen, Baotong Lu, Huiqiang Jiang, Zhenhua Han, Qianxi Zhang, Qi Chen, Chengruidong Zhang, Bailu Ding, Kai Zhang, Chen Chen, Fan Yang, Yuqing Yang, Lili Qiu.* Arxiv 2024.

31. [**Sirius: Contextual Sparsity with Correction for Efficient LLMs.**](https://www.arxiv.org/abs/2409.03856) *Yang Zhou, Zhuoming Chen, Zhaozhuo Xu, Victoria Lin, Beidi Chen.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/infini-ai-lab/sirius)](https://github.com/infini-ai-lab/sirius)

32. [**Inf-MLLM: Efficient Streaming Inference of Multimodal Large Language Models on a Single GPU.**](https://www.arxiv.org/abs/2409.09086) *Zhenyu Ning, Jieru Zhao, Qihao Jin, Wenchao Ding, Minyi Guo.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/infly-ai/INF-MLLM)](https://github.com/infly-ai/INF-MLLM)

33. [**Training-Free Activation Sparsity in Large Language Models.**](https://www.arxiv.org/abs/2408.14690) *James Liu, Pragaash Ponnusamy, Tianle Cai, Han Guo, Yoon Kim, Ben Athiwaratkun.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/FasterDecoding/TEAL)](https://github.com/FasterDecoding/TEAL)

34. [**KVPruner: Structural Pruning for Faster and Memory-Efficient Large Language Models.**](https://www.arxiv.org/abs/2409.11057) *Bo Lv, Quan Zhou, Xuanang Ding, Yan Wang, Zeming Ma.* Arxiv 2024.

35. [**CritiPrefill: A Segment-wise Criticality-based Approach for Prefilling Acceleration in LLMs.**](https://www.arxiv.org/abs/2409.12490) *Junlin Lv, Yuan Feng, Xike Xie, Xin Jia, Qirong Peng, Guiming Xie.* Arxiv 2024.

36. [**Discovering the Gems in Early Layers: Accelerating Long-Context LLMs with 1000x Input Token Reduction.**](https://arxiv.org/abs/2409.17422) *Zhenmei Shi, Yifei Ming, Xuan-Phi Nguyen, Yingyu Liang, Shafiq Joty.* Arxiv 2024.

37. [**KV-Compress: Paged KV-Cache Compression with Variable Compression Rates per Attention Head.**](https://arxiv.org/abs/2410.00161) *Isaac Rehg.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/IsaacRe/vllm-kvcompress)](https://github.com/IsaacRe/vllm-kvcompress)

38. [**InfiniPot: Infinite Context Processing on Memory-Constrained LLMs.**](https://arxiv.org/abs/2410.01518) *Minsoo Kim, Kyuhong Shim, Jungwook Choi, Simyung Chang.* EMNLP 2024.

39. [**Locret: Enhancing Eviction in Long-Context LLM Inference with Trained Retaining Heads.**](https://arxiv.org/abs/2410.01805) *Yuxiang Huang, Binhang Yuan, Xu Han, Chaojun Xiao, Zhiyuan Liu.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/huangyuxiang03/Locret)](https://github.com/huangyuxiang03/Locret)

40. [**SparseVLM: Visual Token Sparsification for Efficient Vision-Language Model Inference.**](https://arxiv.org/abs/2410.04417) *Yuan Zhang, Chun-Kai Fan, Junpeng Ma, Wenzhao Zheng, Tao Huang, Kuan Cheng, Denis Gudovskiy, Tomoyuki Okuno, Yohei Nakata, Kurt Keutzer, Shanghang Zhang.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Gumpest/SparseVLMs)](https://github.com/Gumpest/SparseVLMs)

41. [**LoCoCo: Dropping In Convolutions for Long Context Compression.**](https://arxiv.org/abs/2406.05317) *Ruisi Cai, Yuandong Tian, Zhangyang Wang, Beidi Chen.* ICML 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/VITA-Group/LoCoCo)](https://github.com/VITA-Group/LoCoCo)

42. [**DuoAttention: Efficient Long-Context LLM Inference with Retrieval and Streaming Heads.**](https://arxiv.org/abs/2410.10819) *Guangxuan Xiao, Jiaming Tang, Jingwei Zuo, Junxian Guo, Shang Yang, Haotian Tang, Yao Fu, Song Han.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/mit-han-lab/duo-attention)](https://github.com/mit-han-lab/duo-attention)

43. [**SimLayerKV: A Simple Framework for Layer-Level KV Cache Reduction.**](https://arxiv.org/abs/2410.13846) *Xuan Zhang, Cunxiao Du, Chao Du, Tianyu Pang, Wei Gao, Min Lin.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/sail-sg/SimLayerKV)](https://github.com/sail-sg/SimLayerKV)

44. [**In-context KV-Cache Eviction for LLMs via Attention-Gate.**](https://arxiv.org/abs/2410.12876) *Zihao Zeng, Bokai Lin, Tianqi Hou, Hao Zhang, Zhijie Deng.* Arxiv 2024.

45. [**CacheGen: KV Cache Compression and Streaming for Fast Large Language Model Serving.**](https://arxiv.org/abs/2310.07240) *Yuhan Liu, Hanchen Li, Yihua Cheng, Siddhant Ray, Yuyang Huang, Qizheng Zhang, Kuntai Du, Jiayi Yao, Shan Lu, Ganesh Ananthanarayanan, Michael Maire, Henry Hoffmann, Ari Holtzman, Junchen Jiang.* ACM SIGCOMM 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/LMCache/LMCache)](https://github.com/LMCache/LMCache)

46. [**MagicPIG: LSH Sampling for Efficient LLM Generation.**](https://arxiv.org/abs/2410.16179) *Zhuoming Chen, Ranajoy Sadhukhan, Zihao Ye, Yang Zhou, Jianyu Zhang, Niklas Nolte, Yuandong Tian, Matthijs Douze, Leon Bottou, Zhihao Jia, Beidi Chen.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Infini-AI-Lab/MagicPIG)](https://github.com/Infini-AI-Lab/MagicPIG)

47. [**TidalDecode: Fast and Accurate LLM Decoding with Position Persistent Sparse Attention.**](https://arxiv.org/abs/2410.05076) *Lijie Yang, Zhihao Zhang, Zhuofu Chen, Zikun Li, Zhihao Jia.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/DerrickYLJ/TidalDecode)](https://github.com/DerrickYLJ/TidalDecode)

48. [**ShadowKV: KV Cache in Shadows for High-Throughput Long-Context LLM Inference.**](https://arxiv.org/abs/2410.21465) *Hanshi Sun, Li-Wen Chang, Wenlei Bao, Size Zheng, Ningxin Zheng, Xin Liu, Harry Dong, Yuejie Chi, Beidi Chen.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/bytedance/ShadowKV)](https://github.com/bytedance/ShadowKV)

49. [**BUZZ: Beehive-structured Sparse KV Cache with Segmented Heavy Hitters for Efficient LLM Inference.**](https://arxiv.org/abs/2410.23079) *Junqi Zhao, Zhijin Fang, Shu Li, Shaohui Yang, Shichao He.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/JunqiZhao888/buzz-llm)](https://github.com/JunqiZhao888/buzz-llm)

50. [**CItruS: Chunked Instruction-aware State Eviction for Long Sequence Modeling.**](https://arxiv.org/abs/2406.12018) *Yu Bai, Xiyuan Zou, Heyan Huang, Sanxing Chen, Marc-Antoine Rondeau, Yang Gao, Jackie Chi Kit Cheung.* EMNLP 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/ybai-nlp/CItruS)](https://github.com/ybai-nlp/CItruS)

51. [**TokenSelect: Efficient Long-Context Inference and Length Extrapolation for LLMs via Dynamic Token-Level KV Cache Selection.**](https://arxiv.org/abs/2411.02886) *Wei Wu, Zhuoshi Pan, Chao Wang, Liyi Chen, Yunchu Bai, Kun Fu, Zheng Wang, Hui Xiong.* Arxiv 2024.

52. [**Recycled Attention: Efficient inference for long-context language models.**](https://arxiv.org/abs/2411.05787) *Fangyuan Xu, Tanya Goyal, Eunsol Choi.* Arxiv 2024.

53. [**VL-Cache: Sparsity and Modality-Aware KV Cache Compression for Vision-Language Model Inference Acceleration.**](https://arxiv.org/abs/2410.23317) *Dezhan Tu, Danylo Vashchilenko, Yuzhe Lu, Panpan Xu.* Arxiv 2024.

54. [**Squeezed Attention: Accelerating Long Context Length LLM Inference.**](https://arxiv.org/abs/2411.09688) *Coleman Hooper, Sehoon Kim, Hiva Mohammadzadeh, Monishwaran Maheswaran, June Paik, Michael W. Mahoney, Kurt Keutzer, Amir Gholami.* Arxiv 2024.

55. [**ArkVale: Efficient Generative LLM Inference with Recallable Key-Value Eviction.**](https://github.com/pku-liang/ArkVale/blob/main/media/arkvale-nips24-paper.pdf) *Renze Chen, Zhuofeng Wang, Beiquan Cao, Tong Wu, Size Zheng, Xiuhong Li, Xuechao Wei, Shengen Yan, Meng Li, Yun Liang.* NeurIPS 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/pku-liang/ArkVale)](https://github.com/pku-liang/ArkVale)

56. [**Not All Heads Matter: A Head-Level KV Cache Compression Method with Integrated Retrieval and Reasoning.**](https://arxiv.org/abs/2410.19258) *Yu Fu, Zefan Cai, Abedelkadir Asi, Wayne Xiong, Yue Dong, Wen Xiao.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/FYYFU/HeadKV)](https://github.com/FYYFU/HeadKV)

57. [**[CLS] Attention is All You Need for Training-Free Visual Token Pruning: Make VLM Inference Faster.**](https://arxiv.org/pdf/2412.01818) *Qizhe Zhang, Aosong Cheng, Ming Lu, Zhiyong Zhuo, Minqi Wang, Jiajun Cao, Shaobo Guo, Qi She, Shanghang Zhang.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Theia-4869/FasterVLM)](https://github.com/Theia-4869/FasterVLM)

58. [**Fit and Prune: Fast and Training-free Visual Token Pruning for Multi-modal Large Language Models.**](https://arxiv.org/abs/2409.10197) *Weihao Ye, Qiong Wu, Wenhao Lin, Yiyi Zhou.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Theia-4869/FasterVLM)](https://github.com/ywh187/FitPrune)

59. [**ClusterKV: Manipulating LLM KV Cache in Semantic Space for Recallable Compression.**](https://arxiv.org/abs/2412.03213) *Guangda Liu, Chengwei Li, Jieru Zhao, Chenqi Zhang, Minyi Guo.* Arxiv 2024.

60. [**Unifying KV Cache Compression for Large Language Models with LeanKV.**](https://arxiv.org/abs/2412.03131) *Yanqi Zhang, Yuwei Hu, Runyuan Zhao, John C.S. Lui, Haibo Chen.* Arxiv 2024.

61. [**DynamicKV: Task-Aware Adaptive KV Cache Compression for Long Context LLMs.**](https://arxiv.org/abs/2412.14838) *Xiabin Zhou, Wenbin Wang, Minyan Zeng, Jiaxian Guo, Xuebo Liu, Li Shen, Min Zhang, Liang Ding.* Arxiv 2024.

62. [**SCOPE: Optimizing Key-Value Cache Compression in Long-context Generation.**](https://arxiv.org/abs/2412.13649) *Jialong Wu, Zhenglin Wang, Linhai Zhang, Yilong Lai, Yulan He, Deyu Zhou.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Linking-ai/SCOPE)](https://github.com/Linking-ai/SCOPE)

63. [**HashEvict: A Pre-Attention KV Cache Eviction Strategy using Locality-Sensitive Hashing.**](https://arxiv.org/abs/2412.16187) *Minghui Liu, Tahseen Rabbani, Tony O'Halloran, Ananth Sankaralingam, Mary-Anne Hartley, Brian Gravelle, Furong Huang, Cornelia Fermüller, Yiannis Aloimonos.* Arxiv 2024.

64. [**SepLLM: Accelerate Large Language Models by Compressing One Segment into One Separator.**](https://arxiv.org/abs/2412.12094) *Guoxuan Chen, Han Shi, Jiawei Li, Yihang Gao, Xiaozhe Ren, Yimeng Chen, Xin Jiang, Zhenguo Li, Weiyang Liu, Chao Huang.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/HKUDS/SepLLM)](https://github.com/HKUDS/SepLLM)

65. [**MiniKV: Pushing the Limits of LLM Inference via 2-Bit Layer-Discriminative KV Cache.**](https://arxiv.org/abs/2411.18077) *Akshat Sharma, Hangliang Ding, Jianping Li, Neel Dani, Minjia Zhang.* Arxiv 2025.

66. [**FastKV: KV Cache Compression for Fast Long-Context Processing with Token-Selective Propagation.**](https://arxiv.org/abs/2502.01068) *Dongwon Jo, Jiwon Song, Yulhwa Kim, Jae-Joon Kim.* Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/dongwonjo/FastKV)](https://github.com/dongwonjo/FastKV)

67. [**ChunkKV: Semantic-Preserving KV Cache Compression for Efficient Long-Context LLM Inference.**](https://arxiv.org/abs/2502.00299) *Xiang Liu, Zhenheng Tang, Peijie Dong, Zeyu Li, Bo Li, Xuming Hu, Xiaowen Chu.* Arxiv 2025.

68. [**LServe: Efficient Long-sequence LLM Serving with Unified Sparse Attention.**](https://arxiv.org/abs/2502.14866) *Shang Yang, Junxian Guo, Haotian Tang, Qinghao Hu, Guangxuan Xiao, Jiaming Tang, Yujun Lin, Zhijian Liu, Yao Lu, Song Han.* MLSys 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/mit-han-lab/omniserve)](https://github.com/mit-han-lab/omniserve)

69. [**RocketKV: Accelerating Long-Context LLM Inference via Two-Stage KV Cache Compression.**](https://www.arxiv.org/abs/2502.14051) *Payman Behnam, Yaosheng Fu, Ritchie Zhao, Po-An Tsai, Zhiding Yu, Alexey Tumanov.* Arxiv 2025.
    
70. [**Dynamic-LLaVA: Efficient Multimodal Large Language Models via Dynamic Vision-language Context Sparsification.**](https://arxiv.org/abs/2412.00876) *Wenxuan Huang, Zijie Zhai, Yunhang Shen, Shaosheng Cao, Fei Zhao, Xiangfeng Xu, Zheyu Ye, Shaohui Lin.* ICLR 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Osilly/dynamic_llava)](https://github.com/Osilly/dynamic_llava)

71. [**DBudgetKV: Dynamic Budget in KV Cache Compression for Ensuring Optimal Performance.**](https://arxiv.org/abs/2502.16886) *Xuanfan Ni, Liyan Xu, Chenyang Lyu, Longyue Wang, Mo Yu, Lemao Liu, Fandong Meng, Jie Zhou, Piji Li.* Arxiv 2025.

72. [**Dialogue Without Limits: Constant-Sized KV Caches for Extended Responses in LLMs.**](https://arxiv.org/abs/2503.00979) *Ravi Ghadia, Avinash Kumar, Gaurav Jain, Prashant Nair, Poulami Das.* Arxiv 2025.

73. [**MEDA: Dynamic KV Cache Allocation for Efficient Multimodal Long-Context Inference.**](https://arxiv.org/abs/2502.17599) *Zhongwei Wan, Hui Shen, Xin Wang, Che Liu, Zheda Mai, Mi Zhang.* NAACL 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/AIoT-MLSys-Lab/MEDA)](https://github.com/AIoT-MLSys-Lab/MEDA)

74. [**KVCrush: Key value cache size-reduction using similarity in head-behaviour.**](https://arxiv.org/abs/2503.00022) *Gopi Krishna Jha, Sameh Gobriel, Liubov Talamanova, Alexander Kozlov, Nilesh Jain.* Arxiv 2025.

75. [**LLMs Know What to Drop: Self-Attention Guided KV Cache Eviction for Efficient Long-Context Inference.**](https://arxiv.org/abs/2503.08879) *Guangtao Wang, Shubhangi Upasani, Chen Wu, Darshan Gandhi, Jonathan Li, Changran Hu, Bo Li, Urmish Thakker.* ICLR 2025.

76. [**SpeCache: Speculative Key-Value Caching for Efficient Generation of LLMs.**](https://arxiv.org/abs/2503.16163) *Shibo Jie, Yehui Tang, Kai Han, Zhi-Hong Deng, Jing Han.* Arxiv 2025.

77. [**KV-Distill: Nearly Lossless Learnable Context Compression for LLMs.**](https://arxiv.org/abs/2503.10337) *Vivek Chari, Guanghui Qin, Benjamin Van Durme.* Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/vnchari/kv-distill)](https://github.com/vnchari/kv-distill)

78. [**SentenceKV: Efficient LLM Inference via Sentence-Level Semantic KV Caching.**](https://arxiv.org/abs/2504.00970) *Yuxuan Zhu, Ali Falahati, David H. Yang, Mohammad Mohammadi Amiri.* Arxiv 2025.

79. [**The Sparse Frontier: Sparse Attention Trade-offs in Transformer LLMs.**](https://arxiv.org/abs/2504.17768) *Piotr Nawrot, Robert Li, Renjie Huang, Sebastian Ruder, Kelly Marchisio, Edoardo M. Ponti.* Arxiv 2025.

80. [**FreqKV: Frequency Domain Key-Value Compression for Efficient Context Window Extension.**](https://arxiv.org/abs/2505.00570) *Jushi Kai, Boyi Zeng, Yixuan Wang, Haoli Bai, Bo Jiang, Zhouhan Lin.* Arxiv 2025.

81. [**Mustafar: Promoting Unstructured Sparsity for KV Cache Pruning in LLM Inference.**](https://arxiv.org/abs/2505.22913) *Donghyeon Joo, Helya Hosseini, Ramyad Hadidi, Bahar Asgari.* Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/dhjoo98/mustafar)](https://github.com/dhjoo98/mustafar)
    
82. [**CAKE: Cascading and Adaptive KV Cache Eviction with Layer Preferences.**](https://arxiv.org/abs/2503.12491) *Ziran Qin, Yuchen Cao, Mingbao Lin, Wen Hu, Shixuan Fan, Ke Cheng, Weiyao Lin, Jianguo Li.* ICLR 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/antgroup/cakekv)](https://github.com/antgroup/cakekv)

83. [**R-KV: Redundancy-aware KV Cache Compression for Training-Free Reasoning Models Acceleration.**](https://arxiv.org/abs/2505.24133) *Zefan Cai, Wen Xiao, Hanshi Sun, Cheng Luo, Yikai Zhang, Ke Wan, Yucheng Li, Yeyang Zhou, Li-Wen Chang, Jiuxiang Gu, Zhen Dong, Anima Anandkumar, Abedelkadir Asi, Junjie Hu.* Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Zefan-Cai/R-KV)](https://github.com/Zefan-Cai/R-KV)

84. [**KVzip: Query-Agnostic KV Cache Compression with Context Reconstruction.**](https://arxiv.org/abs/2505.23416) *Jang-Hyun Kim, Jinuk Kim, Sangwoo Kwon, Jae W. Lee, Sangdoo Yun, Hyun Oh Song.* Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/snu-mllab/KVzip)](https://github.com/snu-mllab/KVzip)



### 2️⃣ Merging

1. [**D2O: Dynamic Discriminative Operations for Efficient Generative Inference of Large Language Models.**](https://arxiv.org/abs/2406.13035) *Zhongwei Wan, Xinjian Wu, Yu Zhang, Yi Xin, Chaofan Tao, Zhihong Zhu, Xin Wang, Siqi Luo, Jing Xiong, Mi Zhang.* Arxiv 2024.
   
2. [**Model Tells You Where to Merge: Adaptive KV Cache Merging for LLMs on Long-Context Tasks.**](https://arxiv.org/abs/2407.08454) *Zheng Wang, Boxiao Jin, Zhongzhi Yu, Minjia Zhang.* Arxiv 2024.

3. [**CaM: Cache Merging for Memory-efficient LLMs Inference.**](https://openreview.net/forum?id=LCTmppB165) *Yuxin Zhang, Yuxuan Du, Gen Luo, Yunshan Zhong, Zhenyu Zhang, Shiwei Liu, Rongrong Ji.* ICML 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/zyxxmu/cam)](https://github.com/zyxxmu/cam)

4. [**Hierarchical Context Merging: Better Long Context Understanding for Pre-trained LLMs.**](https://arxiv.org/abs/2404.10308) *Woomin Song, Seunghyuk Oh, Sangwoo Mo, Jaehyung Kim, Sukmin Yun, Jung-Woo Ha, Jinwoo Shin.* ICLR 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/alinlab/HOMER)](https://github.com/alinlab/HOMER)

5. [**Token Merging: Your ViT But Faster.**](https://arxiv.org/abs/2210.09461) *Daniel Bolya, Cheng-Yang Fu, Xiaoliang Dai, Peizhao Zhang, Christoph Feichtenhofer, Judy Hoffman.* ICLR 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/facebookresearch/ToMe)](https://github.com/facebookresearch/ToMe)

6. [**LOOK-M: Look-Once Optimization in KV Cache for Efficient Multimodal Long-Context Inference.**](https://arxiv.org/abs/2406.18139) *Zhongwei Wan, Ziang Wu, Che Liu, Jinfa Huang, Zhihong Zhu, Peng Jin, Longyue Wang, Li Yuan.* EMNLP 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/SUSTechBruce/LOOK-M)](https://github.com/SUSTechBruce/LOOK-M)

7. [**Leave No Context Behind: Efficient Infinite Context Transformers with Infini-attention.**](https://arxiv.org/abs/2404.07143) *Tsendsuren Munkhdalai, Manaal Faruqui, Siddharth Gopal.* Arxiv 2024. 

8. [**Compressed Context Memory for Online Language Model Interaction.**](https://arxiv.org/abs/2312.03414) *Jang-Hyun Kim, Junyoung Yeom, Sangdoo Yun, Hyun Oh Song.* ICLR 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/snu-mllab/Context-Memory)](https://github.com/snu-mllab/Context-Memory)

9. [**CacheBlend: Fast Large Language Model Serving for RAG with Cached Knowledge Fusion.**](https://arxiv.org/abs/2405.16444) *Jiayi Yao, Hanchen Li, Yuhan Liu, Siddhant Ray, Yihua Cheng, Qizheng Zhang, Kuntai Du, Shan Lu, Junchen Jiang.* EuroSys 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/LMCache/LMCache)](https://github.com/LMCache/LMCache)

10. [**AIM: Adaptive Inference of Multi-Modal LLMs via Token Merging and Pruning.**](https://arxiv.org/abs/2412.03248) *Yiwu Zhong, Zhuoming Liu, Yin Li, Liwei Wang.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/LaVi-Lab/AIM)](https://github.com/LaVi-Lab/AIM)

11. [**KeepKV: Eliminating Output Perturbation in KV Cache Compression for Efficient LLMs Inference.**](https://arxiv.org/abs/2504.09936) *Yuxuan Tian, Zihan Wang, Yebo Peng, Aomufei Yuan, Zhiming Wang, Bairen Yi, Xin Liu, Yong Cui, Tong Yang.* Arxiv 2025.

### 3️⃣ Cross-Layer

1. [**You Only Cache Once: Decoder-Decoder Architectures for Language Models.**](https://arxiv.org/abs/2405.05254) *Yutao Sun, Li Dong, Yi Zhu, Shaohan Huang, Wenhui Wang, Shuming Ma, Quanlu Zhang, Jianyong Wang, Furu Wei.* NeurIPS 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/unilm)](https://github.com/microsoft/unilm/tree/master/YOCO)
   
2. [**Reducing Transformer Key-Value Cache Size with Cross-Layer Attention.**](https://arxiv.org/abs/2405.12981) *William Brandon, Mayank Mishra, Aniruddha Nrusimha, Rameswar Panda, Jonathan Ragan Kelly.* Arxiv 2024.
   
3. [**Layer-Condensed KV Cache for Efficient Inference of Large Language Models.**](https://arxiv.org/abs/2405.10637) *Haoyi Wu, Kewei Tu.* ACL 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/whyNLP/LCKV)](https://github.com/whyNLP/LCKV)

4. [**MiniCache: KV Cache Compression in Depth Dimension for Large Language Models.**](https://arxiv.org/abs/2405.14366) *Akide Liu, Jing Liu, Zizheng Pan, Yefei He, Gholamreza Haffari, Bohan Zhuang.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/AkideLiu/MiniCache)](https://github.com/AkideLiu/MiniCache)

5. [**MLKV: Multi-Layer Key-Value Heads for Memory Efficient Transformer Decoding.**](https://arxiv.org/abs/2406.09297) *Zayd Muhammad Kawakibi Zuhri, Muhammad Farid Adilazuarda, Ayu Purwarianti, Alham Fikri Aji.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/zaydzuhri/pythia-mlkv)](https://github.com/zaydzuhri/pythia-mlkv)

6. [**A Systematic Study of Cross-Layer KV Sharing for Efficient LLM Inference.**](https://arxiv.org/abs/2410.14442) *You Wu, Haoyi Wu, Kewei Tu.* Arxiv 2024.

7. [**KVSharer: Efficient Inference via Layer-Wise Dissimilar KV Cache Sharing.**](https://arxiv.org/abs/2410.18517) *Yifei Yang, Zouying Cao, Qiguang Chen, Libo Qin, Dongjie Yang, Hai Zhao, Zhi Chen.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/yangyifei729/KVSharer)](https://github.com/yangyifei729/KVSharer)

8. [**SwiftKV: Fast Prefill-Optimized Inference with Knowledge-Preserving Model Transformation.**](https://arxiv.org/abs/2410.03960) *Aurick Qiao, Zhewei Yao, Samyam Rajbhandari, Yuxiong He.* Arxiv 2024.

9. [**Compressing KV Cache for Long-Context LLM Inference with Inter-Layer Attention Similarity.**](https://arxiv.org/abs/2412.02252) *Da Ma, Lu Chen, Situo Zhang, Yuxun Miao, Su Zhu, Zhi Chen, Hongshen Xu, Hanqi Li, Shuai Fan, Lei Pan, Kai Yu.* Arxiv 2024. 

### 4️⃣ Low-Rank

1. [**Fast Transformer Decoding: One Write-Head is All You Need.**](https://arxiv.org/abs/1911.02150) *Noam Shazeer.* Arxiv 2019.
   
2. [**GQA: Training Generalized Multi-Query Transformer Models from Multi-Head Checkpoints.**](https://arxiv.org/abs/2305.13245) *Joshua Ainslie, James Lee-Thorp, Michiel de Jong, Yury Zemlyanskiy, Federico Lebrón, Sumit Sanghai.* EMNLP 2023.

3. [**DeepSeek-V2: A Strong, Economical, and Efficient Mixture-of-Experts Language Model.**](https://arxiv.org/abs/2405.04434) *DeepSeek-AI.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-V2)](https://github.com/deepseek-ai/DeepSeek-V2)

4. [**Effectively Compress KV Heads for LLM.**](https://arxiv.org/abs/2406.07056) *Hao Yu, Zelan Yang, Shen Li, Yong Li, Jianxin Wu.* Arxiv 2024.

5. [**Palu: Compressing KV-Cache with Low-Rank Projection.**](https://arxiv.org/abs/2407.21118) *Chi-Chih Chang, Wei-Cheng Lin, Chien-Yu Lin, Chong-Yan Chen, Yu-Fang Hu, Pei-Shuo Wang, Ning-Chi Huang, Luis Ceze, Kai-Chiang Wu.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/shadowpa0327/Palu)](https://github.com/shadowpa0327/Palu)

6.  [**LoRC: Low-Rank Compression for LLMs KV Cache with a Progressive Compression Strategy.**](https://arxiv.org/abs/2410.03111) *Rongzhi Zhang, Kuang Wang, Liyuan Liu, Shuohang Wang, Hao Cheng, Chao Zhang, Yelong Shen.* Arxiv 2024.

7.  [**Tensor Product Attention Is All You Need.**](https://arxiv.org/abs/2501.06425) *Yifan Zhang, Yifeng Liu, Huizhuo Yuan, Zhen Qin, Yang Yuan, Quanquan Gu, Andrew Chi-Chih Yao.* Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/tensorgi/T6)](https://github.com/tensorgi/T6)

8.  [**ThinK: Thinner Key Cache by Query-Driven Pruning.**](https://arxiv.org/abs/2407.21018) *Yuhui Xu, Zhanming Jie, Hanze Dong, Lei Wang, Xudong Lu, Aojun Zhou, Amrita Saha, Caiming Xiong, Doyen Sahoo.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/SalesforceAIResearch/ThinK)](https://github.com/SalesforceAIResearch/ThinK)

### 5️⃣ Quantization

1. [**ZipCache: Accurate and Efficient KV Cache Quantization with Salient Token Identification.**](https://www.arxiv.org/abs/2405.14256) *Yefei He, Luoming Zhang, Weijia Wu, Jing Liu, Hong Zhou, Bohan Zhuang.* Arxiv 2024.

2. [**No Token Left Behind: Reliable KV Cache Compression via Importance-Aware Mixed Precision Quantization.**](https://arxiv.org/abs/2402.18096) *June Yong Yang, Byeongwook Kim, Jeongin Bae, Beomseok Kwon, Gunho Park, Eunho Yang, Se Jung Kwon, Dongsoo Lee.* Arxiv 2024.

3. [**KIVI: A Tuning-Free Asymmetric 2bit Quantization for KV Cache.**](https://arxiv.org/abs/2402.02750) *Zirui Liu, Jiayi Yuan, Hongye Jin, Shaochen Zhong, Zhaozhuo Xu, Vladimir Braverman, Beidi Chen, Xia Hu.* ICML 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/jy-yuan/KIVI)](https://github.com/jy-yuan/KIVI)

4. [**GEAR: An Efficient KV Cache Compression Recipe for Near-Lossless Generative Inference of LLM.**](https://arxiv.org/abs/203.05527) *Hao Kang, Qingru Zhang, Souvik Kundu, Geonhwa Jeong, Zaoxing Liu, Tushar Krishna, Tuo Zhao.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/opengear-project/GEAR)](https://github.com/opengear-project/GEAR)

5. [**PQCache: Product Quantization-based KVCache for Long Context LLM Inference.**](https://arxiv.org/abs/2407.12820) *Hailin Zhang, Xiaodong Ji, Yilin Chen, Fangcheng Fu, Xupeng Miao, Xiaonan Nie, Weipeng Chen, Bin Cui.* Arxiv 2024.

6. [**Unlocking Data-free Low-bit Quantization with Matrix Decomposition for KV Cache Compression.**](https://arxiv.org/abs/2405.12591) *Peiyu Liu, Ze-Feng Gao, Wayne Xin Zhao, Yipeng Ma, Tao Wang, Ji-Rong Wen.* Arxiv 2024.

7. [**SKVQ: Sliding-window Key and Value Cache Quantization for Large Language Models.**](https://arxiv.org/abs/2405.06219) *Haojie Duanmu, Zhihang Yuan, Xiuhong Li, Jiangfei Duan, Xingcheng Zhang, Dahua Lin.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/cat538/SKVQ)](https://github.com/cat538/SKVQ)

8. [**QAQ: Quality Adaptive Quantization for LLM KV Cache.**](https://arxiv.org/abs/2403.04643) *Shichen Dong, Wen Cheng, Jiayu Qin, Wei Wang.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/ClubieDong/QAQ-KVCacheQuantization)](https://github.com/ClubieDong/QAQ-KVCacheQuantization)

9. [**KVQuant: Towards 10 Million Context Length LLM Inference with KV Cache Quantization.**](https://arxiv.org/abs/2401.18079) *Coleman Hooper, Sehoon Kim, Hiva Mohammadzadeh, Michael W. Mahoney, Yakun Sophia Shao, Kurt Keutzer, Amir Gholami.* NeurIPS 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/SqueezeAILab/KVQuant)](https://github.com/SqueezeAILab/KVQuant)

10. [**WKVQuant: Quantizing Weight and Key/Value Cache for Large Language Models Gains More.**](https://arxiv.org/abs/2402.12065) *Yuxuan Yue, Zhihang Yuan, Haojie Duanmu, Sifan Zhou, Jianlong Wu, Liqiang Nie.* Arxiv 2024.

11. [**KVTuner: Sensitivity-Aware Layer-wise Mixed Precision KV Cache Quantization for Efficient and Nearly Lossless LLM Inference.**](https://arxiv.org/abs/2502.04420) *Xing Li, Zeyu Xing, Yiming Li, Linping Qu, Hui-Ling Zhen, Wulong Liu, Yiwu Yao, Sinno Jialin Pan, Mingxuan Yuan.* Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/cmd2001/KVTuner)](https://github.com/cmd2001/KVTuner)

12. [**Plug-and-Play 1.x-Bit KV Cache Quantization for Video Large Language Models.**](https://arxiv.org/abs/2503.16257) *Keda Tao, Haoxuan You, Yang Sui, Can Qin, Huan Wang.* Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/KD-TAO/VidKV)](https://github.com/KD-TAO/VidKV)

13. [**BitDecoding: Unlocking Tensor Cores for Long-Context LLMs Decoding with Low-Bit KV Cache.**](https://arxiv.org/abs/2503.18773) *Dayou Du, Shijie Cao, Jianyi Cheng, Ting Cao, Mao Yang.* Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/DD-DuDa/BitDecoding)](https://github.com/DD-DuDa/BitDecoding)


### 6️⃣ Prompt Compression

1. [**LLMLingua: Compressing Prompts for Accelerated Inference of Large Language Models.**](https://arxiv.org/abs/2310.05736) *Huiqiang Jiang, Qianhui Wu, Chin-Yew Lin, Yuqing Yang, Lili Qiu.* EMNLP 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/LLMLingua)](https://github.com/microsoft/LLMLingua)

2. [**LLMLingua-2: Data Distillation for Efficient and Faithful Task-Agnostic Prompt Compression.**](https://arxiv.org/abs/2403.12968) *Zhuoshi Pan, Qianhui Wu, Huiqiang Jiang, Menglin Xia, Xufang Luo, Jue Zhang, Qingwei Lin, Victor Rühle, Yuqing Yang, Chin-Yew Lin, H. Vicky Zhao, Lili Qiu, Dongmei Zhang.* ACL 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/LLMLingua)](https://github.com/microsoft/LLMLingua)

3. [**LongLLMLingua: Accelerating and Enhancing LLMs in Long Context Scenarios via Prompt Compression.**](https://arxiv.org/abs/2310.06839) *Huiqiang Jiang, Qianhui Wu, Xufang Luo, Dongsheng Li, Chin-Yew Lin, Yuqing Yang, Lili Qiu.* ACL 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/LLMLingua)](https://github.com/microsoft/LLMLingua)

4. [**TACO-RL: Task Aware Prompt Compression Optimization with Reinforcement Learning.**](https://arxiv.org/abs/2409.13035) *Shivam Shandilya, Menglin Xia, Supriyo Ghosh, Huiqiang Jiang, Jue Zhang, Qianhui Wu, Victor Rühle.* Arxiv 2024.

5. [**ICPC: In-context Prompt Compression with Faster Inference.**](https://arxiv.org/abs/2501.01625) *Ziyang Yu, Yuyu Liu.* Arxiv 2025.

6. [**Better Prompt Compression Without Multi-Layer Perceptrons.**](https://arxiv.org/abs/2501.06730) *Edouardo Honig, Andrew Lizarraga, Zijun Frank Zhang, Ying Nian Wu.* Arxiv 2025.


### 7️⃣ Reuse

1. [**KVLink: Accelerating Large Language Models via Efficient KV Cache Reuse.**](https://www.arxiv.org/abs/2502.16002) *Jingbo Yang, Bairu Hou, Wei Wei, Yujia Bao, Shiyu Chang.* Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/UCSB-NLP-Chang/KVLink)](https://github.com/UCSB-NLP-Chang/KVLink)


### 8️⃣ Non-Autoregressive

1. [**dKV-Cache: The Cache for Diffusion Language Models.**](https://arxiv.org/abs/2505.15781) *Xinyin Ma, Runpeng Yu, Gongfan Fang, Xinchao Wang.* Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/horseee/dKV-Cache)](https://github.com/horseee/dKV-Cache)

2. **dLLM-Cache: Accelerating Diffusion Large Language Models with Adaptive Caching.** *Zhiyuan Liu, Yicun Yang, Yaojie Zhang, Junjie Chen, Chang Zou, Qingyan Wei, Shaobo Wang, Linfeng Zhang.* Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/maomaocun/dLLM-cache)](https://github.com/maomaocun/dLLM-cache)


## 📊 Evaluation

1. [**KV Cache Compression, But What Must We Give in Return? A Comprehensive Benchmark of Long Context Capable Approaches.**](https://arxiv.org/abs/2407.01527) *Jiayi Yuan, Hongyi Liu, Shaochen (Henry)Zhong, Yu-Neng Chuang, Songchen Li, Guanchu Wang, Duy Le, Hongye Jin, Vipin Chaudhary, Zhaozhuo Xu, Zirui Liu, Xia Hu.* EMNLP 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/henryzhongsc/longctx_bench)](https://github.com/henryzhongsc/longctx_bench)

2. [**SCBench: A KV Cache-Centric Analysis of Long-Context Methods.**](https://arxiv.org/abs/2412.10319) *Yucheng Li, Huiqiang Jiang, Qianhui Wu, Xufang Luo, Surin Ahn, Chengruidong Zhang, Amir H. Abdi, Dongsheng Li, Jianfeng Gao, Yuqing Yang, Lili Qiu.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/MInference)](https://github.com/microsoft/MInference/tree/main/scbench)

3. [**More Tokens, Lower Precision: Towards the Optimal Token-Precision Trade-off in KV Cache Compression.**](https://arxiv.org/abs/2412.12706) *Jiebin Zhang, Dawei Zhu, Yifan Song, Wenhao Wu, Chuqiao Kuang, Xiaoguang Li, Lifeng Shang, Qun Liu, Sujian Li.* Arxiv 2024.

4. [**Rethinking Key-Value Cache Compression Techniques for Large Language Model Serving.**](https://arxiv.org/abs/2503.24000) *Wei Gao, Xinyu Zhou, Peng Sun, Tianwei Zhang, Yonggang Wen.* Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/LLMkvsys/rethink-kv-compression)](https://github.com/LLMkvsys/rethink-kv-compression)

