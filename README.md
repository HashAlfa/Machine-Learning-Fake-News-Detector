# Machine-Learning-Fake-News-Detector
Make a difference between real and fake news.

In this machine learning project, terms like tfidfvectorizer, PassiveAggressive Classifier, Confusion matrix used.

What is a TfidfVectorizer?
TF (Term Frequency): This is about counting how often a word appears in a document. If a word appears a lot in one document, it might be important for that document. It's like noticing which ingredient is used most in a recipe.

IDF (Inverse Document Frequency): This part is a bit trickier. It reduces the importance of a word if it appears in too many documents. It's like if you hear a song playing everywhere, it becomes less "special" in any one place. So, if a word is really common in all documents (like "the" or "is"), it's probably not that important for understanding what makes a specific document special.


What is a PassiveAggressiveClassifier?
A Passive Aggressive Classifier is an online learning algorithm that reacts passively when it predicts correctly and becomes aggressive when it makes a mistake. It updates itself to correct errors without converging like many other algorithms. Its goal is to make minimal changes to the weight vector while fixing mistakes in predictions.
