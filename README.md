# CA03
Spam eMail Detection using Naive Bayes Classification Algorithm

# Description
In this exercise we shall train the model with set of emails labelled as either from Spam
or Not Spam. There are 702 emails equally divided into spam and non spam category.
Next, we shall test the model on 260 emails. We shall ask model to predict the category
of this emails and compare the accuracy with correct classification that we already know.

## Instructions:
1. Download Data Zip file to local computer
2. Open ipynb file
3. Click "Open in Colab" button or click the Colab link
4. Unzip and Upload Data file to goolge drive under correct folder.
5. Run code by lines or select runtime in the menu bar - click run all in the dropdown list

## Usage
Basically, sklearn Naive Bayes provides three alternatives for model training:
• Gaussian: It is used in classification and it assumes that features follow a normaldistribution.

• Multinomial: It is used for discrete counts. For example, let’s say, we have a text classification problem. Here we can consider bernoulli trials which is one step
further and instead of “word occurring in the document”, we have “count how often word occurs in the document”, you can think of it as “number of times
outcome number x_i is observed over the n trials”.

• Bernoulli: The binomial model is useful if your feature vectors are binary (i.e.zeros and ones). One application would be text classification with ‘bag of words’
model where the 1s & 0s are “word occurs in the document” and “word does not occur in the document” respectively.

## Conclusion
The Naive Bayes considers the independence in features. For example it assumes the
occurrence of one word/ feature is independent of other. But in real life it may not be so (
occurrence of morning is high after Good).
