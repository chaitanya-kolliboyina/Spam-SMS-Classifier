# SMS Spam Classifier using Neural Networks(Dense, LSTM,BI- LSTM)
Working with various neural network models on same data and finding which model performs better 
## Abstract
Short message service, popularly known as SMS is a way of communication through text. It is used to  send messages int the form of person-person or an organisation to person. In present scenarios we are knowingly and unknowingly give our mobile number to many organistions. These organisations use our contact information to advertise their product or service even though it is not necessary for us in the form of text message (or) SMS. 

<p>&nbsp;</p>

Such type of SMS are considered as spam. When these spam messages  number is in control, we can delete manually but now-a-days this number is huge and cause disturbance to us. This is where this project comes into picture. The main idea is, if we make a system which classifies the SMS into SPAM and HAM(not spam) by learning from the thousands of examples which are already classified  then this task of classification woukld become easier and helps the user to stay organised . 

<p>&nbsp;</p>

The main aim of this project is to design a classifier with help of various neural network models viz. Dense, LSTM, Bi-LSTM and based on the accuracy the best model will be decided to use as a " SMS spam classifier "
<p>&nbsp;</p>

### Data set link 
https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection

Total data set size  = 5572
<p>&nbsp;</p>

* spam messages =  747

* Ham messages  =  4825
<p>&nbsp;</p>

* Data Samples used  = 1494
     * Ham messages   =  747
     * Spam messages  =  747

* Training data   =  896
* validation data = 478
* Testing data    =  120

#### Different models accuracy on test data :
<p>&nbsp;</p>

* Dense model = 94.16%
* LSTM model  = 92.43%
* Bi-LSTM model = 94.38%

<p>&nbsp;</p>

#### From these accuracies, BI-LSTM model works more accurate than Dense, LSTM
