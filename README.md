
# What is Hierarchical Clustering?

Hierarchical clustering is where you build a cluster tree (a dendrogram) to represent data, where each group (or “node”) links to two or more successor groups. The groups are nested and organized as a tree, which ideally ends up as a meaningful classification scheme.

Each node in the cluster tree contains a group of similar data; Nodes group on the graph next to other, similar nodes. Clusters at one level join with clusters in the next level up, using a degree of similarity; The process carries on until all nodes are in the tree, which gives a visual snapshot of the data contained in the whole set. The total number of clusters is not predetermined before you start the tree creation.


# What is a Dendrogram?
![Dengoram](https://www.statisticshowto.datasciencecentral.com/wp-content/uploads/2016/11/clustergram.png)

A dendrogram is a type of tree diagram showing hierarchical clustering — relationships between similar sets of data. They are frequently used in biology to show clustering between genes or samples, but they can represent any type of grouped data.


We use [Credit Card](https://www.kaggle.com/arjunbhasin2013/ccdata) Dataset

## Resources

[Statisticshowto.datasciencecentral](https://www.statisticshowto.datasciencecentral.com/hierarchical-clustering/)
