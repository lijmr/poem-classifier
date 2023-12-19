I completed this project through a Natural Language Processing course on Udemy as part of my journey in learning more about machine learning and AI as a computer science student in college. The course is by Lazy Programmer Inc. and can be found in the link below:
https://www.udemy.com/course/data-science-natural-language-processing-in-python/

This project is a classifier that uses Markov Models to classify whether a poem is written by Edgar Allan Poe or Robert Frost. The steps taken to build the classifier are as follows:
  1. Clean and prepare the data by splitting each poem into lines, assigning them the proper class label, and removing any unnecesary punctuation
  2. Use sklearn to split the cleaned data into training and testing sets. Mutate the data such that each unique word is represented by a unique integer. Create a dictionary that stores this mapping.
  3. Use Markov Models to create the initial state distributions and the state transition matrices from the training set. This is how the classifier is trained.
  4. Build the poem classifier that uses the initial state distributions and state transition matrices to predict whether an input text is written by Edgar Allan Poe or Robert Frost.
  5. Test the classifier for accuracy.

This was a great first project in learning NLP! It really solidified my understanding of Markov Models and helped me get more experience using the sklearn.
