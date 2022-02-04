# MOVIE RATING PREDICTION: 

AZURE GALLERY LINK:
https://gallery.azure.ai/Experiment/Movierating-prediction-2

# Description

  We usually come across movie rating websites where users are allowed to rate ad comment on movies online. These ratings are provided as input to the website rating system. The admin then checks reviews, critic’s ratings and displays an online rating for every movie.
  Here we propose an online system that automatically allows users to post reviews and stores them to rate movies based on user sentiments. The system now analyzes this data to check for user sentiments associated with each comment. Our system consists of a sentiment library designed for English as well as hindi sentiment analysis. The system breaks user comments to check for sentimental keywords and predicts user sentiment associated with it. Once the keywords are found it associates the comment with a sentiment rank. 
  The system now gathers all comments for a particular movie and then calculates an average ranting to score it. This score is generated for every movie in the system. The system also sorts and displays top rating movies as per analysis and calculates a top ten list automatically. This provides an automated movie rating system based on sentiment analysis. Advantages Allows for automated movie rating system. False rating cannot be entered since system calculates based on user comments. It removes human errors that commonly occur during manual analysis. The system provides an unbiased result.
  Thus the system excludes human efforts and saves time and resources. Disadvantages The system must be given proper inputs otherwise system can produce wrong results. The system needs to be hosted on cloud to receive and process country wide results.

# Model Pictures:

# MOVIE RATING PREDICTION MACHINE LEARNING MODEL
![image(4)](https://user-images.githubusercontent.com/89579555/152369233-d000732c-6839-4884-a7ff-ff2efbecab5a.png)

# MOVIE RATING PREDICTION DATASET

![image](https://user-images.githubusercontent.com/89579555/152369120-e584d3ef-1a61-4394-9c59-d7199e591014.png)

# TRAINED MODEL
![image(1)](https://user-images.githubusercontent.com/89579555/152369127-fb624f39-928f-4d3c-bb93-331cd3553cb6.png)

# SCORE MODEL RATING PREDICTION
![image(2)](https://user-images.githubusercontent.com/89579555/152369182-01b170fa-8549-40cb-9819-8b9f3359fd40.png)

# SCORE MODEL FROM RATED PREDICTION
![image(3)](https://user-images.githubusercontent.com/89579555/152369216-72add909-f84e-482f-b357-d2bbdab16571.png)

# EVALUATED MODEL FOR RATING
![image(5)](https://user-images.githubusercontent.com/89579555/152369256-4c0bf39f-349a-4e16-a84d-f766c6b1cbf0.png)

# DETAILED DESCRIPTION
Create Project/Experiment and import movie rating data set from saved dataset samples. After creating experiment, we need to drag and drop the required modules in canvas.

I have used the below modules for my experiment in the given order

 DATA SET:
 
   Data set required for experiment is added
   
 IMDB MOVIE TITLES:
 
   This data set consists of movie id and movie names.
   
 Editing Metadata:
 
   Used to change data type of fields, etc.
   
 Join data:
 
   Used to join the above two dataset.
   
 Select column in dataset:
 
   Select columns to inclue or exclude from a dataset in an operation.formerly known as project columns.
   
 Remove duplicate rows:
 
   Remove the duplicate rows from a dataset.
   
 Split data:
 
   split the rows of a dataset into two distinct areas,here the dataset is splitted into Train and Score matchbox recommender.
   
 Train matchbox recommender:
 
   Train a bayesian recommender using the matchbox algorithm.
   
 Score matchbox recommender:
 
   It scores a dataset using matchbox recommender.
   
 Evaluate recommender:
 
   this is the final dataset it evaluates and gives the accuracy values 
   this evaluate recommender is used to evaluates a recommender model.
After creating, run the model by clicking run button in the bottom side. After running successfully, we can score and evaluate the model.

# Deploying the model:
Deploy the model by Setting up Web Service in ML Studio. For first time select Update Predictive Experiment. after deployment of model, it can be used in webs.

Web Service Consumption options:

     Excel 2010 or earlier
     Request-Response Web App Template
