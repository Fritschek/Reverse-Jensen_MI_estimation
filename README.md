# Reverese-Jensen_MI_estimation
 Estimation of Mutual Information based on a reverse Jensen inequality approach
 
 The RJE (Reverse-Jensen MI Estimator) is based on the recent submitted paper [Fritschek et al., "Neural Mutual Information Estimation for ChannelCoding: State-of-the-Art Estimators, Analysis, andPerformance Comparison", accepted at SPAWC 2020]()
 
 The code is a shortened version of the [colab code](https://colab.research.google.com/github/google-research/google-research/blob/master/vbmi/vbmi_demo.ipynb)
 by Ben Poole, which shows differences in mutual information estimators, based on their analyses in the paper [Poole et al., "On Variational Bounds of Mutual Information", ICML 2019](https://arxiv.org/abs/1905.06922)
 
 We removed the interpolation bounds, and unnecessary code due to those bounds, as we want to focus on simpler methods, and 1)
 added the recent SMILE estimator, based on the paper [Song et al., "Understanding the Limitations of Variational Mutual Information Estimators", ICLR 2020](https://arxiv.org/abs/1910.06222), 2) added our RJE Estimator, and 3) added wireless channel models and supporting functions.
