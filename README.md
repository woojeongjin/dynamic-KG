# Dynamic Knowledge Graph Completion
This page is to summarize important materials about *dynamic (temporal) knowledge graph completion* and *dynamic graph embedding*.

## Background

## List of Related Works
- **Temporal knowledge graph completion**
	- [Know-Evolve: Deep Temporal Reasoning for Dynamic Knowledge Graphs](https://arxiv.org/abs/1705.05742)
		- Rakshit Trivedi, Hanjun Dai, Yichen Wang, Le Song. ICML 2017.
		- [Video](https://vimeo.com/238228194)
		- [Code (cpp)](https://github.com/rstriv/Know-Evolve)
	- [Learning Sequence Encoders for Temporal Knowledge Graph Completion](https://arxiv.org/abs/1809.03202)
		- Alberto Garcia-Duran, Sebastijan Dumancic, Mathias Niepert. EMNLP 2018.
	- [Towards time-aware knowledge graph completion](http://aclweb.org/anthology/C16-1161)
		- Tingsong Jiang, Tianyu Liu, Tao Ge, Lei Sha, Baobao Chang, Sujian Li and Zhifang Sui. COLING 2016
	- [Predicting the co-evolution of event and knowledge graphs](https://arxiv.org/abs/1512.06900)
		- Cristóbal Esteban, Volker Tresp, Yinchong Yang, Stephan Baier, Denis Krompaß. FUSION 2016.
	- [Deriving validity time in knowledge graph](https://dl.acm.org/citation.cfm?id=3191639)
		- Julien Leblay and Melisachew Wudage Chekol. WWW 2018.
	- [HyTE: Hyperplane-based Temporally aware Knowledge Graph Embedding](http://aclweb.org/anthology/D18-1225)
		- Shib Sankar Dasgupta, Swayambhu Nath Ray, Partha Talukdar. EMNLP 2018.
		- [Code (TF based)](https://github.com/malllabiisc/HyTE)

- **Dynamic graph embedding**
	- [Representation Learning over Dynamic Graphs](https://arxiv.org/abs/1803.04051)
		- Rakshit Trivedi, Mehrdad Farajtabar, Prasenjeet Biswal, Hongyuan Zha. ArXiv.
		- [DyREP: Learning Representations over Dynamic Graphs](https://openreview.net/forum?id=HyePrhR5KX)
	- [DynGEM: Deep Embedding Method for Dynamic Graphs](https://arxiv.org/abs/1805.11273)
		- Palash Goyal, Nitin Kamra, Xinran He, Yan Liu. ArXiv.
	- [Graph2Seq: Scalable Learning Dynamics for Graphs](https://openreview.net/forum?id=Ske7ToC5Km)
		- Anonymous, under review at ICLR 2019.
	- [Dynamic Graph Representation Learning via Self-Attention Networks](https://openreview.net/forum?id=HylsgnCcFQ)
		- Anonymous, under review at ICLR 2019.
	- [Continuous-Time Dynamic Network Embeddings](http://ryanrossi.com/pubs/nguyen-et-al-WWW18-BigNet.pdf)
		- Giang Hoang Nguyen, John Boaz Lee, Ryan A. Rossi, Nesreen K. Ahmed, Eunyee Koh, Sungchul Kim. WWW 2018.
	- [GC-LSTM: Graph Convolution Embedded LSTM for Dynamic Link Prediction](https://arxiv.org/pdf/1812.04206.pdf)
		- Jinyin Chen, Xuanheng Xu, Yangyang Wu, Haibin Zheng
	- [Learning Dynamic Embeddings from Temporal Interaction Networks](https://www-cs.stanford.edu/~srijan/pubs/paper-interactions.pdf)
		- Srijan Kumar, Xikun Zhang, Jure Leskovec
	- [Graph Convolutional Neural Networks for Web-Scale Recommender Systems](https://arxiv.org/pdf/1806.01973)
		- Rex Ying, Ruining He, Kaifeng Chen, Pong Eksombatchai, William L. Hamilton, Jure Leskovec
	- [Stochastic Training of Graph Convolutional Networks with Variance Reduction](https://arxiv.org/pdf/1710.10568.pdf)
		- Jianfei Chen, Jun Zhu, Le Song
	- [Dynamic Graph Convolutional Networks](https://arxiv.org/pdf/1704.06199.pdf)
		- Franco Manessi, Alessandro Rozza, Mario Manzo
	- [Streaming Graph Neural Networks](https://arxiv.org/pdf/1810.10627.pdf)
		- Yao Ma, Ziyi Guo, Zhaochun Ren, Eric Zhao, Jiliang Tang, Dawei Yin

- **Knowledge graph embedding**
	- [Modeling Relational Data with Graph Convolutional Networks](https://arxiv.org/abs/1703.06103)
		- Michael Schlichtkrull, Thomas N. Kipf, Peter Bloem, Rianne van den Berg, Ivan Titov, Max Welling. ESWC 2018.
		- [Code (Keras based)](https://github.com/tkipf/relational-gcn), [Code (TF based)](https://github.com/MichSchli/RelationPrediction)

- **Static graph embedding**
	- [Inductive Representation Learning on Large Graphs](https://www-cs-faculty.stanford.edu/people/jure/pubs/graphsage-nips17.pdf)
		- William L. Hamilton, Rex Ying, Jure Leskovec
		- [Code (TF based)](https://github.com/williamleif/GraphSAGE), [Code (Pytorch based)](https://github.com/williamleif/graphsage-simple/)

- **Relational inference**
	- [Neural Relational Inference for Interacting Systems](https://arxiv.org/abs/1802.04687)
		- Thomas Kipf, Ethan Fetaya, Kuan-Chieh Wang, Max Welling, Richard Zemel. ICML 2018.
		- [Code (Pytorch based)](https://github.com/ethanfetaya/NRI)

- **Survey**
	- [Deep Learning on Graphs: A Survey](https://arxiv.org/abs/1812.04202)
		- Ziwei Zhang, Peng Cui, Wenwu Zhu
	- [Graph Neural Networks: A Review of Methods and Applications](https://arxiv.org/abs/1812.08434)
		- Jie Zhou, Ganqu Cui, Zhengyan Zhang, Cheng Yang, Zhiyuan Liu, Maosong Sun
	- [A Comprehensive Survey on Graph Neural Networks](https://arxiv.org/abs/1901.00596)
		- Zonghan Wu, Shirui Pan, Fengwen Chen, Guodong Long, Chengqi Zhang, Philip S. Yu
	- [A Comprehensive Survey of Graph Embedding: Problems, Techniques and Applications](https://arxiv.org/abs/1709.07604)
		- Hongyun Cai, Vincent W. Zheng, Kevin Chen-Chuan Chang

## Useful Libararies
- [Deep graph library](https://www.dgl.ai)
