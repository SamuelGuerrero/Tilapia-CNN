
# **VGG-16 vs LeNet-5**

## Description

The experimentation aims to assess the performance of two widely recognized architectures: [LeNet-5](https://ieeexplore.ieee.org/document/726791), a pioneering model in the field, and [VGG-16](https://arxiv.org/abs/1409.1556), renowned for its architectural depth. The evaluation will involve five models *M<sub>1A</sub>*, *M<sub>2A</sub>*,..., *M<sub>5A</sub>* each employing the LeNet-5 architecture, and an additional set of five models *M<sub>1B</sub>*, *M<sub>1B</sub>*,..., *M<sub>5B</sub>* corresponding to VGG-16. This dual approach enables us to comprehensively gauge the generalization capabilities of both architectures using diverse metrics.

![](https://i.postimg.cc/fyXk5fZ5/Le-Net-5-Architecture.png)
![](https://i.postimg.cc/c18Ks0YY/VGG-16-Architecture.png)

These models will undergo training using images focused on the genital papillae of Nile tilapia (Oreochromis niloticus), with the primary objective being the prediction of their sex through binary classification. This specialized focus on the tilapia's genital papillae ensures that the models are tailored to address the intricacies of sex prediction in this specific biological context. The utilization of distinct architectures and metrics will provide a robust foundation for comparative analysis, offering valuable insights into their respective strengths and weaknesses in the context of binary sex classification.

![](https://www.bigfish.mx/__export/1494447198016/sites/debate/img/2017/05/10/tilapia.jpg_1902800913.jpg)
![](https://i.postimg.cc/BZLw3W8P/Dataset.png)


This meticulous analysis reveals how the VGG-16 architecture outperforms LeNet-5 on the specific task of binary sex classification in tilapia, highlighting the importance of choosing the right architecture for specific biological problems. The results present a detailed view of performance differences, enabling informed decision making in future binary classification projects in similar biological contexts.

![](https://i.postimg.cc/W46nY0pN/Graph-VGG-16-vs-Le-Net-5.png)
![](https://i.postimg.cc/SKpdGgh1/Results-VGG-Le-Net.png)
