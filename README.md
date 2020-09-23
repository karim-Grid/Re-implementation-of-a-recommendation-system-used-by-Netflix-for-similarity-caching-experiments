# Introduction
In this internship we have explored  a state of the art method for recommendation systems on Netflix named RecVAE,  then we have preprocessed the MovieLens20M, Netflix and Million Songs datasets  to set up our experimentations on this preprocessed datasets. The final goal from our  experimentations is to retrieve the users embeddings of the three datasets. A user embedding is a 200 dimensional vector that describe the content that the RecVAE  system will recommend to each user  in the dataset. Then after retrieving the users embeddings,  we have analyzed their distribution type  in a 200 dimensional space to moved on finally to build a timestamped trace for users-embeddings for similarity caching experiments.
# Experiments:
- The notebook above intituled Generation of the users embeddings trace describe our reimplementation of the recommender system  RecVAE code by using Pytorch to generate the embeddings for the MovieLens20M, Netflix and Million Songs users.
- The notebook above intituled Distribution of the users embeddings in a 200 dimensional space show the approaches that we developped to analyse the embeddings distribution type. Each user embedding is of dimension 200 so we need to discover their distribution type in a 200 dimensional space.
# Requirements :
 - Original MovieLens20M, Netflix and Million Songs datasets 
 - Pytorch
 - Pandas
 - Numpy and Matplotlib
# References : 
- [1]  RecVAE: a New Variational Autoencoder for Top-N Recommendations with Im-plicit Feedback 24 Dec 2019 , Ilya Shenbin , Anton Alekseev , Elena Tutubalina ,Valentin Malykh , Sergey I. Nikolenko.
- [2]  Variational   Autoencoders   for   Collaborative   Filtering   Dawen   Liang   RahulG.  KrishnanNetflix  Los  Gatos,  CA  dliang@netflix.com  MIT  Cambridge,  MArahulgk@mit.edu  Matthew  D.  Hoffman  Tony  Jebara  Google  AI  San  Francisco,CA mhoffman@google.com Netflix Los Gatos, CA tjebara@netflix.com
- [3]  Distributions of Angles in Random Packing on Sphere. Tony Cai, Jianqing Fanand Tiefeng Jiang.

