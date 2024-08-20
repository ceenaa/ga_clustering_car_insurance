# Detecting Car Insurance Fraud Using Improved Clustering with Genetic Algorithm

# Overview
This project presents a novel approach for detecting car insurance fraud by employing an optimized genetic algorithm for data clustering. Traditional clustering methods, such as K-means, often struggle with the complexities inherent in determining the optimal number of clusters and data allocation. Our approach leverages the power of genetic algorithms, a method inspired by natural evolution, to improve the accuracy and efficiency of clustering, particularly in the challenging field of insurance fraud detection.

# Key Features
* Optimized Clustering: The project uses a genetic algorithm to determine the best clustering structure, significantly improving the accuracy of fraud detection compared to traditional methods.
* Enhanced Accuracy: Our method has shown improvements in F1 score and overall accuracy across multiple insurance datasets.
* Scalable Solution: The approach is designed to handle large datasets and complex clustering problems, making it suitable for real-world insurance fraud detection scenarios.

# Methodology
* Genetic Algorithm for Clustering
* Chromosome Formation: Each chromosome represents a potential solution with the number of clusters and their corresponding centers encoded. The chromosome length is determined by multiplying the number of clusters by the number of features in the dataset.
* Crossover, Mutation, and Survival: New and diverse methods are applied for the crossover, mutation, and survival processes to enhance the clustering performance.
* Evaluation Criterion: Similar to the K-means algorithm, an evaluation criterion is chosen to optimize the clustering performance. The genetic algorithm allows for the exploration of a broader solution space, resulting in more accurate clustering outcomes.

# Performance Evaluation
The method was tested on three insurance datasets specifically selected for fraud detection. The results were promising:

* Dataset 1: **27%** improvement in **F1 score** and a **6%** increase in **accuracy**.
* Dataset 2: **1%** improvement in **F1 score** and a **2%** increase in **accuracy**.
* Dataset 3: **2%** improvement in **F1 score** and a **9%** increase in **accuracy**.
These results demonstrate the effectiveness of the genetic algorithm in outperforming traditional clustering methods like K-means.

# Results
### Visualization
![image](https://github.com/user-attachments/assets/3d3d5042-e97f-4c42-816c-716433e5a6fe)

### Convergence
![image](https://github.com/user-attachments/assets/846c50ce-b4ba-4b38-821e-8348aeda57d9)

# Contributer
<a href="https://github.com/ceenaa/ga_clustering_car_insurance/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ceenaa/ga_clustering_car_insurance" />
</a>

Made with [contrib.rocks](https://contrib.rocks).
