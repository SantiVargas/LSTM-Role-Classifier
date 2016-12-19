# LSTM-Role-Classifier
Role Classification using Deep LSTM and Bi-LSTM Networks

##### How to run?
```$ python run_model.py``` to run LSTM Model.  
_Change parameters of the model within the file_

#### Implementation Description
We can describe our ’LSTM Retrofitted Classifier’ algorithm
as below:
1. Categorize processes into five folds.

2. Preprocess dataset and create embeddings from glove
vectors, which are global vectors for word representation.

3. Process data and, create test and train matrices for the
model.

4. Create embedding matrix for initialization using pretrained
embeddings and initialize with all zeroes.

5. Create a word vector and store embedding vector in it.

6. Retrofit embeddings against lexicons (PPDB, Framenet,
Wordnet-synonyms, Wordnet-synonyms+)

7. Define LSTM model by adding Retrofitted Embeddings
and LSTM layers to it.

8. Train LSTM model, with history as a parameter for its
typical LSTM functionality.

9. Run LSTM Retrofitted Model on test data in five folds
created at the beginning of the algorithm.

##### Project Description
* Class: CSE 537 - Aritificial Intelligence
* Professor: Niranjan Balasubramanian
* Team Members: Shilpi Bhattacharyya, Santiago Vargas, and Russell Walker
* Semester: Fall 2016
* Assignment: Final Project
