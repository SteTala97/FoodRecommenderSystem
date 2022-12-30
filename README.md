# FoodRecommenderSystem
A **recommender system** for **multimodal data** about food recipes. This is a project for the **Artificial Intelligence** course at **Università degli Studi di Milano Bicocca** (a.a. 2021/2022), and the work was done by me and my classmate **Kevin Manella**.

The dataset we used, "*Food Ingredients and Recipes Dataset with Images*", is available at [Kaggle](https://www.kaggle.com/) website [here](https://www.kaggle.com/datasets/pes12017000148/food-ingredients-and-recipe-dataset-with-images).

For the task of *multimodal embedding* we used the following resources:
  - **Image embedding**: [VGG16](https://arxiv.org/pdf/1409.1556.pdf) implemented with [Tensorflow and Keras](https://www.tensorflow.org/api_docs/python/tf/keras/applications/vgg16/VGG16);
  - **Paragraph embedding**: [Doc2Vec](https://radimrehurek.com/gensim/models/doc2vec.html) implemented with the [Gensim library](https://radimrehurek.com/gensim/index.html).
<br>

A graph that shows the multimodal embedding approach we implemented:
![](https://github.com/SteTala97/FoodRecommenderSystem/blob/main/demo_imgs/multimodal_embedding.png)

A graph that shows the approach implemented to get similar recipes given the embeddings:
![](https://github.com/SteTala97/FoodRecommenderSystem/blob/main/demo_imgs/cosine_distance.png)

An example of promising results on data already present in the original dataset:
![](https://github.com/SteTala97/FoodRecommenderSystem/blob/main/demo_imgs/results_existing_data.jpg)

An example of promising results on new data found on the web (Google images):
![](https://github.com/SteTala97/FoodRecommenderSystem/blob/main/demo_imgs/results_new_data.jpg)
