OVERVIEW: 
The purpose of this analysis is to help Alphabet Soup identify applicants that would most likely be successful in their ventures. 

RESULTS:
First, I preprocessed the data by reading in the charity data csv, dropping a few columns in the data set, binning , encoding, splitting data into training and testing datasets, and scaling those datasets. 

Second, I compiled, trained, and evaluated the model, in which I saved and downloaded a new file. 

Third, I reviewed the results, which were below the 75% accuracy rate. Therefore, I went back to the beginning and followed the First step of preprocessing the data, then compiling...evaluating the model. I made sure this time around to change the number of epochs from 100 to 50. I also adjusted the layers to: layer one = 8 to 2 & layer two = 5 to 1.