# NLP

###### Thesis: Can I read in a text file or some text and then provide information about the text i.e Word, count, words used, comparison against most frequently used words. etc. Maybe then suggest type of text, and then with some significance level determine if a work was written by the same author. etc

###### Natural Language Processing: 
This file is my first attempt at lerning NLP, I started off with small tasks i.e. 
- Reading in some text file in different formats i.e (txt, docx, pdf etc)
- Determining some insights i.e Word, count, words used, comparison against most frequently used words. etc.

###### Insight Generation From Customer Feedback:
I reviewed a fashion website's customer responses, 23 million total. Using spacy, NLTK and a few other libraries and models. I classified it by sentiment and complexity. Generating more datasets that can be used for further analysis. 
![Readability-Ease of Reading](https://user-images.githubusercontent.com/94771416/212569888-b1007218-613a-4034-a676-707115caabd6.png)

![Subjectivity - Opinion Skew](https://user-images.githubusercontent.com/94771416/212570036-b3736bb0-dcbf-4ba5-b7aa-fd2c38acbca0.png)



Lessons:
1. There was correlation between age and sentiment of customer (So apparently Age is not a determinant of Customer Sentiment.)
2. Complicated models can be used to evaluate text, but context is also important. The model indicated the vast majority of text was easily readable by most people. An insight here is that humans use different styles of communication in different settings. 


###### Document Simialrity Evaluation: 
Using streamlit (A python package for deploying ML projects) I created a function that takes in two files, scores them based on similarity and returns a file containing words that are missing when compared with a target document. [Link](https://github.com/Daa7314/cv_Eval)

