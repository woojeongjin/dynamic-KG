# Dynamic Knowledge Graph Completion
This page is to summarize important materials about *dynamic (temporal) knowledge graph completion* and *dynamic graph embedding*.

# Bookmarks
- [Temporal Knowledge Graph Completion](#Temporal-knowledge-graph-completion-/-reasoning)
- [Dynamic Graph Embedding](#Dynamic-graph-embedding)
- [Knowledge Graph Embedding](#Knowledge-graph-embedding)
- [Static Graph Embedding](#Static-graph-embedding)
- [Survey](#Survey)
- [Others](#Others)
- [Useful Libararies](#Useful-Libararies)

## Temporal Knowledge Graph Completion / Reasoning
- [Recurrent Event Network: Global Structure Inference over Temporal Knowledge Graph](https://arxiv.org/abs/1904.05530)
	- Woojeong Jin, He Jiang, Meng Qu, Tong Chen, Changlin Zhang, Pedro Szekely, Xiang Ren. Short version accepted to ICLR-RLGM, 2019.
		- This work is on an *extrapolation* problem which is to make predictions at unobserved times, different from interpolation work.
		- Proposes a novel neural architecture for modeling complex entity interaction sequences, which consists of a *recurrent event encoder* and a *neighborhood aggregator*.
		- Explores various neighborhood aggregators: a multi-relational graph aggregator demonstrates its effectiveness among them.
		- [Code and Data](https://github.com/INK-USC/re-net)
<!-- - [Know-Evolve: Deep Temporal Reasoning for Dynamic Knowledge Graphs](https://arxiv.org/abs/1705.05742)
	- Rakshit Trivedi, Hanjun Dai, Yichen Wang, Le Song. ICML 2017.
	- [Video](https://vimeo.com/238228194)
	- [Code (cpp)](https://github.com/rstriv/Know-Evolve) -->
- [Learning Sequence Encoders for Temporal Knowledge Graph Completion](https://arxiv.org/abs/1809.03202) (Interpolation)
	- Alberto Garcia-Duran, Sebastijan Dumancic, Mathias Niepert. EMNLP 2018.
- [Towards time-aware knowledge graph completion](http://aclweb.org/anthology/C16-1161) (Interpolation)
	- Tingsong Jiang, Tianyu Liu, Tao Ge, Lei Sha, Baobao Chang, Sujian Li and Zhifang Sui. COLING 2016.
- [Deriving validity time in knowledge graph](https://dl.acm.org/citation.cfm?id=3191639) (Interpolation)
	- Julien Leblay and Melisachew Wudage Chekol. WWW Workshop 2018.
- [HyTE: Hyperplane-based Temporally aware Knowledge Graph Embedding](http://aclweb.org/anthology/D18-1225) (Interpolation)
	- Shib Sankar Dasgupta, Swayambhu Nath Ray, Partha Talukdar. EMNLP 2018.
	- [Code (TF based)](https://github.com/malllabiisc/HyTE)
- [Predicting the co-evolution of event and knowledge graphs](https://arxiv.org/abs/1512.06900)
	- Cristóbal Esteban, Volker Tresp, Yinchong Yang, Stephan Baier, Denis Krompaß. FUSION 2016.

## Dynamic Graph Embedding
- [DyREP: Learning Representations over Dynamic Graphs](https://openreview.net/forum?id=HyePrhR5KX) (Extrapolation)
	- Rakshit Trivedi, Mehrdad Farajtabar, Prasenjeet Biswal, Hongyuan Zha. ICLR 2019.
- [DynGEM: Deep Embedding Method for Dynamic Graphs](https://arxiv.org/abs/1805.11273)
	- Palash Goyal, Nitin Kamra, Xinran He, Yan Liu. IJCAI 2017.
- [Graph2Seq: Scalable Learning Dynamics for Graphs](https://openreview.net/forum?id=Ske7ToC5Km)
	- Shaileshh Bojja Venkatakrishnan, Mohammad Alizadeh, Pramod Viswanath
- [Dynamic Graph Representation Learning via Self-Attention Networks](https://openreview.net/forum?id=HylsgnCcFQ)
	- Aravind Sankar, Yanhong Wu, Liang Gou, Wei Zhang, Hao Yang
- [Continuous-Time Dynamic Network Embeddings](http://ryanrossi.com/pubs/nguyen-et-al-WWW18-BigNet.pdf)
	- Giang Hoang Nguyen, John Boaz Lee, Ryan A. Rossi, Nesreen K. Ahmed, Eunyee Koh, Sungchul Kim. WWW 2018.
- [GC-LSTM: Graph Convolution Embedded LSTM for Dynamic Link Prediction](https://arxiv.org/pdf/1812.04206.pdf)
	- Jinyin Chen, Xuanheng Xu, Yangyang Wu, Haibin Zheng
- [Learning Dynamic Embeddings from Temporal Interaction Networks](https://www-cs.stanford.edu/~srijan/pubs/paper-interactions.pdf)
	- Srijan Kumar, Xikun Zhang, Jure Leskovec
- [Dynamic Graph Convolutional Networks](https://arxiv.org/pdf/1704.06199.pdf)
	- Franco Manessi, Alessandro Rozza, Mario Manzo
- [Streaming Graph Neural Networks](https://arxiv.org/pdf/1810.10627.pdf)
	- Yao Ma, Ziyi Guo, Zhaochun Ren, Eric Zhao, Jiliang Tang, Dawei Yin
<!-- - [dynnode2vec: Scalable Dynamic Network Embedding](https://arxiv.org/abs/1812.02356)
 	- Sedigheh Mahdavi, Shima Khoshraftar, Aijun An -->
- [Dynamic Network Embedding: An Extended Approach for Skip-gram based Network Embedding](https://www.ijcai.org/proceedings/2018/0288.pdf)
	- Lun Du, Yun Wang, Guojie Song, Zhicong Lu, Junshan Wang
- [EvolveGCN: Evolving Graph Convolutional Networks for Dynamic Graphs](https://arxiv.org/abs/1902.10191)
	- Aldo Pareja, Giacomo Domeniconi, Jie Chen, Tengfei Ma, Toyotaro Suzumura, Hiroki Kanezashi, Tim Kaler, Charles E. Leisersen, ArXiv.
- [Gated Residual Recurrent Graph Neural Networks for Traffic Prediction](https://oar.a-star.edu.sg/jspui/bitstream/123456789/3020/1/AAAI-ChenC.4591.pdf#page8)
	- Cen Chen, Kenli Li, Sin G. Teo, Xiaofeng Zou, Kang Wang, Jie Wang, Zeng Zeng, AAAI 2019.
- [Structured Sequence Modeling with Graph Convolutional Recurrent Networks](https://arxiv.org/abs/1612.07659)
	- Youngjoo Seo, Michaël Defferrard, Pierre Vandergheynst, Xavier Bresson, ICONIP 2017.
- [Dynamic Network Embedding by Modeling Triadic Closure Process](http://yangy.org/works/dynamictriad/dynamic_triad.pdf)
	- Lekui Zhou, Yang Yang, Xiang Ren, Fei Wu, Yueting Zhuang. AAAI 2018.

## Knowledge Graph Embedding
- [Modeling Relational Data with Graph Convolutional Networks](https://arxiv.org/abs/1703.06103)
	- Michael Schlichtkrull, Thomas N. Kipf, Peter Bloem, Rianne van den Berg, Ivan Titov, Max Welling. ESWC 2018.
	- [Code (Keras based)](https://github.com/tkipf/relational-gcn), [Code (TF based)](https://github.com/MichSchli/RelationPrediction)
- [Neural Relational Inference for Interacting Systems](https://arxiv.org/abs/1802.04687)
	- Thomas Kipf, Ethan Fetaya, Kuan-Chieh Wang, Max Welling, Richard Zemel. ICML 2018.
	- [Code (Pytorch based)](https://github.com/ethanfetaya/NRI)
- [Interpretable Graph Convolutional Neural Networks for Inference on Noisy Knowledge Graphs](https://arxiv.org/abs/1812.00279)
	- Daniel Neil, Joss Briody, Alix Lacoste, Aaron Sim, Paidi Creed, Amir Saffari. ICONIP 2017.

## Static Graph Embedding
- [Inductive Representation Learning on Large Graphs](https://www-cs-faculty.stanford.edu/people/jure/pubs/graphsage-nips17.pdf)
	- William L. Hamilton, Rex Ying, Jure Leskovec
	- [Code (TF based)](https://github.com/williamleif/GraphSAGE), [Code (Pytorch based)](https://github.com/williamleif/graphsage-simple/)
- [Graph Convolutional Neural Networks for Web-Scale Recommender Systems](https://arxiv.org/pdf/1806.01973)
	- Rex Ying, Ruining He, Kaifeng Chen, Pong Eksombatchai, William L. Hamilton, Jure Leskovec
- [Stochastic Training of Graph Convolutional Networks with Variance Reduction](https://arxiv.org/pdf/1710.10568.pdf)
	- Jianfei Chen, Jun Zhu, Le Song
- [A Higher-Order Graph Convolutional Layer](http://sami.haija.org/papers/high-order-gc-layer.pdf)
	- Sami Abu-El-Haija, Nazanin Alipourfard, Hrayr Harutyunyan, Amol Kapoor, Bryan Perozzi
- [Higher-order Graph Convolutional Networks](http://ryanrossi.com/pubs/Higher-order-GCNs.pdf)
	- John Boaz Lee, Ryan A. Rossi, Xiangnan Kong, Sungchul Kim, Eunyee Koh, and Anup Rao


## Other Survey Papers
- [Deep Learning on Graphs: A Survey](https://arxiv.org/abs/1812.04202)
	- Ziwei Zhang, Peng Cui, Wenwu Zhu
- [Graph Neural Networks: A Review of Methods and Applications](https://arxiv.org/abs/1812.08434)
	- Jie Zhou, Ganqu Cui, Zhengyan Zhang, Cheng Yang, Zhiyuan Liu, Maosong Sun
- [A Comprehensive Survey on Graph Neural Networks](https://arxiv.org/abs/1901.00596)
	- Zonghan Wu, Shirui Pan, Fengwen Chen, Guodong Long, Chengqi Zhang, Philip S. Yu
- [A Comprehensive Survey of Graph Embedding: Problems, Techniques and Applications](https://arxiv.org/abs/1709.07604)
	- Hongyun Cai, Vincent W. Zheng, Kevin Chen-Chuan Chang
- [How Powerful are Graph Neural Networks?](https://arxiv.org/abs/1810.00826)
	- Keyulu Xu, Weihua Hu, Jure Leskovec, Stefanie Jegelka. ICLR 2019.
- [Relational Representation Learning for Dynamic (Knowledge) Graphs: A Survey](https://arxiv.org/abs/1905.11485)
	- Seyed Mehran Kazemi, Rishab Goel, Kshitij Jain, Ivan Kobyzev, Akshay Sethi, Peter Forsyth, Pascal Poupart

## Others
- [Temporal Convolutional Networks: A Unified Approach to Action Segmentation](https://arxiv.org/abs/1608.08242)
	- Colin Lea, Rene Vidal, Austin Reiter, Gregory D. Hager
- [What to Do Next: Modeling User Behaviors by Time-LSTM](https://www.ijcai.org/proceedings/2017/0504.pdf)
	- Yu Zhu, Hao Li, Yikang Liao, Beidou Wang, Ziyu Guan, Haifeng Liu, Deng Cai. IJCAI 2017.
- [Patient Subtyping via Time-Aware LSTM Networks](http://biometrics.cse.msu.edu/Publications/MachineLearning/Baytasetal_PatientSubtypingViaTimeAwareLSTMNetworks.pdf)
	- Inci M. Baytas, Cao Xiao, Xi Zhang, Fei Wang, Anil K. Jain, Jiayu Zhou. KDD 2017.

## Useful Libararies
- [Deep graph library](https://www.dgl.ai)
- [Pytorch geometric](https://github.com/rusty1s/pytorch_geometric)
