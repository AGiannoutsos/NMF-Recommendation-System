# NMF-Recommendation-System
A Non Negative Matrix Factorization Recommendation System that suggests content for a social network application


# About the project
We will use databases derived from user posts on a social networking platform [LinkedDit](https://github.com/AGiannoutsos/LinkedDIT/) for this application.
Using the NMF algorithm, we will extract features from this data.
Then, using an algorithm of near neighborhoods, we'll see which posts correlate.
As a result, these postings are recommended for each user to consume the suggested content. 

1.   We extract features from the data posted by users

2.   We analyze, implement and test the NMF algorithm

3.   We compose it all together and together with the nearest neighbors algorithm we build a recommenstation system 

## Code and report
Code, comments and report exist in the notebook which you can open in Colab from here [![Click here to open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AGiannoutsos/NMF-Recommendation-System/blob/main/Non_Negative_Matrix_Factorization_for_Recommendation_System.ipynb)


## Non Negative Matrix Factorization
NMF is a method of reducing dimensions like PCA, but NMF keeps the components and characteristics of the arrays positive. The aim is to export easily interpretable components to media that by their nature can not display negative values ​​such as the pixels of an image, video, spectral data of audio, for understanding the meaning of text and more.

To the problem of normalized table factorization, we can add various destinations beyond the non-negativity of the components.
In this exercise we have the limitation of the Frobian norm minimization of base components and vectors. With the normalization we look to reduce the coefficients so that there is little variation and the model is more stable and in addition so that some feature does not over-adapt to the model and spoils the generalization error of the model. 

