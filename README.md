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

## 📷 Survey

1. [**Keep the Cost Down: A Review on Methods to Optimize LLM' s KV-Cache Consumption.**](https://arxiv.org/abs/2407.18003) *Shi Luohe, Zhang Hongyi, Yao Yao, Li Zuchao, Zhao Hai.* COLM 2024.

2. [**Prompt Compression for Large Language Models: A Survey.**](https://arxiv.org/abs/2410.12388) *Zongqian Li, Yinhong Liu, Yixuan Su, Nigel Collier.* Arxiv 2024.


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

17. [**Attention Score is not All You Need for Token Importance Indicator in KV Cache Reduction: Value Also Matters.**](https://arxiv.org/abs/2406.12335) *Zhiyu Guo, Hidetaka Kamigaito, Taro Watanabe.* Arxiv 2024.

18. [**On the Efficacy of Eviction Policy for Key-Value Constrained Generative Language Model Inference.**](https://arxiv.org/abs/2406.12335) *Siyu Ren, Kenny Q. Zhu.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/DRSY/EasyKV)](https://github.com/DRSY/EasyKV)

19. [**CORM: Cache Optimization with Recent Message for Large Language Model Inference.**](https://arxiv.org/abs/2404.15949) *Jincheng Dai, Zhuowei Huang, Haiyun Jiang, Chen Chen, Deng Cai, Wei Bi, Shuming Shi.* Arxiv 2024.
    
20. [**RazorAttention: Efficient KV Cache Compression Through Retrieval Heads.**](https://www.arxiv.org/abs/2407.15891) *Hanlin Tang, Yang Lin, Jing Lin, Qingsen Han, Shikuan Hong, Yiwu Yao, Gongyi Wang.* Arxiv 2024.

21. [**ThinK: Thinner Key Cache by Query-Driven Pruning.**](https://arxiv.org/abs/2407.21018) *Yuhui Xu, Zhanming Jie, Hanze Dong, Lei Wang, Xudong Lu, Aojun Zhou, Amrita Saha, Caiming Xiong, Doyen Sahoo.* Arxiv 2024.

22. [**A2SF: Accumulative Attention Scoring with Forgetting Factor for Token Pruning in Transformer Decoder.**](https://arxiv.org/abs/2407.20485) *Hyun Rae Jo, Dong Kun Shin.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Dirac-Notation/A2SF)](https://github.com/Dirac-Notation/A2SF)

23. [**Quest: Query-Aware Sparsity for Efficient Long-Context LLM Inference.**](https://arxiv.org/abs/2406.10774) *Jiaming Tang, Yilong Zhao, Kan Zhu, Guangxuan Xiao, Baris Kasikci, Song Han.* ICML 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/mit-han-lab/Quest)](https://github.com/mit-han-lab/Quest)

24. [**LazyLLM: Dynamic Token Pruning for Efficient Long Context LLM Inference.**](https://arxiv.org/abs/2407.14057) *Qichen Fu, Minsik Cho, Thomas Merth, Sachin Mehta, Mohammad Rastegari, Mahyar Najibi.* Arxiv 2024.

25. [**NACL: A General and Effective KV Cache Eviction Framework for LLMs at Inference Time.**](https://arxiv.org/abs/2408.03675) *Yilong Chen, Guoxia Wang, Junyuan Shang, Shiyao Cui, Zhenyu Zhang, Tingwen Liu, Shuohuan Wang, Yu Sun, Dianhai Yu, Hua Wu.* ACL 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/PaddlePaddle/Research)](https://github.com/PaddlePaddle/Research/tree/master/NLP/ACL2024-NACL)

26. [**Post-Training Sparse Attention with Double Sparsity.**](https://arxiv.org/abs/2408.07092) *Shuo Yang, Ying Sheng, Joseph E. Gonzalez, Ion Stoica, Lianmin Zheng.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/andy-yang-1/DoubleSparse)](https://github.com/andy-yang-1/DoubleSparse)

27. [**Farewell to Length Extrapolation, a Training-Free Infinite Context with Finite Attention Scope.**](https://www.arxiv.org/abs/2407.15176) *Xiaoran Liu, Qipeng Guo, Yuerong Song, Zhigeng Liu, Kai Lv, Hang Yan, Linlin Li, Qun Liu, Xipeng Qiu.* Arxiv 2024.

28. [**Dynamic Memory Compression: Retrofitting LLMs for Accelerated Inference.**](https://arxiv.org/abs/2403.09636) *Piotr Nawrot, Adrian Łańcucki, Marcin Chochowski, David Tarjan, Edoardo M. Ponti.* ICML 2024.

29. [**MInference 1.0: Accelerating Pre-filling for Long-Context LLMs via Dynamic Sparse Attention.**](https://arxiv.org/abs/2407.02490) *Huiqiang Jiang, Yucheng Li, Chengruidong Zhang, Qianhui Wu, Xufang Luo, Surin Ahn, Zhenhua Han, Amir H. Abdi, Dongsheng Li, Chin-Yew Lin, Yuqing Yang, Lili Qiu.* NeurIPS 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/MInference)](https://github.com/microsoft/MInference)

30. [**Dynamic Context Pruning for Efficient and Interpretable Autoregressive Transformers.**](https://arxiv.org/abs/2305.15805) *Sotiris Anagnostidis, Dario Pavllo, Luca Biggio, Lorenzo Noci, Aurelien Lucchi, Thomas Hofmann.* NeurIPS 2023.

31. [**RetrievalAttention: Accelerating Long-Context LLM Inference via Vector Retrieval.**](https://arxiv.org/abs/2409.10516) *Di Liu, Meng Chen, Baotong Lu, Huiqiang Jiang, Zhenhua Han, Qianxi Zhang, Qi Chen, Chengruidong Zhang, Bailu Ding, Kai Zhang, Chen Chen, Fan Yang, Yuqing Yang, Lili Qiu.* Arxiv 2024.

32. [**Sirius: Contextual Sparsity with Correction for Efficient LLMs.**](https://www.arxiv.org/abs/2409.03856) *Yang Zhou, Zhuoming Chen, Zhaozhuo Xu, Victoria Lin, Beidi Chen.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/infini-ai-lab/sirius)](https://github.com/infini-ai-lab/sirius)

33. [**Inf-MLLM: Efficient Streaming Inference of Multimodal Large Language Models on a Single GPU.**](https://www.arxiv.org/abs/2409.09086) *Zhenyu Ning, Jieru Zhao, Qihao Jin, Wenchao Ding, Minyi Guo.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/infly-ai/INF-MLLM)](https://github.com/infly-ai/INF-MLLM)

34. [**Training-Free Activation Sparsity in Large Language Models.**](https://www.arxiv.org/abs/2408.14690) *James Liu, Pragaash Ponnusamy, Tianle Cai, Han Guo, Yoon Kim, Ben Athiwaratkun.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/FasterDecoding/TEAL)](https://github.com/FasterDecoding/TEAL)

35. [**KVPruner: Structural Pruning for Faster and Memory-Efficient Large Language Models.**](https://www.arxiv.org/abs/2409.11057) *Bo Lv, Quan Zhou, Xuanang Ding, Yan Wang, Zeming Ma.* Arxiv 2024.

36. [**CritiPrefill: A Segment-wise Criticality-based Approach for Prefilling Acceleration in LLMs.**](https://www.arxiv.org/abs/2409.12490) *Junlin Lv, Yuan Feng, Xike Xie, Xin Jia, Qirong Peng, Guiming Xie.* Arxiv 2024.

37. [**Discovering the Gems in Early Layers: Accelerating Long-Context LLMs with 1000x Input Token Reduction.**](https://arxiv.org/abs/2409.17422) *Zhenmei Shi, Yifei Ming, Xuan-Phi Nguyen, Yingyu Liang, Shafiq Joty.* Arxiv 2024.

38. [**KV-Compress: Paged KV-Cache Compression with Variable Compression Rates per Attention Head.**](https://arxiv.org/abs/2410.00161) *Isaac Rehg.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/IsaacRe/vllm-kvcompress)](https://github.com/IsaacRe/vllm-kvcompress)

39. [**InfiniPot: Infinite Context Processing on Memory-Constrained LLMs.**](https://arxiv.org/abs/2410.01518) *Minsoo Kim, Kyuhong Shim, Jungwook Choi, Simyung Chang.* EMNLP 2024.

40. [**Locret: Enhancing Eviction in Long-Context LLM Inference with Trained Retaining Heads.**](https://arxiv.org/abs/2410.01805) *Yuxiang Huang, Binhang Yuan, Xu Han, Chaojun Xiao, Zhiyuan Liu.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/huangyuxiang03/Locret)](https://github.com/huangyuxiang03/Locret)

41. [**SparseVLM: Visual Token Sparsification for Efficient Vision-Language Model Inference.**](https://arxiv.org/abs/2410.04417) *Yuan Zhang, Chun-Kai Fan, Junpeng Ma, Wenzhao Zheng, Tao Huang, Kuan Cheng, Denis Gudovskiy, Tomoyuki Okuno, Yohei Nakata, Kurt Keutzer, Shanghang Zhang.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Gumpest/SparseVLMs)](https://github.com/Gumpest/SparseVLMs)

42. [**LoCoCo: Dropping In Convolutions for Long Context Compression.**](https://arxiv.org/abs/2406.05317) *Ruisi Cai, Yuandong Tian, Zhangyang Wang, Beidi Chen.* ICML 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/VITA-Group/LoCoCo)](https://github.com/VITA-Group/LoCoCo)

43. [**DuoAttention: Efficient Long-Context LLM Inference with Retrieval and Streaming Heads.**](https://arxiv.org/abs/2410.10819) *Guangxuan Xiao, Jiaming Tang, Jingwei Zuo, Junxian Guo, Shang Yang, Haotian Tang, Yao Fu, Song Han.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/mit-han-lab/duo-attention)](https://github.com/mit-han-lab/duo-attention)

44. [**SimLayerKV: A Simple Framework for Layer-Level KV Cache Reduction.**](https://arxiv.org/abs/2410.13846) *Xuan Zhang, Cunxiao Du, Chao Du, Tianyu Pang, Wei Gao, Min Lin.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/sail-sg/SimLayerKV)](https://github.com/sail-sg/SimLayerKV)

45. [**In-context KV-Cache Eviction for LLMs via Attention-Gate.**](https://arxiv.org/abs/2410.12876) *Zihao Zeng, Bokai Lin, Tianqi Hou, Hao Zhang, Zhijie Deng.* Arxiv 2024.

46. [**CacheGen: KV Cache Compression and Streaming for Fast Large Language Model Serving.**](https://arxiv.org/abs/2310.07240) *Yuhan Liu, Hanchen Li, Yihua Cheng, Siddhant Ray, Yuyang Huang, Qizheng Zhang, Kuntai Du, Jiayi Yao, Shan Lu, Ganesh Ananthanarayanan, Michael Maire, Henry Hoffmann, Ari Holtzman, Junchen Jiang.* ACM SIGCOMM 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/LMCache/LMCache)](https://github.com/LMCache/LMCache)

47. [**MagicPIG: LSH Sampling for Efficient LLM Generation.**](https://arxiv.org/abs/2410.16179) *Zhuoming Chen, Ranajoy Sadhukhan, Zihao Ye, Yang Zhou, Jianyu Zhang, Niklas Nolte, Yuandong Tian, Matthijs Douze, Leon Bottou, Zhihao Jia, Beidi Chen.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Infini-AI-Lab/MagicPIG)](https://github.com/Infini-AI-Lab/MagicPIG)

48. [**TidalDecode: Fast and Accurate LLM Decoding with Position Persistent Sparse Attention.**](https://arxiv.org/abs/2410.05076) *Lijie Yang, Zhihao Zhang, Zhuofu Chen, Zikun Li, Zhihao Jia.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/DerrickYLJ/TidalDecode)](https://github.com/DerrickYLJ/TidalDecode)

49. [**ShadowKV: KV Cache in Shadows for High-Throughput Long-Context LLM Inference.**](https://arxiv.org/abs/2410.21465) *Hanshi Sun, Li-Wen Chang, Wenlei Bao, Size Zheng, Ningxin Zheng, Xin Liu, Harry Dong, Yuejie Chi, Beidi Chen.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/bytedance/ShadowKV)](https://github.com/bytedance/ShadowKV)

50. [**BUZZ: Beehive-structured Sparse KV Cache with Segmented Heavy Hitters for Efficient LLM Inference.**](https://arxiv.org/abs/2410.23079) *Junqi Zhao, Zhijin Fang, Shu Li, Shaohui Yang, Shichao He.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/JunqiZhao888/buzz-llm)](https://github.com/JunqiZhao888/buzz-llm)

51. [**CItruS: Chunked Instruction-aware State Eviction for Long Sequence Modeling.**](https://arxiv.org/abs/2406.12018) *Yu Bai, Xiyuan Zou, Heyan Huang, Sanxing Chen, Marc-Antoine Rondeau, Yang Gao, Jackie Chi Kit Cheung.* EMNLP 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/ybai-nlp/CItruS)](https://github.com/ybai-nlp/CItruS)

52. [**TokenSelect: Efficient Long-Context Inference and Length Extrapolation for LLMs via Dynamic Token-Level KV Cache Selection.**](https://arxiv.org/abs/2411.02886) *Wei Wu, Zhuoshi Pan, Chao Wang, Liyi Chen, Yunchu Bai, Kun Fu, Zheng Wang, Hui Xiong.* Arxiv 2024.

53. [**Recycled Attention: Efficient inference for long-context language models.**](https://arxiv.org/abs/2411.05787) *Fangyuan Xu, Tanya Goyal, Eunsol Choi.* Arxiv 2024.

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

### 3️⃣ Cross-Layer

1. [**You Only Cache Once: Decoder-Decoder Architectures for Language Models.**](https://arxiv.org/abs/2405.05254) *Yutao Sun, Li Dong, Yi Zhu, Shaohan Huang, Wenhui Wang, Shuming Ma, Quanlu Zhang, Jianyong Wang, Furu Wei.* NeurIPS 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/unilm)](https://github.com/microsoft/unilm/tree/master/YOCO)
   
2. [**Reducing Transformer Key-Value Cache Size with Cross-Layer Attention.**](https://arxiv.org/abs/2405.12981) *William Brandon, Mayank Mishra, Aniruddha Nrusimha, Rameswar Panda, Jonathan Ragan Kelly.* Arxiv 2024.
   
3. [**Layer-Condensed KV Cache for Efficient Inference of Large Language Models.**](https://arxiv.org/abs/2405.10637) *Haoyi Wu, Kewei Tu.* ACL 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/whyNLP/LCKV)](https://github.com/whyNLP/LCKV)

4. [**MiniCache: KV Cache Compression in Depth Dimension for Large Language Models.**](https://arxiv.org/abs/2405.14366) *Akide Liu, Jing Liu, Zizheng Pan, Yefei He, Gholamreza Haffari, Bohan Zhuang.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/AkideLiu/MiniCache)](https://github.com/AkideLiu/MiniCache)

5. [**MLKV: Multi-Layer Key-Value Heads for Memory Efficient Transformer Decoding.**](https://arxiv.org/abs/2406.09297) *Zayd Muhammad Kawakibi Zuhri, Muhammad Farid Adilazuarda, Ayu Purwarianti, Alham Fikri Aji.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/zaydzuhri/pythia-mlkv)](https://github.com/zaydzuhri/pythia-mlkv)

6. [**A Systematic Study of Cross-Layer KV Sharing for Efficient LLM Inference.**](https://arxiv.org/abs/2410.14442) *You Wu, Haoyi Wu, Kewei Tu.* Arxiv 2024.

7. [**KVSharer: Efficient Inference via Layer-Wise Dissimilar KV Cache Sharing.**](https://arxiv.org/abs/2410.18517) *Yifei Yang, Zouying Cao, Qiguang Chen, Libo Qin, Dongjie Yang, Hai Zhao, Zhi Chen.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/yangyifei729/KVSharer)](https://github.com/yangyifei729/KVSharer)

8. [**SwiftKV: Fast Prefill-Optimized Inference with Knowledge-Preserving Model Transformation.**](https://arxiv.org/abs/2410.03960) *Aurick Qiao, Zhewei Yao, Samyam Rajbhandari, Yuxiong He.* Arxiv 2024. 

### 4️⃣ Low-Rank

1. [**Fast Transformer Decoding: One Write-Head is All You Need.**](https://arxiv.org/abs/1911.02150) *Noam Shazeer.* Arxiv 2019.
   
2. [**GQA: Training Generalized Multi-Query Transformer Models from Multi-Head Checkpoints.**](https://arxiv.org/abs/2305.13245) *Joshua Ainslie, James Lee-Thorp, Michiel de Jong, Yury Zemlyanskiy, Federico Lebrón, Sumit Sanghai.* EMNLP 2023.

3. [**DeepSeek-V2: A Strong, Economical, and Efficient Mixture-of-Experts Language Model.**](https://arxiv.org/abs/2405.04434) *DeepSeek-AI.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-V2)](https://github.com/deepseek-ai/DeepSeek-V2)

4. [**Effectively Compress KV Heads for LLM.**](https://arxiv.org/abs/2406.07056) *Hao Yu, Zelan Yang, Shen Li, Yong Li, Jianxin Wu.* Arxiv 2024.

5. [**Palu: Compressing KV-Cache with Low-Rank Projection.**](https://arxiv.org/abs/2407.21118) *Chi-Chih Chang, Wei-Cheng Lin, Chien-Yu Lin, Chong-Yan Chen, Yu-Fang Hu, Pei-Shuo Wang, Ning-Chi Huang, Luis Ceze, Kai-Chiang Wu.* Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/shadowpa0327/Palu)](https://github.com/shadowpa0327/Palu)

6.  [**LoRC: Low-Rank Compression for LLMs KV Cache with a Progressive Compression Strategy.**](https://arxiv.org/abs/2410.03111) *Rongzhi Zhang, Kuang Wang, Liyuan Liu, Shuohang Wang, Hao Cheng, Chao Zhang, Yelong Shen.* Arxiv 2024.

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

### 6️⃣ Prompt Compression

1. [**LLMLingua: Compressing Prompts for Accelerated Inference of Large Language Models.**](https://arxiv.org/abs/2310.05736) *Huiqiang Jiang, Qianhui Wu, Chin-Yew Lin, Yuqing Yang, Lili Qiu.* EMNLP 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/LLMLingua)](https://github.com/microsoft/LLMLingua)

2. [**LLMLingua-2: Data Distillation for Efficient and Faithful Task-Agnostic Prompt Compression.**](https://arxiv.org/abs/2403.12968) *Zhuoshi Pan, Qianhui Wu, Huiqiang Jiang, Menglin Xia, Xufang Luo, Jue Zhang, Qingwei Lin, Victor Rühle, Yuqing Yang, Chin-Yew Lin, H. Vicky Zhao, Lili Qiu, Dongmei Zhang.* ACL 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/LLMLingua)](https://github.com/microsoft/LLMLingua)

3. [**LongLLMLingua: Accelerating and Enhancing LLMs in Long Context Scenarios via Prompt Compression.**](https://arxiv.org/abs/2310.06839) *Huiqiang Jiang, Qianhui Wu, Xufang Luo, Dongsheng Li, Chin-Yew Lin, Yuqing Yang, Lili Qiu.* ACL 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/LLMLingua)](https://github.com/microsoft/LLMLingua)

4. [**TACO-RL: Task Aware Prompt Compression Optimization with Reinforcement Learning.**](https://arxiv.org/abs/2409.13035) *Shivam Shandilya, Menglin Xia, Supriyo Ghosh, Huiqiang Jiang, Jue Zhang, Qianhui Wu, Victor Rühle.* Arxiv 2024.

## 📊 Evaluation

1. [**KV Cache Compression, But What Must We Give in Return? A Comprehensive Benchmark of Long Context Capable Approaches.**](https://arxiv.org/abs/2407.01527) *Jiayi Yuan, Hongyi Liu, Shaochen (Henry)Zhong, Yu-Neng Chuang, Songchen Li, Guanchu Wang, Duy Le, Hongye Jin, Vipin Chaudhary, Zhaozhuo Xu, Zirui Liu, Xia Hu.* EMNLP 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/henryzhongsc/longctx_bench)](https://github.com/henryzhongsc/longctx_bench)

