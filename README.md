# Rule-Based-Chatbot : Syeraa
An effort to develop a chatbot using NLP and Python based on ML rules with an idea to query any website provided with the link as an input.

Getting Started

Step 1: Import required libraries   
________________________________________

The pre-requisite is to import the libraries which includes the following:
-	newspaper package for extracting and parsing articles
-	random function for generating greeting responses for bot
-	string to perform various string processing operation
-	nltk to deal with human language data and interact with user
-	numpy to work with numerical computations

Figure 3: Import Libraries


Step 2: Data reading
________________________________________

Data is required to teach the chatbot, where we will have a files & document called corpus which is understandable by chatbot. This step is basically pre-processing and handling the data where it will understand the words.
 
Figure 4: Data Reading




Step 3: Programming a greet response
________________________________________

Here we design greet response where it will respond to the texts like a human conversation. These greets are changeable as per client requirement. To a single greet, bot can give different outputs.

 
Figure 5: Greet response

Step 4: Generate responses
________________________________________
To give out certain responses, TF-IDF concept will be used, the feature extraction which is based on textual inputs. Cosine similarity is used to check & teach the chatbot about how to find certain behaviour inputs and understand the differences/ similarities and map the input to the documents. Also, if the chatbot does not understand anything it will respond with “Please enter a valid Input”.

Figure 6: Generate responses

Step 5: Programming Start and End points in conversation
At starting, after running the chatbot instead of greeting it will say “I am Syeraa. I will guide you for now”. If you want to quit you can simply write “Bye” to which bot will greet you with “see you later” or other from the exit list.

Figure 7: Start and End points in conversation



RESULT
________________________________________
The end result of the interaction with Syeraa is shown below:

Figure 8: Start Point of conversation

Figure 9: Example of conversation

Figure 10: Example of conversation
 
Figure 11: No result found output
 
Figure 12: End Point of conversation
