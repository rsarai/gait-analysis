# gait-analysis


## Graduation Project
This was a project developed during the year of 2018 as a graduation thesis oriented by Prof. Fernando Buarque and co-oriented by M.Sc. Rafael Caldas with the title: Analysis and selection of cinematic aspects of the human gait to classify subjects by age group. This project was made in portuguese and the full text is [here](https://drive.google.com/file/d/1pqHtTaTi5BP9sa2CXS9OoK8W09H4C2V1/view?usp=sharing).

This repository contains all the experiments and the data used on the process.

The experiments were carried taking into consideration the age groups and the number of available gait characteristics. The database consists of healthy individuals, both genres and of different ages, totaling 180 samples divided into 6 groups according to the age group. Including individuals under 10 years of age; 10-19 years old; 20-29 years old; 30-39 years of age; 40-49 years of age and individuals above 50 years of age, but not greater than 75 years of age. As input from the algorithms, we can use some variation of the five symmetry variables (Rst, Rsw, RssR, RssL and Rs) and two kinematic variables (ACT and Cadence) of the 180 subjects randomly selected. Initially, all six age groups were compared, along with the seven input parameters collected by the IMUs. Then, experiments were performed with the groups of greater and lesser similarity, that is, groups A and C and groups E and F. In relation to the hybrid approaches, the algorithms admit any combination of input resources, thus, experiments were performed varying of two to seven input parameters for the two groups, in order to validate the previous idea that some characteristics are more important than others in the classification process. Scenario coverage resulted in 704 experiments.


### Abstract
The gait analysis based on information collected by motion sensors has become common in recent years. Several techniques of machine learning are applied to simplify gait interpretation and to develop decision support models. This happens because of the widespread availability of sensors to measure movements on smartphones, fitness trackers and smart-watches. In order to support the evaluation of gait dysfunctions, two hybrid techniques were developed based on self-organizing maps (SOM) and two clustering algorithm, which in the scope of this work were K-means and Fuzzy C-means (FCM). The produced algorithms were compared with the base versions to assess the quality of the classification. The experiments used a database collected by inertial sensors of 180 individuals divided into six age groups. The results showed that the SOM + FCM method has a high precision (88 %) identifying with groups with significantly similar gait patterns. The results also showed the relevance of Cadence in the classification by age group.


**Keywords**: Gait analysis, Self organizing Maps, Neural Networks, Clustering, K-Means,
Fuzzy C-Means, Feature Relevance.
