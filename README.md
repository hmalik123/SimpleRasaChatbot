Simple Rasabot that provides cybersecurity mitigation advice

To run you must have: 

Rasa version – 3.0.0 to 3.2.2 
Rasa SDK version -  3.2.0 
Python Version – 3.8.13 

// Pre-requirements //

- difflib : run the following command to use difflib(python library) in your anaconda virtual environment : 

pip install cdifflib 

- pandas: run the following command to use pandas(python library) in your anaconda virtual environment :

pip install pandas

|Train Chatbot|

Before the chatbot can be launched the data much be trained using the command below: 

rasa train

|Launch Chatbot| 

In an anaconda terminal window launch the following command : 

rasa run actions 

In other anaconda terminal window launch the following command : 

rasa shell 
