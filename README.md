# Adult-Census-Income
### Problem Statement
To determine whether a person makes over $50K a year or not.  Problem Solving approach- PCA on Adult Census data and then using K-means Clustering and Hierarchical/Agglomerative Clustering for clustering the classes accordingly


### Problem Solving approach-
PCA on Adult Census data and then using K-means Clustering and Hierarchical/Agglomerative Clustering for clustering the classes accordingly

### Description:
The Data set contains information about various attributes like education, gender, family status etc, of people from diverse backgrounds.

### Attribute Information:
age: continuous.
workclass: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov etc
Fnlwgt: Sample weight.
education: Bachelors, Some-college, 11th, HS-grad, Prof-school etc
education-num: continuous.
marital-status: Married-civ-spouse, Divorced, Never-married, Separated etc
occupation: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial etc
relationship: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.
race: White, Asian-Pac-Islander, Black etc
sex: Female, Male.
capital-gain: continuous.
capital-loss: continuous.
hours-per-week: continuous.
native-country: United-States, Cambodia, England, Puerto-Rico, Canada etc

### Different workclass that an individual may belong to
![image](https://user-images.githubusercontent.com/92087972/192086551-8e9a5bc3-0843-4b66-bd4d-5b73d0e4cb89.png)
### different education level
![image](https://user-images.githubusercontent.com/92087972/192086695-4205f2b7-71c2-49aa-80aa-e9892b8ebef6.png)
![image](https://user-images.githubusercontent.com/92087972/192086867-f9a836e4-49a9-42fa-bd79-8b5bbdfeeb3f.png)
![image](https://user-images.githubusercontent.com/92087972/192086886-9c43c623-5300-4d51-a6bb-2b489248c193.png)

### Variance using PCA
![image](https://user-images.githubusercontent.com/92087972/192086935-bce7a5a0-ad5b-47ed-84c0-7546ea43a407.png)

### USing KNN
![image](https://user-images.githubusercontent.com/92087972/192086973-18c1bad2-2e14-4102-8fcf-d83f4b4b210c.png)

![image](https://user-images.githubusercontent.com/92087972/192086994-e7bae38a-d929-47db-a27e-7c22f8db60fa.png)

### Dendrograms to find the number of classes in the dataset

![image](https://user-images.githubusercontent.com/92087972/192087028-03c5c0ed-4208-4967-9fba-f10a458ec98c.png)

![image](https://user-images.githubusercontent.com/92087972/192087053-b0911f16-9e27-42d3-9407-32f493a40292.png)

Altough there is no definitive answer since cluster analysis is essentially an exploratory approach; the interpretation of the resulting hierarchical structure is context-dependent and often several solutions are equally good from a theoretical point of view.

### Based on above information we can divide people into the following parts:-
- People who do private jobs:
spends around 38-42 hrs per week working.
- Capital gains are negligible.
suffers the most capital loss.
- People who work as a self-employed-inc:
spends around 50 hours per week working.
captial gains is highest for such person.
- People who are working as a self-employed-not-inc:
spends the least time, around 36 hours per week working.
capital gains for such group of people are negligible.
and so on.

### Machine Learning model evaluations
- In this project, we have attempted to cluster adult census dataset using K-means and agglomerative clustering and we also reduce the dimensionality of the dataset using PCA.
- We came up with 6 clusters using K-means and 4 classes using agglomerative clustering.
- Although selection of the clusters can be revised using Silhoutte score but for a general introductory part it is okay to visualize the plot (either elbow graph or dendrograms) and come up with a particular clusters size.


