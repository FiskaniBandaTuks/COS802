# FINE-GRAINED DETECTION OF SEXISM USING NATURAL LANGUAGE PROCESSING TECHNIQUES 
# Done by : Fiskani Banda , u16060416 

In this project , experimentation is used to find the most suitable model to perform  the classification task that is presented. Firstly preprocessing of the data is performed. Some of the entries have multiple labels and due to the different granularity levels of the labels, there are multiple classes. Thus, this is a multi-class and multi-label classification . The overall experimentation can be divided into 2 steps : (i) Feature Engineering and (ii) Model Implementation .

## Compilation Enviroment 

The main code document Sexism_Project.ipynb is ran and performed on Google colab. Parts of the code has  been coded out as it takes more than an hour to compile, thus if required please uncomment the following sections : 
- Data Augmentation

No additional setup is required , unless using another environment is used to compile the code. If a different environment is used to compile the code , some extra python module installations might be required. Please use the command !pip install "module name" at the beginning of the script for it to run smoothly. To easily run the code without any problems, the google colab enviroment is suggested. 

## Sections of the code 

The code is divided into 3 sections , namely : 
- Data Analysis - This section covers the loading of the dataset and the libraries , the initial data analysis as well as the preprocessing of the data. 
- Experimental Setup - This section covers the data augmentation as well as the data preparation needed before the feature extraction and classification section 
- Feature Extraction and Classification - This section performs the 3 different feature extraction methods : TF-IDF , Word2vec and FastText. This is where the classifiers are implemented. The classifiers explored in this project is : MLP, KNN, Naive Bayes, One-vs-Rest and SVM. 

## Dataset 
The datasets that are used in the project have been divided into 2 : the original dataset and the augmented dataset. These can be found in their respective folders. The original dataset is te dataset that is derived directly from the SemEval 2022 Task 10 , and th augmented dataset contains the csv file which houses the augmented data as well as the original data. 
