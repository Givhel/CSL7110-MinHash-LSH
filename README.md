# CSL7110 Assignment 2  
## MinHashing and Locality Sensitive Hashing

This repository contains the implementation of MinHashing and Locality Sensitive Hashing (LSH) for detecting similarity between documents and users. The assignment was completed as part of the course **CSL7110 – Machine Learning with Big Data**.

## Author
Kunal Mishra  
Roll Number: M25CSA036  

## Topics Covered
- K-Grams generation (character and word based)
- Jaccard Similarity computation
- MinHash signature generation
- Similarity estimation using MinHash
- Locality Sensitive Hashing (LSH)
- Application of MinHash and LSH on MovieLens 100k dataset

## Dataset
MovieLens 100k dataset from GroupLens:
https://files.grouplens.org/datasets/movielens/ml-100k.zip

## Implementation
All algorithms are implemented in **Python using Jupyter Notebook**.

Key components include:
- Document similarity using K-Grams
- MinHash approximation of Jaccard similarity
- LSH banding technique for efficient similarity search
- Experiments with different hash sizes and thresholds

## Repository Structure
M25CSA036_CSL7110_Assignment.ipynb   # Main notebook
minhash/                              # Document dataset
ml-100k/                              # MovieLens dataset
README.md


## Tools Used
- Python
- Jupyter Notebook
- Hashing techniques
- Set similarity algorithms

## Conclusion
The experiments demonstrate that increasing the number of hash functions improves MinHash accuracy. LSH significantly reduces the number of comparisons while still detecting highly similar pairs when appropriate banding parameters are used.
