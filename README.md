In this project,I will be using Bag of words model under Natural Language processing 
Bag of Words Model:
In English language there are 20,000 to 30,000 words. 3000 words cover 95% of the common words used.Each word has been assigned a space in a vector which remains the same. Any word or character that doesnt come under the 20,000 words are deonted with the last index.As per the frequency of words in a given paragraph, the postion is incremented by 1.
The dataset contains a series of paragraphs which is either real news or fake news.
The steps are :
1.Importing the libraries
2.Importing the dataset
3.Cleaning the text
To clean the text, I will import libraries like re to simplify the review. Using the re library's sub function ,we replace all characters except alphabets(A-Z,a-z) by spaces. I will also be using the nltk library and download the stopwords from the nltk library, we will also use Porter Stemmer function to apply stemming. In stemming,we take only the root of the word which includes enough about its nature.We will also remove the stopwords

4.Creating the bag of words model:
We will use vectorization to take all the reviews and put them nto different columns,we will also add a parameer called max_features to take only the words that appear maximum number of times

5.Splitting the dataset into training set and test set
6.Training the Naive Bayes model on the training set
7.Predicting the test set results
8.Making the confusion matrix
