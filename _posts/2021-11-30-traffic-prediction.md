---
layout: post
title:  "Traffic Prediction"
category: [AI]
date:   2021-11-30 15:43:00 +0900
published: false
---
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

Traffic prediction is one of the most interesting topics in recent AI conferences. Traffic prediction is challenging yet intriguing due to its temporal and spatial complexities. Since traffic values such as traffic volume or speed are measured in real numbers, it is rather easier to define a problem as follows:

$$ [X^{(1)}, ..., X^{(t-1)};\mathcal{G}] \xrightarrow{h(\cdot)} \hat{X}^{(t)} $$

Where $$X^{(t)} \in \mathbb{R}^{N_x}$$ is a vector of traffic values of $$N_x$$ sensors at timestamp $$t$$, $$\mathcal{G}$$ is a connection network between the traffic sensors, and $$h(\cdot)$$ is a prediction model that can be assumed as a function. We normally evaluate the performance of the preiction model $$h(\cdot)$$ using *mean absolute error (MAE)*, *mean squared error (MSE)*, *root mean squared error (RMSE)*, *mean absolute percent error (MAPE)*,  or *normalized mean absolute error (NMAE)*. These evaluation metrics may also be used as loss function if the model is based on deep neural network.

Although we first described the problem as we can use all the historical values to predict the next step, it is not feasible to require all the historical data for each next step prediction. Therefore, we may define a problem in rather narrowed down fashion as follows:

$$ [X^{(t-P+1)}, ..., X^{(t)};\mathcal{G}] \xrightarrow{h(\cdot)} [\hat{X}^{(t+1)}, ..., \hat{X}^{(t+Q)}] $$

Here we defined problem to predict next $$Q$$ time stemps based on previous $$P$$ time steps. This assumes that the temporal correlation pattern can be found within $$P$$- timesteps to predict the next $$Q$$- timesteps while the spatial correlation between the traffic sensors catched by the sensor network $$\mathcal{G}$$.

Here are some list of papers that you can consider as baselines.

* **DCRNN** - Li, Yaguang, et al. "Diffusion convolutional recurrent neural network: Data-driven traffic forecasting." arXiv preprint arXiv:1707.01926 (2017).
* **ST-MetaNet** - Pan, Zheyi, et al. "Urban traffic prediction from spatio-temporal data using deep meta learning." Proceedings of the 25th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining. 2019.
* **GMAN** - Zheng, Chuanpan, et al. "Gman: A graph multi-attention network for traffic prediction." Proceedings of the AAAI Conference on Artificial Intelligence. Vol. 34. No. 01. 2020.

Here are some of my favorite researchers who are working in this field.

* [Junbo Zhang](https://zhangjunbo.org/)
