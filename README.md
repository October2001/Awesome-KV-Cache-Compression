# Awesome-KV-Cache-Compression
📰 Must-read papers on KV Cache Compression 🔥

# 📢 News
🔥 [2024-07-23] Project Begining.

# 📜 Papers

> You can directly click on the title to jump to the corresponding PDF link location

## 📷 Survey

## 💡 Method
### 1️⃣ Evication
1. [**Scissorhands: Exploiting the Persistence of Importance Hypothesis for LLM KV Cache Compression at Test Time.**](https://arxiv.org/abs/2305.17118) *Zichang Liu, Aditya Desai, Fangshuo Liao, Weitao Wang, Victor Xie, Zhaozhuo Xu, Anastasios Kyrillidis, Anshumali Shrivastava.* NeurIPS 2023.

2. [**SnapKV: LLM Knows What You are Looking for Before Generation.**](https://arxiv.org/abs/2404.14469) *Yuhong Li, Yingbing Huang, Bowen Yang, Bharat Venkitesh, Acyr Locatelli, Hanchen Ye, Tianle Cai, Patrick Lewis, Deming Chen.* arXiv 2024.

3. [**H2O: Heavy-Hitter Oracle for Efficient Generative Inference of Large Language Models.**](https://arxiv.org/abs/2306.14048) *Zhenyu Zhang, Ying Sheng, Tianyi Zhou, Tianlong Chen, Lianmin Zheng, Ruisi Cai, Zhao Song, Yuandong Tian, Christopher Ré, Clark Barrett, Zhangyang Wang, Beidi Chen.* NeurIPS 2023.

4. [**Model Tells You What to Discard: Adaptive KV Cache Compression for LLMs.**](https://arxiv.org/abs/2310.01801) *Suyu Ge, Yunan Zhang, Liyuan Liu, Minjia Zhang, Jiawei Han, Jianfeng Gao.* ICLR 2024.

5. [**PyramidInfer: Pyramid KV Cache Compression for High-throughput LLM Inference.**](https://arxiv.org/abs/2405.12532) *Dongjie Yang, XiaoDong Han, Yan Gao, Yao Hu, Shilin Zhang, Hai Zhao.* ACL 2024.

6. [**Transformers are Multi-State RNNs.**](https://arxiv.org/abs/2401.06104) *Matanel Oren, Michael Hassid, Nir Yarden, Yossi Adi, Roy Schwartz.* arXiv 2024.

7. [**Efficient Streaming Language Models with Attention Sinks.**](https://arxiv.org/abs/2309.17453) *Guangxuan Xiao, Yuandong Tian, Beidi Chen, Song Han, Mike Lewis.* ICLR 2024.

8. [**A Simple and Effective L2 Norm-Based Strategy for KV Cache Compression.**](https://arxiv.org/abs/2406.11430) *Alessio Devoto, Yu Zhao, Simone Scardapane, Pasquale Minervini.* arXiv 2024.

9. [**Retrieval Head Mechanistically Explains Long-Context Factuality.**](https://arxiv.org/abs/2404.15574) *Wenhao Wu, Yizhong Wang, Guangxuan Xiao, Hao Peng, Yao Fu.* arXiv 2024.

### 2️⃣ Merging
1. [**D2O: Dynamic Discriminative Operations for Efficient Generative Inference of Large Language Models.**](https://arxiv.org/abs/2406.13035) *Zhongwei Wan, Xinjian Wu, Yu Zhang, Yi Xin, Chaofan Tao, Zhihong Zhu, Xin Wang, Siqi Luo, Jing Xiong, Mi Zhang.* arXiv 2024.
   
2. [**Model Tells You Where to Merge: Adaptive KV Cache Merging for LLMs on Long-Context Tasks.**](https://arxiv.org/abs/2407.08454) *Zheng Wang, Boxiao Jin, Zhongzhi Yu, Minjia Zhang.* arXiv 2024.

### 3️⃣ Cross-Layer
1. [**You Only Cache Once: Decoder-Decoder Architectures for Language Models.**](https://arxiv.org/abs/2405.05254) *Yutao Sun, Li Dong, Yi Zhu, Shaohan Huang, Wenhui Wang, Shuming Ma, Quanlu Zhang, Jianyong Wang, Furu Wei.* arXiv 2024.
   
2. [**Reducing Transformer Key-Value Cache Size with Cross-Layer Attention.**](https://arxiv.org/abs/2405.12981) *William Brandon, Mayank Mishra, Aniruddha Nrusimha, Rameswar Panda, Jonathan Ragan Kelly.* arXiv 2024.
   
3. [**Layer-Condensed KV Cache for Efficient Inference of Large Language Models.**](https://arxiv.org/abs/2405.10637) *Haoyi Wu, Kewei Tu.* arXiv 2024.

4. [**MiniCache: KV Cache Compression in Depth Dimension for Large Language Models.**](https://arxiv.org/abs/2405.14366) *Akide Liu, Jing Liu, Zizheng Pan, Yefei He, Gholamreza Haffari, Bohan Zhuang.* arXiv 2024.

### 4️⃣ Low-Rank
1. [**DeepSeek-V2: A Strong, Economical, and Efficient Mixture-of-Experts Language Model.**](https://arxiv.org/abs/2405.04434) *DeepSeek-AI.* arXiv 2024.

### 5️⃣ Quantization
1. [**ZipCache: Accurate and Efficient KV Cache Quantization with Salient Token Identification.**](https://www.arxiv.org/abs/2405.14256) *Yefei He, Luoming Zhang, Weijia Wu, Jing Liu, Hong Zhou, Bohan Zhuang.* arXiv 2024.

2. [**No Token Left Behind: Reliable KV Cache Compression via Importance-Aware Mixed Precision Quantization.**](https://arxiv.org/abs/2402.18096) *June Yong Yang, Byeongwook Kim, Jeongin Bae, Beomseok Kwon, Gunho Park, Eunho Yang, Se Jung Kwon, Dongsoo Lee.* arXiv 2024.

3. [**KIVI: A Tuning-Free Asymmetric 2bit Quantization for KV Cache.**](https://arxiv.org/abs/2402.02750) *Zirui Liu, Jiayi Yuan, Hongye Jin, Shaochen Zhong, Zhaozhuo Xu, Vladimir Braverman, Beidi Chen, Xia Hu.* arXiv 2024.

4. [**GEAR: An Efficient KV Cache Compression Recipe for Near-Lossless Generative Inference of LLM.**](https://arxiv.org/abs/2403.05527) *Hao Kang, Qingru Zhang, Souvik Kundu, Geonhwa Jeong, Zaoxing Liu, Tushar Krishna, Tuo Zhao.* arXiv 2024.
  
## 📊 Evaluation
1. [**KV Cache Compression, But What Must We Give in Return? A Comprehensive Benchmark of Long Context Capable Approaches.**](https://arxiv.org/abs/2407.01527) *Jiayi Yuan, Hongyi Liu, Shaochen (Henry)Zhong, Yu-Neng Chuang, Songchen Li, Guanchu Wang, Duy Le, Hongye Jin, Vipin Chaudhary, Zhaozhuo Xu, Zirui Liu, Xia Hu.* arXiv 2024.

