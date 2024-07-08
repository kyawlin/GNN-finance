# GNN-finance
Curated list of `Graph Neural Network Applications in Business and Finance`
<!-- toc -->

- [Dataset](#Dataset)
- [Forecasting in Finaicial Market](#Forecasting-in-Finaicial-Market)
- [Credit Rating and Risk Management](#Credit-Rating-and-Risk-Management)
- [Fraud Detection and Money Laundering](#Fraud-Detection-and-Money-Laundering)
- [Stock Recommendation](#Stock-Recommendation)
- [Others](#Others)

<!-- tocstop -->
# Dataset
1.**The Elliptic Data Set** maps Bitcoin transactions to real entities belonging to licit categories (exchanges, wallet providers, miners, licit services, etc.) versus illicit ones (scams, malware, terrorist organizations, ransomware, Ponzi schemes, etc.). The task on the dataset is to classify the illicit and licit nodes in the graph.  https://www.kaggle.com/ellipticco/elliptic-data-set

# Forecasting in financial market
1. [Discrete-time graph neural networks for transaction prediction in Web3 social platforms](https://link.springer.com/article/10.1007/s10994-024-06579-y) (2024) Manuel Dileo, Matteo Zignani
2.  [Financial time series forecasting with multi-modality graph neural network](https://www.sciencedirect.com/science/article/abs/pii/S003132032100399X) (2022)
 DaweiCheng
3.  [Spatio-temporal Multi-graph Networks for
Demand Forecasting in Online Marketplaces](https://assets.amazon.science/50/90/df9385f840c7b0363febf882a6ad/spatio-temporal-multi-graph-networks-fordemand-forecasting-in-online-marketplaces.pdf) (2021)
 Ankit Gandhi, Aakanksha,Sivaramakrishnan Kaveri, and Vineet Chaoji
 4. [Linking Bank Clients using Graph Neural Networks Powered by Rich Transactional Data
](https://arxiv.org/abs/2001.08427) (2020)
 Valentina Shumovskaia, Kirill Fedyanin, Ivan Sukharev, Dmitry Berestnev, Maxim Panov
5. [ROLAND: GNN for Financial Networks](https://snap.stanford.edu/graphlearning-workshop/slides/stanford_graph_learning_Finance.pdf)
Jiaxuan You
6. [Exploring Graph Neural Networks for Stock Market Predictions with Rolling Window Analysis](https://arxiv.org/abs/1909.10660) (2019)
Daiki Matsunaga, Toyotaro Suzumura, Toshihiro Takahashi 
7. [Temporal Relational Ranking for Stock Prediction](https://arxiv.org/abs/1809.09441) (2019)
Fuli Feng, Xiangnan He, Xiang Wang, Cheng Luo, Yiqun Liu, Tat-Seng Chua
8. [Incorporating Corporation Relationship via Graph Convolutional Neural Networks for Stock Price Prediction](https://dl.acm.org/doi/abs/10.1145/3269206.3269269)(2018)
Yingmei Chen, Zhongyu Wei, Xuanjing Huang
9. [Knowledge-Driven Event Embedding for Stock Prediction](https://aclanthology.org/C16-1201/) (2016)
Xiao Ding, Yue Zhang, Ting Liu, Junwen Duan
10. [HATS: A Hierarchical Graph Attention Network for Stock Movement Prediction](https://arxiv.org/abs/1908.07999) (2019)
 Raehyun Kim, Chan Ho So, Minbyul Jeong, Sanghoon Lee, Jinkyu Kim, Jaewoo Kang
 11. [Spatiotemporal Multi-Graph Convolution Network for Ride-Hailing Demand Forecasting](https://ojs.aaai.org//index.php/AAAI/article/view/4247) (2019)
Xu Geng, Yaguang Li, Leye Wang
12. [Stock Forecasting using Neural Network
with Graphs](https://etheses.whiterose.ac.uk/28012/6/Shuyi_202025658_Thesis.pdf) (2021) [Thesis]
Shuyi Peng
13. [Scalable Financial Index Tracking with Graph Neural Networks](https://ieeexplore.ieee.org/document/9513742) (2021)
 Zepeng Zhang, Ziping Zhao
14. [Lifelong Property Price Prediction: A Case Study for the Toronto Real Estate Market](https://arxiv.org/pdf/2008.05880.pdf) (2020)
Hao Peng, Jianxin Li, Zheng Wang, Renyu Yang

# Credit Rating and Risk Management

1. [Financial Risk Analysis for SMEs with Graph-based Supply Chain Mining](https://www.ijcai.org/Proceedings/2020/0643.pdf) (2020)
 Shuo Yang, Zhiqiang Zhang, Jun Zhou, Yang Wang , Wang Sun, Xingyu Zhong, Yanming Fang, Quan Yu, Yuan Qi
2. [Auto-encoder based Graph Convolutional Networks for Online Financial Anti-fraud](https://ieeexplore.ieee.org/document/8759109) (2019)
Le Lv, Jianbo Cheng, Nanbo Peng
3. [EWS-GCN: Edge Weight-Shared Graph Convolutional Network for Transactional Banking Data](https://arxiv.org/abs/2009.14588) (2020)
  Ivan Sukharev, Valentina Shumovskaia, Kirill Fedyanin, Maxim Panov, Dmitry Berestnev
4. [Temporal-Aware Graph Neural Network for Credit Risk Prediction](https://epubs.siam.org/doi/pdf/10.1137/1.9781611976700.79) (2021)
Daixin Wang, Zhiqiang Zhang, Jun Zhou, Peng Cui 

# Fraud Detection and Money Laundering

 1. [A loan application fraud detection method based on knowledge graph and neural network](https://dl.acm.org/doi/abs/10.1145/3194206.3194208) (2018)
 Qing Zhan, Hang Yin
 2. [Auto-encoder based Graph Convolutional Networks for Online Financial Anti-fraud](<https://ieeexplore.ieee.org/document/8759109>) (2019)
  Le Lv; Jianbo Cheng; Nanbo Peng; Min Fan; Dongbin Zhao; Jianhong Zhang
3. [A semi-supervised graph attentive network for financial fraud detection](https://ieeexplore.ieee.org/abstract/document/8970829) (2019)
Daixin Wang; Jianbin Lin; Peng Cui; Quanhui Jia; Zhen Wang; Yanming Fang; Quan Yu; Jun Zhou; Shuang Yan
4. [Anti-money laundering in bitcoin: Experimenting with graph convolutional networks for financial forensics](https://arxiv.org/abs/1908.02591) (2019)
Mark Weber, Giacomo Domeniconi, Jie Chen, Daniel Karl I. Weidele, Claudio Bellei, Tom Robinson, Charles E. Leiserson
5. [Towards Consumer Loan Fraud Detection: Graph Neural Networks
with Role-Constrained Conditional Random Field](https://ojs.aaai.org/index.php/AAAI/article/view/16582) (2021)
Bingbing Xu, Huawei Shen, Bingjie Sun, Rong An, Qi Cao, Xueqi Cheng

# Stock Recommendation

1. [FinGAT: Financial Graph Attention Networks for
Recommending Top-K Profitable Stocks](https://arxiv.org/pdf/2106.10159.pdf) (2021)
Yi-Ling Hsu, Yu-Che Tsai
2. [Relation-aware dynamic attributed graph attention network for stocks recommendation](https://ui.adsabs.harvard.edu/abs/2022PatRe.12108119F/abstract) (2022)
Feng, Shibo ; Xu, Chen ; Zuo, Yu ; Chen, Guo ; Lin, Fan ; XiaHou, Jianbing
3. [Time-aware Graph Relational Attention Network for Stock
Recommendation](https://dl.acm.org/doi/abs/10.1145/3340531.3412160) (2020)
Xiaoting Ying, Cong Xu

# Others

1. [GFTE: Graph-based Financial Table Extraction](https://arxiv.org/abs/2003.07560) (2020)
Yiren Li, Zheng Huang, Junchi Yan, Yi Zhou, Fan Ye, Xianhui Liu
2. [Classifying and Understanding Financial Data Using Graph Neural Network](https://www.jpmorgan.com/content/dam/jpm/cib/complex/content/technology/ai-research-publications/pdf-1.pdf) (2019)
 Xiaoxiao Li, Joao Saude, Prashant Reddy, Manuela Veloso
 3. [GRAM: Graph-based Attention Model for Healthcare
Representation Learning](https://arxiv.org/pdf/1611.07012.pdf) (2017)
 Edward Choi, Mohammad Taha Bahadori, Le Song, Walter F. Stewart, Jimeng Sun
 
### Remarks.
Free free to pull request or point out the mistakes. 
