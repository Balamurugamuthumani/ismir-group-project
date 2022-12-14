# ismir-group-project

Ideas

1. To have the features in a .csv/pandas format
  a. Pandas profiling for better understanding of data, how the columns are linked, and how they are making a difference for a particular class
2. To reduce columns, perform PCA
  a. We'll use T-SNE (or) UMAP to accomplish the task
  b. Try reducing 200 features down to 2 cols or until 3 cols also. 
  c. Visualize them (include in PPT)

**Musical Inference**

1. Listen to samples in the dataset (in every class) and will have our assumption to which classes sound similar to the ears
2. Based on the listening experience, decide how many clusters we can form by merging some

Dataset Preparation for Training/Testing for ***supervised learning***
1. we have to change the labeling values according to our musical inference
2. train/test split

Dataset Preparation for Training/Testing for ***unsupervised learning***
1. Remove the label colummn (last column)
2. Train test split
(if we use k-means for unsupervised learning we will give k values or clustering value)

select the model and perform traing the model

Testing the model

for evaluation
1. we will use confusion matrix for showing the results (supervised learning)


extras
  1. Running a clustering algorithm with 200 features
  2. Plotting a heat map with all 200 features
  3. Exploring some more features to improve accuracy
  4. Explore and extend the same concepts to tabla datasets
