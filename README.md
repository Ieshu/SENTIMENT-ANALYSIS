# SENTIMENT-ANALYSIS USING TKINTER

Sentiment analysis is contextual mining of text which identifies and extracts subjective information in source material, and helping a business to understand the social sentiment of their brand, product or service while monitoring online conversations. 

The purpose of this analysis is to build a prediction model to predict whether a review on the restaurant is positive or negative.

To build a model to predict if review is positive or negative, following steps are performed.

1.Importing Dataset

2.Preprocessing Dataset

3.Vectorization

4.Training and Classification

5.Analysis Conclusion

Then we will create a GUI application using Tkinter and load the model on the web application . This will be the basic breakdown of pages

a. Create a login page with credentials so as to check authenticity of the user.

b. On successful login,make user navigate to next page containing 2 buttons 
                   > One button to check sentiment of single feedback i.e. one review
                   >  Second button to check the sentiment of a bulk feedback i.e loads of reviews will be passed at once 

c. On selecting single feedback bbutton,the user will navigate to another page where he/she will enter one review and check the prediction of the model. 

d. Whereas on selecting bulk button,the user will be navigated to another page where he/she will need to browse a file containing bunch of reviews from local and them upload it.
    Another button will be there to predict and save the output or predictions in a location ,which has to be specified bythe user itself.
