Assignmnet 1 - 
	Good reference - https://github.com/Arn-O/udacity-deep-learning/blob/master/1_notmnist.ipynb
	
	Understand : In training whatever size of x is, we create according y vector. Here we use reshape function to shape it properly. In case of text classification, scikitlearn provide fit_transform() or fit() function to do this reshaping. 

	Cosnider matrix of 28x28. For 50 iamge of each class, we store each pixel feature in matrix. When we test, we match new image 28x28 pixel with 50 images normalized pixel position. 

	This is simple logistic regression, which store images pixel in matrix as a feature to train the classifier. And match new input text image's feature with trained data to predict. 

	Without deep learning even this classifier works well. Let's see what is next in the course.
