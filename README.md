# Spam-Detection-Project
Spam messages are becoming more prevalent across all electronic media due to increased internet and mobile phone usage. These messages have been a significant issue for mobile service communication services.
The simplicity of sending spam messages to numerous individuals has contributed to the growth of spam communications.
The number of SMS spam is increasing due to several factors. Since neither the SMS application (access layer) nor the telecom operator (service provider layer) has properly installed SMS spam filters, spam messages can be routed to a user's mobile phone unfiltered.
Also, SMS does not require the user to be connected to the internet, therefore spam can reach the user's mobile phone and is thus different from e-mail and other online communication services. Lastly, the ease of sending bulk SMS to several users at once is another factor.
Spam messages can distract a mobile phone user from reading critical messages by piling up their inbox and pushing them to the top of the inbox. Users may find it annoying to receive an SMS spam alert while hoping for other important messages. Because of this, sending spam messages can potentially reduce the effectiveness of SMS as a communication tool. Spam messages are often delivered to many users and are irrelevant or uninvited.
Spam detection has been developed to address SMS spam issues. Typically, binary classification is employed as a spam detection method. A spam detector classifies every message into two types: spam and ham(or good mail).
This classification helps in creating a user-friendly environment free of unwanted messages, thereby saving a lot of time and hassle.
Spam could be of various types; some major ones are unnecessary advertisements and different types of fraud. 
Our dataset contains 5 features and 5574 data entries .Different machine-learning models have been employed to classify messages into spam or ham(good mail). Among these models, multinomial naive Bayes and Random Forests have produced the best results, with an accuracy of 97.09 and 97.48, respectively. Lastly, to further improve the accuracy and efficacy of the whole model, we’ve also implemented stemming and vectorization.

Scores of our final models :
![image](https://user-images.githubusercontent.com/88649199/208297086-8d9cabe8-5b6a-47f2-b0a2-f03795b676b8.png)
