# Machine Learning
In this repository, I upload my Complete Deep Learning code which I have learned from different courses(Coursera, udemy, edx, udacity), different websites blogs, different tutorials from YouTube, books, and research papers. I have covered both Supervised and Unsupervised Deep Learning Algorithms with Practical Implementation.

#### Our Machine Learning Blog
###### Link: https://medium.com/machine-learning-researcher

#### Book that we write on Deep Learning Topic Available on Amazon
###### Title: Deep Learning Objective
###### Link: https://www.amazon.com/dp/1070238945

#### These are following Projects that I have done in Deep Learning

  ## <----------------------------Supervised Deep Learning --------------------------->
  
### Project 1: Artificial Neural Networks to solve a Customer Churn problem
In this part, we solve a data analytics challenge for a bank. The dataset with a large sample of the bank's customers. To make this dataset, the bank gathered information such as customer id, credit score, gender, age, tenure, balance, if the customer is active, has a credit card, etc. During a period of 6 months, the bank observed if these customers left or stayed in the bank. We use Artificial Neural Network(ANN) that can predict, based on geo-demographical and transactional information given above, if any individual customer will leave the bank or stay (customer churn). Besides, we asked to rank all the customers of the bank, based on their probability of leaving. To do that, we use the right Deep Learning model, one that is based on a probabilistic approach. And in the end, we create significant added value to the bank. By applying the Deep Learning model the bank may significantly reduce customer churn. And in the end, we get 84.05% of Churn problem.
##### Project Link: https://github.com/AmirAli5/Deep-Learning/tree/master/1.Supervised%20Deep%20Learning/1.Artificial%20Neural%20Network/Dataset


### Project 2: Convolutional Neural Networks for Image Recognition
In this part, we create a Convolutional Neural Network that is able to detect various objects in images. We implement this Deep Learningmodel to recognize a cat or a dog in a set of pictures. However, this model can be reused to detect anything else and we just simply replace the dataset of image folder with another dataset. For example, you will be able to train the same model on a set of brain images, to detect if they contain a tumor or not. But if you want to keep it fitted to cats and dogs, then you will literally be able to take a picture of your cat or your dog, and your model will predict which pet you have.In this project we train our cat and dog dataset which contains ten thousand images of cat and dog and we train 80% image for training and remaining 20% image for testing and we get more than 80% accuracy. After this, we just test only take one image of cat and Dog than predict using Sigmoid function in the output layer and our model correctly predicts.
##### Source: 
Jeremy Elson, John R. Douceur, Jon Howell, Jared Saul, Asirra: A CAPTCHA that Exploits Interest-Aligned Manual Image Categorization, in Proceedings of 14th ACM Conference on Computer and Communications Security (CCS), Association for Computing Machinery, Inc., Oct. 2007
##### Project Link: https://github.com/AmirAli5/Deep-Learning/tree/master/1.Supervised%20Deep%20Learning/2.Convolutional%20Neural%20Network

### Project 3: Recurrent Neural Networks to predict Google Stock Prices
In this part, you create one of the most powerful Deep Learning models. We will even go as far as saying that you will create the Deep Learning model closest to “Artificial Intelligence”. Why is that? Because this model will have long-term memory, just like us, humans. The branch of Deep Learning which facilitates this is Recurrent Neural Networks. Classic RNNs have short memory and were neither popular nor powerful for this exact reason. But a recent major improvement in Recurrent Neural Networks gave rise to the popularity of LSTMs (Long Short Term Memory RNNs) which has completely changed the playing field. We are extremely excited to include these cutting-edge deep learning methods in our course! In this part you we implement this ultra-powerful model, and we take the challenge to use it to predict the real Google stock price. A similar challenge has already been faced by researchers at Stanford University and us to do at least as good as them.In the end we train 200 numbers of epoch after building our model we get more than 85% of real-time Google Stock Price Prediction. And In the end, we compare our result with real-time Google stock price and our predicted line is almost close to real-time Google stock price.
##### Reference:
Financial Market Time Series Prediction with Recurrent Neural Networks Armando Bernal, Sam Fok, Rohit Pidaparthi December 14, 2012.
##### Project Link: https://github.com/AmirAli5/Deep-Learning/tree/master/1.Supervised%20Deep%20Learning/3.Recurrent%20Neural%20Network

## <-------------------------Unsupervised Deep Learning --------------------------->

### Project 4: Self-Organizing Maps to investigate Fraud
According to a recent report published by Markets & Markets, the Fraud Detection and Prevention Market is going to be worth $33.19 Billion USD by 2021. This is a huge industry and the demand for advanced Deep Learning skills is only going to grow. We use Unsupervised Deep Learning Models which is Self-Organization Map. The business challenge here is about detecting fraud in credit card applications. We create a Deep Learning model for a bank and given a dataset that contains information on customers applying for an advanced credit card. This is the data that customers provided when filling the application form. We detect potential fraud within these applications. That means that by the end of the challenge, we build a Self Organization maps iterally come up with an explicit list of customers who potentially cheated on their applications.
##### Project Link: https://github.com/AmirAli5/Deep-Learning/tree/master/2.Unsupervised%20Deep%20Learning/4.Self%20Organization%20Map

### Project 5: Boltzmann Machines to create a Recommender System for Movies Ratings
From Amazon product suggestions to Netflix movie recommendations - good recommender systems are very valuable in today's World. And specialists who can create them are some of the top-paid Data Scientists on the planet. We work on a dataset that has exactly the same features as the Netflix dataset: plenty of movies, thousands of users, who have rated the movies they watched. The ratings go from 1 to 5, exactly like in the Netflix dataset, which makes the Recommender System more complex to build than if the ratings were simply “Liked” or “Not Liked”. Our final Recommender System is able to predict the ratings of the movies the customers didn’t watch. Accordingly, by ranking the predictions from 5 down to 1, our Deep Learning model able to recommend which movies each user should watch. We use our model Deep Belief Networks, complex Boltzmann. The list of movies explicit so simply needs to rate the movies you already watched, input your ratings in the dataset, execute our model and voila! The Recommender System will tell you exactly which movies you would love one night you if are out of ideas of what to watch on Netflix! 
##### Reference:
An Introduction to Restricted Boltzmann Machines Asja Fischer1,2 and Christian Igel2 1 Institut f¨ur Neuroinformatik, Ruhr-Universit¨at Bochum, Germany 2 Department of Computer Science, University of Copenhagen, Denmark.
##### Project Link: https://github.com/AmirAli5/Deep-Learning/tree/master/2.Unsupervised%20Deep%20Learning/5.Restricted%20Boltzman%20Machine

### Project 6: Stacked Auto Encoders to create a Recommender System for Movies Ratings
From Amazon product suggestions to Netflix movie recommendations - good recommender systems are very valuable in today's World. And specialists who can create them are some of the top-paid Data Scientists on the planet. We work on a dataset that has exactly the same features as the Netflix dataset: plenty of movies, thousands of users, who have rated the movies they watched. The ratings go from 1 to 5, exactly like in the Netflix dataset, which makes the Recommender System more complex to build than if the ratings were simply “Liked” or “Not Liked”. Our final Recommender System is able to predict the ratings of the movies the customers didn’t watch. Accordingly, by ranking the predictions from 5 down to 1, our Deep Learning model able to recommend which movies each user should watch. We use our model Deep Belief Networks, complex Stacked Auto Encoder. The list of movies explicit so simply needs to rate the movies you already watched, input your ratings in the dataset, execute our model and voila! The Recommender System will tell you exactly which movies you would love one night you if are out of ideas of what to watch on Netflix!!
##### Project Link: https://github.com/AmirAli5/Deep-Learning/tree/master/2.Unsupervised%20Deep%20Learning/6.Stack%20Auto%20Encoder
