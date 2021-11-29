# IS417Myproject

Description:

Product reviews are increasingly becoming important with the evolution of e-commerce and online shopping. Consumers post a lot of positive and negative reviews on product pages. The product reviews can be analyzed to understand how the market and consumers react to a specific product. Using sentiment analysis, product reviews can be used to analyze opinions, emotions and attitude towards a product.

The Question:

To solve the business problem by analyzing the product categories that have lower reviews (inferior products) and the products that have higher reviews (superior products).

Dataset and process:

https://www.kaggle.com/saurav9786/amazon-product-reviews (Links to an external site.)

https://www.kaggle.com/datafiniti/consumer-reviews-of-amazon-products (Links to an external site.)

The dataset is based on amazon product reviews and consumer reviews for amazon products. The aim of this project is to analyze customer satisfaction while understanding the reasons for positive and negative reviews.

To implement this, I will first use tokenization for text preprocessing and filter the words using stopwords and use Scikit-Learn’s Count vectorizer to build a dictionary and convert it into feature vector. Multinomial Naïve Bayes Classifier can also be used to test the accuracy level based on the features. 
The assumption is that the text reviews for the products is sufficient to predict accuracy and to analyze the product sentiments.
