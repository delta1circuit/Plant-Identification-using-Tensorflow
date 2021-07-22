# Plant-Identification-using-Tensorflow

This is a simple machine learning project, wherein the program detects the plant from the image og its leaf. 

The dataset used is the PlantVillage dataset from Kaggle which can be found here - https://www.kaggle.com/emmarex/plantdisease

Make a folder named "data" in the working directory of the python files. Create a folder for each plant data - I have only taken 5 plants, but you cam take as many as you want. 
Just make sure you update the classifier.py file with the names of the plants in the variable 'category' so that you get the required results. 

Running:
First run the utils.py file followed by the classifier.py file. This is a one-time job. 
Next, run the detect.py file whenever you want to see the result. Note that the result will vary everytime, as we are shuffling and using the same data for testing the results.
