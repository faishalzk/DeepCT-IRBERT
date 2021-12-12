# IR-BERT With DeepCT Framework as a First-stage Retrieval Pipeline

## Dataset
This code use dataset from The document contains 6980 queries or questions with each query having 1000 candidate passage lists. The dataset provided by Dai and Callan, 2019 could be downloaded from https://github.com/AdeDZY/DeepCT

## Methods
We try to combine the retrievalpower of BM25 indexed with DeepCT term weight-ing based on paper Dai and Callan, 2019 with the contextual understanding gained through IR-BERT based on paper Deshmukh and Sethi, 2020 on MS-MARCO dataset

## References
Yinqiong Cai, Yixing Fan, Jiafeng Guo, Fei Sun, Ruqing Zhang, and Xueqi Cheng. 2021. Semantic Models for the First-stage Retrieval: A Comprehensive Review. CoRR, abs/2103.04831. https://arxiv.org/abs/2103.04831

Zhuyun Dai and Jamie Callan. 2019. Context-Aware Sentence/Passage Term Importance Estimation For First Stage Retrieval. https://arxiv.org/abs/1910.10687

Zhuyun Dai and Jamie Callan. 2020. Context-Aware Document Term Weighting for Ad-Hoc Search. In Pro-ceedings of The Web Conference 2020, WWW ’20,page 1897–1907, New York, NY, USA. Association for Computing Machinery. https://dl.acm.org/doi/abs/10.1145/3366423.3380258

Anup Anand Deshmukh and Udhav Sethi. 2020. IR-BERT: Leveraging BERT for Semantic Search in Background Linking for News Articles. CoRR,abs/2007.12603. https://arxiv.org/abs/2007.12603

Luyu Gao, Zhuyun Dai, and Jamie Callan. 2021. Rethink Training of BERT Rerankers in Multi-Stage Retrieval Pipeline. CoRR, abs/2101.08751. https://arxiv.org/abs/2101.08751

Nils Reimers and Iryna Gurevych. 2019. Sentence-BERT: Sentence Embeddings using Siamese BERT-Networks. CoRR, abs/1908.10084. https://arxiv.org/abs/1908.10084

Stuart Rose, Dave Engel, Nick Cramer, and Wendy Cowley. 2010. Automatic Keyword Extraction from Individual Documents, pages 1 – 20 https://www.researchgate.net/publication/227988510_Automatic_Keyword_Extraction_from_Individual_Documents
