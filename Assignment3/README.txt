Running instructions for assignment3

1. Run the clustering algorithms on the datasets and describe what you see. 
https://github.com/cicidong/CS-7641-Assignment3/blob/main/Assignment3/src/1_Clustering_Credit_card.ipynb
https://github.com/cicidong/CS-7641-Assignment3/blob/main/Assignment3/src/2_Clustering_Flight_Delay.ipynb

2. Apply the dimensionality reduction algorithms to the two datasets and describe what you see. 
https://github.com/cicidong/CS-7641-Assignment3/blob/main/Assignment3/src/3-Dimension_reduction_Credit_card.ipynb
https://github.com/cicidong/CS-7641-Assignment3/blob/main/Assignment3/src/4-Dimension_reduction_Flight_Delay.ipynb

3. Reproduce your clustering experiments, but on the data after you've run dimensionality reduction on it. Yes, that’s 16 combinations of datasets, dimensionality reduction, and clustering method. You should look at all of them, but focus on the more interesting findings in your report. 
https://github.com/cicidong/CS-7641-Assignment3/blob/main/Assignment3/src/3-Dimension_reduction_Credit_card.ipynb
https://github.com/cicidong/CS-7641-Assignment3/blob/main/Assignment3/src/4-Dimension_reduction_Flight_Delay.ipynb

4. Apply the dimensionality reduction algorithms to one of your datasets from assignment #1 (if you've reused the datasets from assignment #1 to do experiments 1-3 above then you've already done this) and rerun your neural network learner on the newly projected data.
https://github.com/cicidong/CS-7641-Assignment3/blob/main/Assignment3/src/5-NN_ICA.ipynb
https://github.com/cicidong/CS-7641-Assignment3/blob/main/Assignment3/src/5-NN_LDA.ipynb
https://github.com/cicidong/CS-7641-Assignment3/blob/main/Assignment3/src/5-NN_PCA.ipynb
https://github.com/cicidong/CS-7641-Assignment3/blob/main/Assignment3/src/5-NN_RP.ipynb
reference for prior NN results with original data: 
https://github.com/cicidong/CS-7641-Assignment3/blob/main/Assignment3/src/Modeling-NN-orginal_data.ipynb

5. Apply the clustering algorithms to the same dataset to which you just applied the dimensionality reduction algorithms (you've probably already done this), treating the clusters as if they were new features. In other words, treat the clustering algorithms as if they were dimensionality reduction algorithms. Again, rerun your neural network learner on the newly projected data.
https://github.com/cicidong/CS-7641-Assignment3/blob/main/Assignment3/src/6_NN_Clustering_Credit_card.ipynb
