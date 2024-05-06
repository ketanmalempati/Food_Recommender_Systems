# Receipe Rating Prediction

## Introduction
The abundance of food choices available today can make it difficult for consumers to decide what to eat. To address this problem, food recommendation systems have been developed to help users discover new food items that match their preferences. A food recommendation system predicts a user's preference for a food item based on their past interactions with similar items.

This project focuses on building a food recommendation system that predicts ratings based on user interactions with food items. The dataset used in this project contains user reviews and ratings for different food items, recipe steps, and description and date of interaction. Various models and techniques are being explored, including GloVe, TF-IDF, BM25, neural nets, and Faiss, to calculate similarities between different food items and generate predictions for new food items.

The goal of this project is to build a robust recommendation system that can help users discover new food items they are likely to enjoy, while also providing valuable insights into user preferences and behavior. Such a system can benefit food companies and retailers by better understanding their customers' preferences and providing personalized recommendations. Overall, this project has the potential to enhance the user experience in the food industry and provide more satisfying and personalized recommendations for users.

## Alogorithms
- Glove - The GloVe is a technique for producing vector representations of words using unsupervised learning. Training is done using corpus-based global word-word co-occurrence statistics, and the resulting representations show off some of the word vector space’s fascinating linear substructures.

![image](https://user-images.githubusercontent.com/57043103/235417204-35b34a01-4ce6-49e3-9aed-fe326d1cd35c.png)

- TF-IDF - Term Frequency – Inverse Document Frequency (TF-IDF) is a popular statistical technique utilized in natural language processing and information retrieval to assess a term’s significance in a document compared to a group of documents, known as a corpus. The technique employs a text vectorization process to transform words in a text document into numerical values that denote their importance.

![image](https://user-images.githubusercontent.com/57043103/235396207-42190773-2942-4b44-bf8b-e84368af751e.png)

- BM25 - BM25 is a simple Python package and can be used to index the data, tweets in our case, based on the search query. It works on the concept of TF-IDF. 

![image](https://user-images.githubusercontent.com/57043103/235396293-9fd78407-3a84-49be-95d3-e1ae4dc8d23a.png)

- Faiss - Facebook AI similarity search (FAISS) is an algorithm developed by Facebook for fast and efficient similarity search, especially for large data.it is built with nearest-neighbor search implementations for billion-scale data sets that are some 8.5x faster than the previously reported state-of-the-art, along with the fastest k-selection algorithm on the GPU.

![image](https://user-images.githubusercontent.com/57043103/235396266-080b1fe0-3b65-4fa0-a1e6-c68628bad3f8.png)

- Neural Networks - Neural networks are a type of machine learning model inspired by the structure and function of the human brain. They consist of layers of interconnected "neurons" that process input data and produce output predictions or classifications.

![image](https://user-images.githubusercontent.com/57043103/235396242-cf5cc326-9794-4f75-aac6-2a78f5844e32.png)

- Architectural Diagram

![image](https://user-images.githubusercontent.com/57043103/235417308-1a1dfc5b-17ab-44cb-893c-49a7b6fb4be7.png)
  
## Dataset link
https://www.kaggle.com/code/ngohoantamhuy/food-recommendation-systems
