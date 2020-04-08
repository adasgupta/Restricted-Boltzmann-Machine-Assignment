# Restricted-Boltzmann-Machine-Assignment

Perform Topic Modelling on a set of documents and print the distribution of words in each topic.  

In this assignment, we shall create a function to perform Gibbs sampling k times within contrastive divergence often referred to as CD-k. Let's understand the structure of the notebook and the CD-k training process:

- Importing the dataset.
- Create a bag of words model.
- Note that the shape of a bag of words model will be (data_size, vocablury_size)
- Please note that the above shape might vary with the way you perform bag of words model but the index data_size will be the same.
- Training using CD-k
