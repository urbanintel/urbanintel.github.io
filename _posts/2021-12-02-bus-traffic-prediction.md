---
layout: post
title:  "Bus Demand Prediction"
category: [AI]
date:   2021-12-01 10:22:00 +0900
# prevPart: _posts/2021-11-30-traffic-prediction.md
published: false
---
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

<p align="center"><img src="/assets/img/posts/PCM20190308000187990_P4.jpg" width="500"></p>

The data collected by regular alight tags are not only used for public transportation policy establishment such as demand-tailored route reorganization based on big data, but also to provide citizens with various information necessary for daily life, such as bus congestion levels and the number of people getting on and off at each stop. However, the researches for bus demand prediction is limited, as they simply use geographical neighborhood or line connection network in the modeling, while ignoring the social meaning of the purpose of the destination. If we are able to reason why people are congested in specific time zone, it gives more explaination about the cause of the congestion and further can be used for prediction in the future. Here are some of the related works that has been already been done in this field:

<!-- * WWW 2021: Fine-Grained Urban Flow Prediction
* AAAI 2020: Potential passenger flow prediction: A novel study for urban transportation development
* IJCAI	2019:	STG2Seq - Spatial-Temporal Graph to Sequence Model for Multi-step Passenger Demand Forecasting.
* KDD	2019:	Origin-Destination Matrix Prediction via Graph Convolution - a New Perspective of Passenger Demand Modeling.
* ECML/PKDD 2018:	Discovering Urban Travel Demands Through Dynamic Zone Correlation in Location-Based Social Networks.
* AAAI	2018:	DeepUrbanMomentum - An Online Deep-Learning System for Short-Term Urban Mobility Prediction.
* Potential passenger flow prediction: A novel study for urban transportation development (AAAI-20)
* Community-Aware Multi-Task Transportation Demand Prediction. (AAAI-21)
* Revisiting spatial-temporal similarity: A deep learning framework for traffic prediction (AAAI-19)
* Knowledge Adaption for Demand Prediction based on Multi-task Memory Neural Network. (CIKM-20)
* A Fast and Accurate Method for Estimating People Flow from Spatiotemporal Population Data (IJCAI-18)
* GSTNet: Global Spatial-Temporal Network for Traffic Flow Prediction (IJCAI-19)
* A Sequential Convolution Network for Population Flow Prediction with Explicitly Correlation Modelling (IJCAI-20)
* Co-Prediction of Multiple Transportation Demands Based on Deep Spatio-Temporal Neural Network (KDD-19)
* Predicting short-term bus passenger demand using a pattern hybrid approach (TRC-14)
* Generating demand responsive bus routes from social network data analysis (TRC-21) -->

# 1. Transportation Demand Prediction

1. {% reference liang2021fine %}
   * Keywords: Hierarchical graph
   * They found
2. {% reference gong2020potential %}
3. 
* Bai, Lei, et al. "Stg2seq: Spatial-temporal graph to sequence model for multi-step passenger demand forecasting." arXiv preprint arXiv:1905.10069 (2019).
  * Hello
  * Malfoysdfsd

<!-- 상시적인 하차태그로 수집된 자료는 빅데이터를 기반으로 한 수요 맞춤형 노선개편 등 대중교통 정책수립에 사용될 뿐만 아니라 버스 내 혼잡도나 정류소별 승하차 인원 등 실생활에 필요한 다양한 정보를 시민들에세 제공할 수 있게 된다.   -->

Cited References
{% bibliography -cite %}