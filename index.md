## **Federated Learning under Heterogeneous Resource Constraints**

### Participants:

* Jimmy Lin
* Ruofan Liang

### Description:

~~In the context of federated learning (FL), updates to some parameters are more important than others, since model parameters converge non-uniformly. There might be methods of predicting that some updates are unnecessary. We would like to build a scheduler that generates tasks tailored to the capacity of each device while taking into consideration the non-uniform convergence of parameters.~~

(Updated) With increasing regulations on the management of private user data, federated learning has become a promising solution for learning global models without moving private user data. However, by keeping data on users’ personal devices, the data used for training can differ based on each user’s unique behaviours. These differences, referred to as statistical heterogeneity, violate the IID assumption of federated learning. In this work, we explore new ways of introducing statistical heterogeneity in image classification. Furthermore, we propose two metrics for detecting statistical heterogeneity using the updates submitted by participating clients to the parameter server. Our experiments show that the negative impact of statistical heterogeneity on convergence extends to feature distribution skew, same-feature, different-labels, and same-label, different-features. Results also show that one of our metrics can reliably detect statistical heterogeneity during training

### Timeline:

| Part of the project    | Deadline |
| ---------------------- | -------- |
| [Proposal](https://1drv.ms/b/s!AtiMpA7HPe0QhroXVhudx1adUrWmuA?e=JNeBbD)           | Feb 3    |
| [Progress report](https://1drv.ms/b/s!AtiMpA7HPe0QhrsCBjEoZ4xXGE1kHg?e=ay7xEg)    | Mar 3    |
| [Class presentation](https://1drv.ms/b/s!AtiMpA7HPe0Qhr58iTvy7hse0oezkw?e=s9rIfN) | Apr 7    |
| [Final report](https://1drv.ms/b/s!AtiMpA7HPe0Qhr8Nb94bVQ_OKPZ22Q?e=kFTPXY)       | Apr 16   |
