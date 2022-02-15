# openQA-reading-list
This is a paper reading list on Open-Domain Question Answering.

Our list is still incomplete and the categorization might be inappropriate. We will keep adding papers and improving the list. Any suggestions are welcomed!

## Datasets

* openQA: SQuAD, SQuAD2.0, Natural Questions (NQ), TriviaQA, WebQuestions, CuratedTREC (TREC), MS MARCO

* Biomedical openQA: COVID-QA, BioASQ

## openQA Papers

### 2022

1. AAAI 2022. [Improving Biomedical Information Retrieval with Neural Retrievers](https://arxiv.org/abs/2201.07745). Man Luo, Arindam Mitra, Tejas Gokhale, Chitta Baral.
  <br> 👉 Datasets: BioASQ
  <br> 👉 Method: 

### 2021

1. EMNLP 2021. [Phrase Retrieval Learns Passage Retrieval, Too](https://arxiv.org/pdf/2109.08133v1.pdf). Jinhyuk Lee, Alexander Wettig, Danqi Chen.

1. EMNLP 2021. [RocketQAv2: A Joint Training Method for Dense Passage Retrieval and Passage Re-ranking](https://arxiv.org/abs/2110.07367). Ruiyang Ren, Yingqi Qu, Jing Liu, Wayne Xin Zhao, Qiaoqiao She, Hua Wu, Haifeng Wang, Ji-Rong Wen.

1. EMNLP 2021 Demo. [Open-Domain Question-Answering for COVID-19 and Other Emergent Domains](https://arxiv.org/abs/2110.06962). Sharon Levy, Kevin Mo, Wenhan Xiong, William Yang Wang.
  <br> 👉 Datasets: COVID-QA
  <br> 👉 Method: Retrieval-stage: Dense Retrieval + K-Means + BM25 re-ranking, MRC-stage: fine-tuned on the SQuAD2.0 and fine-tuning this model on COVIDQA

1. EMNLP 2021 Findings. [Dense Hierarchical Retrieval for Open-Domain Question Answering](https://export.arxiv.org/pdf/2110.15439.pdf). Ye Liu, Kazuma Hashimoto, Yingbo Zhou, Semih Yavuz, Caiming Xiong, Philip S. Yu.
  <br> 👉 Datasets: Natural Questions (NQ), TriviaQA, WebQuestions, CuratedTREC (TREC)
  <br> 👉 Method: Dense Hierarchical Retrieval, utilizing both macroscopic semantics in the document and microscopic semantics specific to each passage

1. ACL 2021. [End-to-End Training of Neural Retrievers for Open-Domain Question Answering](https://arxiv.org/abs/2101.00408). Devendra Singh Sachan, Mostofa Patwary, Mohammad Shoeybi, Neel Kant, Wei Ping, William L Hamilton, Bryan Catanzaro.

1. ACL 2021. [PAIR: Leveraging Passage-Centric Similarity Relation for Improving Dense Passage Retrieval](https://arxiv.org/abs/2108.06027). Ruiyang Ren, Shangwen Lv, Yingqi Qu, Jing Liu, Wayne Xin Zhao, QiaoQiao She, Hua Wu, Haifeng Wang, Ji-Rong Wen.

1. NAACL 2021. [RocketQA: An Optimized Training Approach to Dense Passage Retrieval for Open-Domain Question Answering](https://arxiv.org/abs/2010.08191). Yingqi Qu, Yuchen Ding, Jing Liu, Kai Liu, Ruiyang Ren, Wayne Xin Zhao, Daxiang Dong, Hua Wu, Haifeng Wang.

### 2020

1. ACL 2020. [Talk to Papers: Bringing Neural Question Answering to Academic Search](https://arxiv.org/pdf/2004.02002v3.pdf). Tianchang Zhao, Kyusong Lee.

1. ACL 2020. [Contextualized Sparse Representations for Real-Time Open-Domain Question Answering](https://arxiv.org/pdf/1911.02896.pdf). Jinhyuk Lee, Minjoon Seo, Hannaneh Hajishirzi, Jaewoo Kang.

1. ICLR 2020. [Learning to Retrieve Reasoning Paths over Wikipedia Graph for Question Answering](https://arxiv.org/pdf/1911.10470.pdf). Akari Asai, Kazuma Hashimoto, Hannaneh Hajishirzi, Richard Socher, Caiming Xiong.

1. ICML 2020. [REALM: Retrieval-Augmented Language Model Pre-Training](https://arxiv.org/pdf/2002.08909.pdf).
Kelvin Guu, Kenton Lee, Zora Tung, Panupong Pasupat, Ming-Wei Chang.

1. EMNLP 2020. [Dense Passage Retrieval for Open-Domain Question Answering](https://arxiv.org/pdf/2004.04906.pdf), Vladimir Karpukhin, Barlas Oğuz, Sewon Min, Patrick Lewis, Ledell Wu, Sergey Edunov, Danqi Chen, Wen-tau Yih.
  <br> 👉 Datasets: NQ, TriviaQA, WQ, TREC, SQuAD
  <br> 👉 Method: Chose hard negative examples, DPR + BM25

1. EMNLP 2020. [How Much Knowledge Can You Pack Into the Parameters of a Language Model?](https://arxiv.org/pdf/2002.08910.pdf). Adam Roberts, Colin Raffel, Noam Shazeer.

1. NeurIPS 2020. [Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks](https://arxiv.org/pdf/2005.11401.pdf). Patrick Lewis, Ethan Perez, Aleksandara Piktus, Fabio Petroni, Vladimir Karpukhin, Naman Goyal, Heinrich Küttler, Mike Lewis, Wen-tau Yih, Tim Rocktäschel, Sebastian Riedel, Douwe Kiela.

1. NeurIPS 2020. [Language Models are Few-Shot Learners](https://arxiv.org/pdf/2005.14165.pdf). Tom B. Brown, Benjamin Mann, Nick Ryder et al.

1. KDD 2020. [Embedding-based Retrieval in Facebook Search](https://arxiv.org/abs/2006.11632). Jui-Ting Huang, Ashish Sharma, Shuying Sun, Li Xia, David Zhang, Philip Pronin, Janani Padmanabhan, Giuseppe Ottaviano, Linjun Yang.

### 2019

1. OpenAI 2019. [Language Models are Unsupervised Multitask Learners](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf). Alec Radford, Jeffrey Wu, Rewon Child, David Luan, Dario Amodei, Ilya Sutskever.

1. NAACL 2019 (demonstration). [End-to-end Open-domain Question Answering with BERTserini](https://arxiv.org/pdf/1902.01718.pdf). Wei Yang, Yuqing Xie, Aileen Lin, Xingyu Li, Luchen Tan, Kun Xiong, Ming Li, Jimmy Lin.

1. ACL 2019. [Latent Retrieval for Weakly Supervised Open Domain Question Answering](https://aclanthology.org/P19-1612.pdf). Kenton Lee, Ming-Wei Chang, Kristina Toutanova.

1. ACL 2019. [Real-Time Open-Domain Question Answering with Dense-Sparse Phrase Index](https://arxiv.org/pdf/1906.05807.pdf). Minjoon Seo, Jinhyuk Lee, Tom Kwiatkowski, Ankur P. Parikh, Ali Farhadi, Hannaneh Hajishirzi.

1. ACL 2019. [Improving Question Answering over Incomplete KBs with Knowledge-Aware Reader](https://www.aclweb.org/anthology/P19-1417.pdf). Wenhan Xiong, Mo Yu, Shiyu Chang, Xiaoxiao Guo, William Yang Wang.

1. EMNLP 2019. [A Discrete Hard EM Approach for Weakly Supervised Question Answering](https://arxiv.org/pdf/1909.04849.pdf). Sewon Min, Danqi Chen, Hannaneh Hajishirzi, Luke Zettlemoyer.

1. EMNLP 2019. [Multi-passage BERT: A Globally Normalized BERT Model for Open-domain Question Answering](https://arxiv.org/pdf/1908.08167.pdf). Zhiguo Wang, Patrick Ng, Xiaofei Ma, Ramesh Nallapati, Bing Xiang.
  <br> 👉 Task: Multi-Paragraph MRC

1. EMNLP 2019. [PullNet: Open Domain Question Answering with Iterative Retrieval on Knowledge Bases and Text](https://arxiv.org/pdf/1904.09537.pdf). Haitian Sun, Tania Bedrax-Weiss, William W. Cohen.

1. EMNLP 2019. [Revealing the Importance of Semantic Retrieval for Machine Reading at Scale](https://arxiv.org/abs/1909.08041). Yixin Nie, Songhe Wang, Mohit Bansal.

1. arXiv 2019. [Knowledge Guided Text Retrieval and Reading for Open Domain Question Answering](https://arxiv.org/pdf/1911.03868.pdf). Sewon Min, Danqi Chen, Luke Zettlemoyer, Hannaneh Hajishirzi.

1. arXiv 2019. [Passage Re-ranking with BERT](https://arxiv.org/abs/1901.04085). Rodrigo Nogueira, Kyunghyun Cho.

### 2018

1. AAAI 2018. [R^3: Reinforced Reader-Ranker for Open-Domain Question Answering](https://arxiv.org/pdf/1709.00023.pdf). Shuohang Wang, Mo Yu, Xiaoxiao Guo, Zhiguo Wang, Tim Klinger, Wei Zhang, Shiyu Chang, Gerald Tesauro, Bowen Zhou, Jing Jiang.

1. ICLR 2018. [Evidence Aggregation for Answer Re-Ranking in Open-Domain Question Answering](https://arxiv.org/pdf/1711.05116.pdf). Shuohang Wang, Mo Yu, Jing Jiang, Wei Zhang, Xiaoxiao Guo, Shiyu Chang, Zhiguo Wang, Tim Klinger, Gerald Tesauro, Murray Campbell.

1. ACL 2018. [Denoising Distantly Supervised Open-domain Question Answering](https://www.aclweb.org/anthology/P18-1161.pdf). ankai Lin, Haozhe Ji, Zhiyuan Liu, Maosong Sun.

1. ACL 2018. [Simple and Effective Multi-Paragraph Reading Comprehension](https://arxiv.org/abs/1710.10723). Christopher Clark, Matt Gardner.
  <br> 👉 Task: Multi-Paragraph MRC

1. EMNLP 2018. [Open Domain Question Answering Using Early Fusion of Knowledge Bases and Text](https://www.aclweb.org/anthology/D18-1455.pdf). Haitian Sun, Bhuwan Dhingra, Manzil Zaheer, Kathryn Mazaitis, Ruslan Salakhutdinov, William Cohen.

1. NAACL-SRW 2018. [Training a Ranking Function for Open-Domain Question Answering](https://arxiv.org/pdf/1804.04264.pdf). Phu Mon Htut, Samuel R. Bowman, Kyunghyun Cho.

### 2017

1. ACL 2017. [Reading Wikipedia to Answer Open-Domain Questions](https://arxiv.org/pdf/1704.00051.pdf). Danqi Chen, Adam Fisch, Jason Weston, Antoine Bordes.
  <br> 👉 Datasets: SQuAD
  <br> 👉 Method: TF-IDF + MRC

## Related Papers

The task of those papers are somewhat relevant to Open QA (i.e. MRC, Language Models, etc.), of much value as well


### References

1. [总结｜开放领域问答梳理系列(1)](https://mp.weixin.qq.com/s/iLE0zwhzd3ffri8VH24Z9g)

1. [收藏｜开放领域问答梳理2（文末福利)](https://mp.weixin.qq.com/s?__biz=MzIzMDM1Mjk1OA==&mid=2247485800&idx=1&sn=8971fc1358ce64e1ba621165046e30ab&chksm=e8b5f839dfc2712f4f86e91e5915111fe6ba3e4b7464ccefe38d6666e70020263cb0c8985899&cur_album_id=1721332041364881408&scene=189#wechat_redirect)

1. [丹琦女神出品｜开放域问答综述](https://blog.csdn.net/m0_37310036/article/details/121867983)

1. [ACL2020 Tutorial: Open-Domain Question Answering](https://github.com/danqi/acl2020-openqa-tutorial)
