# openQA-reading-list
This is a paper reading list on Open-Domain Question Answering.

Our list is still incomplete and the categorization might be inappropriate. We will keep adding papers and improving the list. Any suggestions are welcomed!

## openQA Papers

### 2017

* ACL 2017 [Reading Wikipedia to Answer Open-Domain Questions](https://arxiv.org/pdf/1704.00051.pdf). Danqi Chen, Adam Fisch, Jason Weston, Antoine Bordes
  <br> 👉 Datasets: SQuAD
  <br> 👉 Method: TF-IDF + MRC

### 2018

* AAAI 2018 [R^3: Reinforced Reader-Ranker for Open-Domain Question Answering](https://arxiv.org/pdf/1709.00023.pdf). Shuohang Wang, Mo Yu, Xiaoxiao Guo, Zhiguo Wang, Tim Klinger, Wei Zhang, Shiyu Chang, Gerald Tesauro, Bowen Zhou, Jing Jiang

* ICLR 2018 [Evidence Aggregation for Answer Re-Ranking in Open-Domain Question Answering](https://arxiv.org/pdf/1711.05116.pdf). Shuohang Wang, Mo Yu, Jing Jiang, Wei Zhang, Xiaoxiao Guo, Shiyu Chang, Zhiguo Wang, Tim Klinger, Gerald Tesauro, Murray Campbell

* ACL 2018 [Denoising Distantly Supervised Open-domain Question Answering](https://www.aclweb.org/anthology/P18-1161.pdf). ankai Lin, Haozhe Ji, Zhiyuan Liu, Maosong Sun

* EMNLP 2018 [Open Domain Question Answering Using Early Fusion of Knowledge Bases and Text](https://www.aclweb.org/anthology/D18-1455.pdf). Haitian Sun, Bhuwan Dhingra, Manzil Zaheer, Kathryn Mazaitis, Ruslan Salakhutdinov, William Cohen

### 2019

* OpenAI 2019 [Language Models are Unsupervised Multitask Learners](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf). Alec Radford, Jeffrey Wu, Rewon Child, David Luan, Dario Amodei, Ilya Sutskever

* NAACL 2019 (demonstration) [End-to-end Open-domain Question Answering with BERTserini](https://arxiv.org/pdf/1902.01718.pdf). Wei Yang, Yuqing Xie, Aileen Lin, Xingyu Li, Luchen Tan, Kun Xiong, Ming Li, Jimmy Lin

* ACL 2019 [Latent Retrieval for Weakly Supervised Open Domain Question Answering](https://aclanthology.org/P19-1612.pdf). Kenton Lee, Ming-Wei Chang, Kristina Toutanova

* ACL 2019 [Real-Time Open-Domain Question Answering with Dense-Sparse Phrase Index](https://arxiv.org/pdf/1906.05807.pdf). Minjoon Seo, Jinhyuk Lee, Tom Kwiatkowski, Ankur P. Parikh, Ali Farhadi, Hannaneh Hajishirzi

* ACL 2019 [Improving Question Answering over Incomplete KBs with Knowledge-Aware Reader](https://www.aclweb.org/anthology/P19-1417.pdf). Wenhan Xiong, Mo Yu, Shiyu Chang, Xiaoxiao Guo, William Yang Wang

* EMNLP 2019 [A Discrete Hard EM Approach for Weakly Supervised Question Answering](https://arxiv.org/pdf/1909.04849.pdf). Sewon Min, Danqi Chen, Hannaneh Hajishirzi, Luke Zettlemoyer

* EMNLP 2019 [Multi-passage BERT: A Globally Normalized BERT Model for Open-domain Question Answering](https://arxiv.org/pdf/1908.08167.pdf). Zhiguo Wang, Patrick Ng, Xiaofei Ma, Ramesh Nallapati, Bing Xiang

* EMNLP 2019 [PullNet: Open Domain Question Answering with Iterative Retrieval on Knowledge Bases and Text](https://arxiv.org/pdf/1904.09537.pdf). Haitian Sun, Tania Bedrax-Weiss, William W. Cohen

* arXiv 2019 [Knowledge Guided Text Retrieval and Reading for Open Domain Question Answering](https://arxiv.org/pdf/1911.03868.pdf). Sewon Min, Danqi Chen, Luke Zettlemoyer, Hannaneh Hajishirzi

### 2020

* ACL 2020 [Contextualized Sparse Representations for Real-Time Open-Domain Question Answering](https://arxiv.org/pdf/1911.02896.pdf). Jinhyuk Lee, Minjoon Seo, Hannaneh Hajishirzi, Jaewoo Kang

* ICLR 2020 [Learning to Retrieve Reasoning Paths over Wikipedia Graph for Question Answering](https://arxiv.org/pdf/1911.10470.pdf). Akari Asai, Kazuma Hashimoto, Hannaneh Hajishirzi, Richard Socher, Caiming Xiong

* ICML 2020 [REALM: Retrieval-Augmented Language Model Pre-Training](https://arxiv.org/pdf/2002.08909.pdf).
Kelvin Guu, Kenton Lee, Zora Tung, Panupong Pasupat, Ming-Wei Chang

* EMNLP 2020 [Dense Passage Retrieval for Open-Domain Question Answering](https://arxiv.org/pdf/2004.04906.pdf), Vladimir Karpukhin, Barlas Oğuz, Sewon Min, Patrick Lewis, Ledell Wu, Sergey Edunov, Danqi Chen, Wen-tau Yih
  <br> 👉 Datasets: NQ, TriviaQA, WQ, TREC, SQuAD
  <br> 👉 Method: DPR + BM25 re-ranking

* EMNLP 2020 [How Much Knowledge Can You Pack Into the Parameters of a Language Model?](https://arxiv.org/pdf/2002.08910.pdf). Adam Roberts, Colin Raffel, Noam Shazeer

* NeurIPS 2020 [Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks](https://arxiv.org/pdf/2005.11401.pdf). Patrick Lewis, Ethan Perez, Aleksandara Piktus, Fabio Petroni, Vladimir Karpukhin, Naman Goyal, Heinrich Küttler, Mike Lewis, Wen-tau Yih, Tim Rocktäschel, Sebastian Riedel, Douwe Kiela

* NeurIPS 2020 [Language Models are Few-Shot Learners](https://arxiv.org/pdf/2005.14165.pdf). Tom B. Brown, Benjamin Mann, Nick Ryder et al

### 2021

 * EMNLP 2021 Demo [Open-Domain Question-Answering for COVID-19 and Other Emergent Domains](https://arxiv.org/abs/2110.06962). Sharon Levy, Kevin Mo, Wenhan Xiong, William Yang Wang
  <br> 👉 Datasets: COVID-QA
  <br> 👉 Method: Retrieval-stage Dense Retrieval + K-Means + BM25 re-ranking, MRC-stage fine-tuned on the SQuAD2.0 + fine-tuning this model on COVIDQA

* EMNLP 2021 Findings [Dense Hierarchical Retrieval for Open-Domain Question Answering](https://export.arxiv.org/pdf/2110.15439.pdf). Ye Liu, Kazuma Hashimoto, Yingbo Zhou, Semih Yavuz, Caiming Xiong, Philip S. Yu
  <br> 👉 Datasets: Natural Questions (NQ), TriviaQA, WebQuestions, CuratedTREC (TREC)
  <br> 👉 Method: Dense Hierarchical Retrieval, utilizing both macroscopic semantics in the document and microscopic semantics specific to each passage
  

## Related Papers

The task of those papers are somewhat relevant to Open QA (i.e. MRC, Language Models, etc.), of much value as well
