# Distance Metric Recommendation for $k$-Means Clustering: A Meta-Learning Approach

**This work was accepted for paper presentation at the 2022 IEEE Region 10 Conference ([TENCON 2022](https://www.tencon2022.org/)):**

- The pre-print version of our paper can be accessed via this [link](https://github.com/memgonzales/meta-learning-clustering/blob/master/Distance%20Metric%20Recommendation%20for%20k-Means%20Clustering%20A%20Meta-Learning%20Approach.pdf).
  - Our TENCON 2022 presentation slides can be accessed via this [link](https://docs.google.com/presentation/d/1PsrlXavi4ubo-PVuop32Cysbz_C0CvcMTTBMo9YuTuc/edit?usp=sharing).
- Our [dataset of datasets](https://github.com/memgonzales/meta-learning-clustering/tree/master/dataset_of_datasets) is publicly released for future researchers. 

## Description

**ABSTRACT:** The choice of distance metric impacts the clustering quality of centroid-based algorithms, such as k-means. Theoretical attempts to select the optimal metric entail deep domain knowledge, while experimental approaches are resourceintensive. This paper presents a meta-learning approach to automatically recommend a distance metric for k-means clustering that optimizes the Davies-Bouldin score. Three distance measures were considered: Chebyshev, Euclidean, and Manhattan. General, statistical, information-theoretic, structural, and complexity meta-features were extracted, and random forest was used to construct the meta-learning model; borderline SMOTE was applied to address class imbalance. The model registered an accuracy of 70.59%. Employing Shapley additive explanations, it was found that the mean of the sparsity of the attributes has the highest meta-feature importance. Feeding only the top 25 most important meta-features increased the accuracy to 71.57%. The main contribution of this paper is twofold: the construction of a meta-learning model for distance metric recommendation and a fine-grained analysis of the importance and effects of the meta-features on the model’s output.

**INDEX TERMS:** meta-learning, meta-features, $k$-means, clustering, distance metric, random forest

<img src="https://github.com/memgonzales/meta-learning-clustering/blob/master/figures/fig.PNG?raw=True" alt="App Screenshots" width = 750> 


## Authors

- <b>Mark Edward M. Gonzales</b> <br/>
  mark_gonzales@dlsu.edu.ph <br/>
  
- <b>Lorene C. Uy</b> <br/>
  lorene_c_uy@dlsu.edu.ph <br/>

- <b>Jacob Adrianne L. Sy</b> <br/>
  jacob_adrianne_l_sy@dlsu.edu.ph <br/>

- <b>Dr. Macario O. Cordel, II</b><br/>
  macario.cordel@dlsu.edu.ph
  
This is the major course output in a machine learning class for master's students under Dr. Macario O. Cordel, II of the Department of Computer Technology, De La Salle University. The task is to create a ten-week investigatory project that applies machine learning to a particular research area or offers a substantial theoretical or algorithmic contribution to existing machine learning techniques.
