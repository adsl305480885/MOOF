<!--
 * @Author: Zhou Hao
 * @Date: 2024-04-07 18:04:04
 * @LastEditors: Zhou Hao
 * @LastEditTime: 2024-04-14 17:43:04
 * @Description: file content
 * @E-mail: 2294776770@qq.com
-->

# MOO: Multi-Objective Oversampling Models for Imbalance Learning of Fault Diagnosis

* **Abstract**：In the fault diagnosis and anomaly detection, datasets are often multi-classiﬁcation, imbalanced and noisy. Multi-imbalance and multi-noise are two challenges in machine learning. Usually, the quality of datasets can be improved through data augmentation such as oversampling. Multi-imbalance and multi-noise are two multi-objective optimization problems because we need to oversample the multiple minority classes. Existing works rarely use multi-objective optimization to solve these two problems. Two multi-objective oversampling optimization models (MOO) used to optimize the oversamplers is proposed in this work. In the ﬁrst of MOO, the optimal number of oversampling for each minority class is calculated to reduce the interference of imbalance. Then, the oversampler is used to generate new samples. In the second of MOO, the features of new samples for each minority class are optimized to reduce the interference of noise. We give a speciﬁc modelling process and prove the existence of Pareto optimal solutions for both multi-objective problems. Multi-objective evolutionary algorithms are used to compute the Pareto optimal solutions. MOO is adaptive and can optimize most existing oversamplers for various datasets. Experiments results based on various datasets with different noise rates and imbalance ratios illustrate that MOO achieves promising performance. The code and datasets are available at https://github.com/adsl305480885/MOOF.
* **Keyword**: Imbalanced classification, lable noise, optimization framework, convex optimization.

# Folders and Filers


* **apis.py**: Some functions for synthesizing artificial datasets.
* **main_MO.py**: Code entry. Call the oversampling algorithms and visualize.
* **OIRP_Multi_Over.pyc**：Encrypted core code, binary files. Decrypted after the paper is received.
* **requirements.txt**: Environment required for code.

# Requirements

### Minimal installation requirements (>=Python 3.7):

* Anaconda 3.
* Linux operating system or Windows operating system.
* Sklearn, numpy, pandas, imbalanced_learn.

### Installation requirements (Python 3):

* conda create -n yourname python=3.7
* conda activate yourname
* pip install -r requirements.txt

# Usage

* pip install -r requirements.txt.
* python ./main_MO.pyc
* python ./OIRP_Multi_Over.pyc
* python ./Runge_Kutta.pycc

##### Output:

* Optimal sampling ratio and new samples after denoising

# Doesn't work?

* Please contact Hao Zhou at zhouhaocqupt@163.com

# Future work
* The complete code, dataset, and experimental results will be made available upon acceptance of the paper.
