# Bhagvad-gita-verse-recommender
It is Word2vec based verse recommender.


test.csv is a dataset that contains Bhagvad Gita verse number followed by the verse.

To run this program download all the files from this repository and you will have to download Word2Vec model

<a href="https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit?resourcekey=0-wjGZdNAUop6WykTtMip30g"> Link to download Word2Vec model </a><br>
Put this Word2Vec model in same directory as other model and our program is ready to be executed.<br>

## Demo

Taking input from user:<br>
```python
user_input = input("Enter the text = ")
```

Preprocessing and vectorising the user input:
```python
user_input = preprocess_and_vectorize(user_input)
```

Let's say user entered "What is meaning of life?"<br>
Then our program will give the following output:<br><br>
![rec res](https://user-images.githubusercontent.com/70089229/210482465-c1e81729-9ccb-4499-8af5-313df6b28941.png)
