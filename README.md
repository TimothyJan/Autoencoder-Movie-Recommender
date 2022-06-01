# Autoencoder-Movie-Recommender
We apply autoencoders to the task of making movie recommendations.

<ol>
<li>We began with the Keras example <a href="https://keras.io/examples/structured_data/collaborative_filtering_movielens/">Collaborative Filtering for Movie Recommendations</a>. This example demonstrates <a href="https://en.wikipedia.org/wiki/Collaborative_filtering">Collaborative filtering</a> using the <a href="https://www.kaggle.com/c/movielens-100k">Movielens dataset</a> to recommend movies to users.</li>
<li>We construct a feature vector for Tim, who chooses and rates several movies, to generate 10 movie recommendations using the recommender model from the Keras example.</li>
<li>To improve our results, we modify the recommender model from the Keras example by replacing the dot product with two hidden <code>Dense</code> layers in our recommender model.</li>
<li>We compare the quality of the recommendations from the Keras example and our new model.</li>
<li>We improve our recommendations further by applying a <a href="https://keras.io/examples/generative/vae/">Variational Autoencoder</a> to add an additional sampling layer to the network.</li>  
</ol>
