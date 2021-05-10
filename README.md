# musical-waddle
Recurrent Neural Network

# Problem:
Using the Keras dataset, create a new notebook and perform each of the following data preparation tasks and answer the related questions:

- Read Reuters dataset into training and testing 
- Prepare dataset
- Build and compile 3 different models using Keras LTSM ideally improving model at each iteration.
- Describe and explain your findings.

# Abstract:
Your next generation search engine startup was successful in having the ability to search for images based on their content. As a result, the startup received its second round of funding to be able to search news articles based on their topic. As the lead data scientist, you are tasked to build a model that classifies the topic of each article or newswire. 

For this assignment, you will leverage the RNN_KERAS.ipynb lab in the lesson. You are tasked to use the Keras Reuters newswire topics classification dataset. This dataset contains 11,228 newswires from Reuters, labeled with over 46 topics. Each wire is encoded as a sequence of word indexes. For convenience, words are indexed by overall frequency in the dataset, so that for instance the integer "3" encodes the 3rd most frequent word in the data. This allows for quick filtering operations such as: "only consider the top 10,000 most common words, but eliminate the top 20 most common words". As a convention, "0" does not stand for a specific word, but instead is used to encode any unknown word.

The analysis is is divided the following way:

### Data Exploration
- **Looking at an example**


### Analysis
- **Processing the data**
- **Training variables (*hyperparameters*)**
- **RNN Model**
    - Based Model
    - 2nd Model
    - 3rd Model
- **Results**

        
### Summary of Findings
