# Enhanced-Product-Recommendation-System
The project involves a sophisticated recommendation system for eCommerce platforms using a hybrid approach that combined text and image categorization through deep learning. This integration delivered highly personalized product suggestions, enhancing user experience, improving accuracy, and addressing the challenge of vast product inventories.

## Dataset
The dataset used for this project can be found [here](https://www.kaggle.com/c/retail-products-classification).

## Purpose

The primary purpose of the system is to address common challenges in recommendation systems, such as data shortages and the cold start problem, while delivering more relevant and useful recommendations to users. By analyzing product images and textual descriptions, the system aims to understand user preferences and behavior to generate tailored recommendations.

## Architecture

The system architecture consists of two main components:
- ConvNet: Responsible for image classification and extraction of hierarchical features from product photos.
- LSTM: Handles text classification and captures complex sequential dependencies in product descriptions.

These components work together to analyze both image and text data and generate personalized recommendations for users.

## Training and Performance

Supervised learning techniques are used to train the neural network models, and performance is iteratively improved through feedback mechanisms such as backpropagation. By continuously refining the models based on user interactions and feedback, the system strives to enhance recommendation quality and relevance.

## Benefits

- Improved recommendation accuracy
- Better handling of data shortages and the cold start problem
- Comprehensive solution integrating content-based and collaborative filtering approaches
- More tailored and relevant recommendations for users

## Experiments and Assessments

The system has undergone extensive experiments and assessments to evaluate recommendation accuracy. Key findings include:
- ![image](https://github.com/Sivasangaran11/Enhanced-Product-Recommendation-System/assets/121967949/e4dec406-1708-4b55-9166-a8628526563e)

- The above figure displays a sample input dataframe representing a dataset of products with associated metadata, including unique identifiers for images, titles, descriptions, and categories.
- ![image](https://github.com/Sivasangaran11/Enhanced-Product-Recommendation-System/assets/121967949/416c60f0-a7bc-48e9-9e1e-ae5d5d22b4e5)

- The above figure illustrates product categories, providing insight into the classification of items within the dataset.
- ![image](https://github.com/Sivasangaran11/Enhanced-Product-Recommendation-System/assets/121967949/30370ad0-a457-49a8-9a7b-a810f58e7c45)

- Visualization of the t-distributed Stochastic Neighbor Embedding (t-SNE), showcasing the embedding space in a two-dimensional space.
- ![image](https://github.com/Sivasangaran11/Enhanced-Product-Recommendation-System/assets/121967949/09f75ae4-5aa6-49af-b982-23650fbe1505)

- Training and validation accuracy, illustrating the performance of the deep learning model combining LSTM with ConvNet.
- The recommendation system generates a similarity matrix based on product descriptions and images, facilitating the ranking of items for personalized recommendations.
- The combination of text and image classification models produced an approximate F1 score of 71.81 on the test data.
- ![image](https://github.com/Sivasangaran11/Enhanced-Product-Recommendation-System/assets/121967949/6072f0da-5e26-4412-b9da-2534d220aae6)

- The above figure presents the top 4 recommendations determined through collaborative filtering, showcasing the cosine similarity values among the top-rated products in relation to a specific individual product.

## Future Directions

Looking ahead, the system lays the groundwork for advanced recommender systems in online commerce. Future enhancements could include incorporating additional data sources, exploring new neural network architectures, and refining recommendation algorithms to further personalize the user experience.
