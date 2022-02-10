# openQA-reading-list
This is a paper reading list on Open-Domain Question Answering.

Our list is still incomplete and the categorization might be inappropriate. We will keep adding papers and improving the list. Any suggestions are welcomed!

## openQA Papers

### 2021

* EMNLP 2021 Findings [Dense Hierarchical Retrieval for Open-Domain Question Answering](https://export.arxiv.org/pdf/2110.15439.pdf), Ye Liu, Kazuma Hashimoto, Yingbo Zhou, Semih Yavuz, Caiming Xiong, Philip S. Yu
  <br> 👉 Datasets: Natural Questions (NQ), TriviaQA, WebQuestions, CuratedTREC (TREC)
  <br> 👉 Method: Dense Hierarchical Retrieval, utilizing both macroscopic semantics in the document and microscopic semantics specific to each passage
  
 * EMNLP 2021 Demo [Open-Domain Question-Answering for COVID-19 and Other Emergent Domains](https://arxiv.org/abs/2110.06962), Sharon Levy, Kevin Mo, Wenhan Xiong, William Yang Wang
  <br> 👉 Datasets: COVID-QA
  <br> 👉 Method: Retrieval-stage Dense Retrieval + K-Means + BM25 re-ranking, MRC-stage fine-tuned on the SQuAD2.0 + fine-tuning this model on COVIDQA

### 2020

* EMNLP 2020 [Dense Passage Retrieval for Open-Domain Question Answering](https://arxiv.org/pdf/2004.04906.pdf), Vladimir Karpukhin, Barlas Oğuz, Sewon Min, Patrick Lewis, Ledell Wu, Sergey Edunov, Danqi Chen, Wen-tau Yih
  <br> 👉 Datasets: NQ, TriviaQA, WQ, TREC, SQuAD
  <br> 👉 Method: DPR + BM25 re-ranking

### 2017

* ACL 2017 [Reading Wikipedia to Answer Open-Domain Questions](https://arxiv.org/pdf/1704.00051.pdf), Danqi Chen, Adam Fisch, Jason Weston, Antoine Bordes
  <br> 👉 Datasets: SQuAD
  <br> 👉 Method: TF-IDF + MRC
