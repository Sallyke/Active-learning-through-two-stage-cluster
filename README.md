# ALTA
"Active learning through two-stage cluster" be published in Fuzz-IEEE 2018

Abstract—Clustering-based active learning approaches take advantage of the structure of the data to select representative instances. However, some algorithms are either inefficient or only applicable to some data. In this paper, we propose an effective and adaptive algorithm that will be called active learning through two-stage clustering (ALTA). The first stage is data preprocessing using the two round-clustering algorithm to obtain √n small blocks, where n is the number of instances. For each block, the closest instance of the center is selected as the representative. The second stage is the active learning of representative instances through density clustering. This stage consists of a number of iterations of density clustering, labeling and classification. In general, data preprocessing reduces the size of the data and the complexity of the algorithm. The combination of distance vector clustering and density clustering makes the algorithm more adaptive. Experiments are performed in comparison against the state-of-the-art active learning algorithms on nine datasets.
Results demonstrate that the new algorithm has higher classification accuracy with the same number of labeled data.

Index Terms—Active learning; data preprocessing; two-roundclustering; density clustering.

@inproceedings{wang2018active,
  title={Active learning through two-stage clustering},
  author={Wang, Min and Fu, Ke and Min, Fan},
  booktitle={2018 IEEE International Conference on Fuzzy Systems (FUZZ-IEEE)},
  pages={1--7},
  year={2018},
  organization={IEEE}
}

JAVA
