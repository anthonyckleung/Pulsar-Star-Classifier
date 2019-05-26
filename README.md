# Pulsar Star Classifier

---

Task: Explore the original work of Lyon *et al.* [1] using modern machine learning tools. 

### Prerequisites:
* Python 3
* numpy, scipy, seaborn, sklearn
* Keras with TensorFlow backend
* data source: [UCI ML repo](https://archive.ics.uci.edu/ml/datasets/HTRU2)

### Description
In the original paper on classifying pulsar stars by Lyon *et al.* [1], much of the discussion
emphasized on the importance of good input features for building a robust classifier. 
In that work, the group worked with features that maximize the separation between
candidate classes and found that a tree-based machine learning classifier,
the Gaussian Hellinger Very Fast Decision Tree, achieved a accuracy test score of close to 0.98.
In this exercise, modern machine learning tools such as sklearn and Keras are used 
to understand the features of the data set and build a classifier that can reproduce 
the accurarcy test score of Lyon *et al.* [1].

-----
### References

[1] R. J. Lyon, B. W. Stappers, S. Cooper, J. M. Brooke, J. D. Knowles, *Fifty Years of Pulsar 
Candidate Selection: From simple filters to a new principled real-time classification approach*, 
Monthly Notices of the Royal Astronomical Society 459 (1), 1104-1123, DOI: [10.1093/mnras/stw656](https://arxiv.org/abs/1603.05166)
