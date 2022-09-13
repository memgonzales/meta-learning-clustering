# Automatic Recommendation of Distance Metric for $k$-Means Clustering: A Meta-Learning Approach

**This work was accepted for paper presentation in TENCON2022.**

This is the major course output in a machine learning class for master's students. The task is to create an investigatory project that applies machine learning to a particular research area or offers a substantial theoretical or algorithmic contribution to existing machine learning techniques. <br>

**ABSTRACT:** The choice of distance metric impacts the clustering quality of centroid-based algorithms, such as $k$-means. Theoretical attempts to select the optimal metric entail deep domain knowledge while experimental approaches are resource-intensive. This paper seeks to address this problem by employing a meta-learning approach to automatically recommend a distance metric for $k$-means clustering that optimizes the Davies-Bouldin score. Three distance measures were considered: Chebyshev, Euclidean, and Manhattan. General, statistical, information-theoretic, structural, and complexity meta-features were extracted, and random forest was used to construct the meta-learning model; borderline SMOTE was applied to address class imbalance. The model registered an accuracy of 70.59%. Employing Shapley additive explanations, it was found that the mean of the sparsity of the attributes has the highest meta-feature importance. Feeding only the top 25 most important meta-features increased the accuracy to 71.57%. The main contribution of this paper is twofold: the construction of a meta-learning model for distance metric recommendation and a fine-grained analysis of the importance and effects of the meta-features on the model’s output.

**INDEX TERMS:** Meta-learning, meta-features, $k$-means, clustering, distance metric, random forest

**RESEARCH PAPER:** [`Final Manuscript.pdf`](https://github.com/memgonzales/meta-learning-clustering/blob/master/Final%20Manuscript.pdf)

**REPOSITORY DIRECTORY:** [`0. Master Notebook.ipynb`](https://github.com/memgonzales/meta-learning-clustering/blob/master/0.%20Master%20Notebook.ipynb) <br>

<img src="https://github.com/memgonzales/meta-learning-clustering/blob/master/figures/block_diagram.png?raw=True" alt="Methodology" width = 250> <img src="https://github.com/memgonzales/meta-learning-clustering/blob/master/figures/shap_chebyshev.png" alt="Most Important Features (Chebyshev) - HAP" width = 500> 

## Citing this Work

## Authors
- <b>Mark Edward M. Gonzales</b> <br/>
  mark_gonzales@dlsu.edu.ph <br/>
  
- <b>Lorene C. Uy</b> <br/>
  lorene_c_uy@dlsu.edu.ph <br/>

- <b>Jacob Adrianne L. Sy</b> <br/>
  jacob_adrianne_l_sy@dlsu.edu.ph <br/>

- <b>Dr. Macario O. Cordel, II</b><br/>
  macario.cordel@dlsu.edu.ph
