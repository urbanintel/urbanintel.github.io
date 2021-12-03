---
layout: post
title:  "Recent Deep Learning for Road Traffic Prediction "
category: [AI]
date:   2021-12-03 10:22:00 +0900
# prevPart: _posts/2021-11-30-traffic-prediction.md
published: true
---
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

More references are found here in this survey.

* Deep learning for road traffic forecasting: Does it make a difference? {% cite manibardo2021deep %}
* Graph neural network for traffic forecasting: A survey {% cite jiang2021graph %}
* Traffic Prediction Survey <https://github.com/aprbw/traffic_prediction>

Conferences of interest:

* KDD
* AAAI
* CIKM
* ICLR
* WWW
* SIGSPATIAL


# DCRNN (ICLR-18) {% cite DBLP:conf/iclr/LiYS018 %}

<p align=center><img src="https://github.com/liyaguang/DCRNN/raw/master/figures/model_architecture.jpg" width=800></p>

* Paper: [Diffusion Convolutional Recurrent Neural Network: Data-Driven Traffic Forecasting](https://openreview.net/forum?id=SJiHXGWAZ)
* Code: <https://github.com/liyaguang/DCRNN>

# ST-GCN (IJCAI-18) {% cite DBLP:conf/ijcai/YuYZ18 %}


<p align=center><img src="https://github.com/VeritasYin/STGCN_IJCAI-18/raw/master/figures/Graph_Structured_Traffic_Data.png" width=360><img src="https://github.com/VeritasYin/STGCN_IJCAI-18/raw/master/figures/STGCN.png" width=450></p>

* Paper: [Spatio-Temporal Graph Convolutional Networks: A Deep Learning Framework for Traffic Forecasting.](https://doi.org/10.24963/ijcai.2018/505)
* Code: <https://github.com/VeritasYin/STGCN_IJCAI-18>

# ST-MetaNet (KDD-19) {% cite DBLP:conf/kdd/PanLW00Z19 %}

<p align=center><img src="https://github.com/panzheyi/ST-MetaNet/raw/master/overview.jpg" width=800></p>

* Paper: [Urban traffic prediction from spatio-temporal data using deep meta learning](https://doi.org/10.1145/3292500.3330884)
* Code: <https://github.com/panzheyi/ST-MetaNet>

# Graph WaveNet (IJCAI-19) {% cite DBLP:conf/ijcai/WuPLJZ19 %}


<p align=center><img src="https://github.com/nnzhan/Graph-WaveNet/raw/master/fig/model.png" width=400></p>

* Paper: [Graph WaveNet for Deep Spatial-Temporal Graph Modeling](https://doi.org/10.24963/ijcai.2019/264)
* Code: <https://github.com/nnzhan/Graph-WaveNet>

# GMAN (AAAI-20) {% cite DBLP:conf/aaai/ZhengFW020 %}

<p align=center><img src="https://github.com/zhengchuanpan/GMAN/raw/master/figure/GMAN.png" width=600></p>

* Paper: [GMAN: A Graph Multi-Attention Network for Traffic Prediction](https://ojs.aaai.org/index.php/AAAI/article/view/5477)
* Code: <https://github.com/zhengchuanpan/GMAN>

# STAG-GCN (CIKM-20) {% cite DBLP:conf/cikm/LuGJFZ20 %}

<p align=center><img src="https://github.com/RobinLu1209/STAG-GCN/raw/master/figures/system_model.png" width=700></p>

* Paper: [Spatiotemporal Adaptive Gated Graph Convolution Network for Urban Traffic Flow Forecasting](https://dl.acm.org/doi/10.1145/3340531.3411894)
* Code: <https://github.com/RobinLu1209/STAG-GCN>


# GTS (ICLR-21) {% cite DBLP:conf/iclr/Shang0B21 %}

<p align=center><img src="/assets/../../assets/img/posts/GTS-architecture.png" width=800></p>

* Paper: [Discrete Graph Structure Learning for Forecasting Multiple Time Series](https://openreview.net/forum?id=WEHSlH5mOk)
* Code: <https://github.com/chaoshangcs/GTS>




## References

{% bibliography -cite %}