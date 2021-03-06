# Intro-to-AI-Machine-Learning-and-Python-basics
Compilation of everything I learned from a Udemy course of AI, ML, &amp; Python
_________
## Contents

	• Knowledge:
		○ Vocab
		○ Explanation
	• Sources
	
	
	• Attached Work (Python)
		○ Reggression Example (Excel)
		○ Python Basics
		○ Python Basics Two
		○ Linear Regression & Training 1
		o Classification Model - Titanic
		o Neural Network - Fashion MNIST

_________
## Knowledge

### Vocab:
	• Heuristics:
		○ a rule that works in many cases, but not in all. Enables you to quickly make a decision when there is no way or time for a detailed analysis of the situation.
	• Deep Learning:
		○ use of neural networks in machine learning.
	• Neural networks:
		○ algorithms which imitate the logic of the human brain.
	• Supervised Learning:
		○ model is trained on labeled data (prepared data).
	• Unsupervised Learning:
		○ model is trained on unlabeled data (algorithm makes decisions based on data attributes).
	• Regression:
		○ determining a predicated numerical value based on a given data set. Values generally follow a trend (e.g. linear or exponential regression).
	• Classification:
		○ segmenting data based on features that could predict a specific outcome (e.g. likely versus unlikely to default on a bank loan based on data patterns).
	• Clustering:
		○ a method of understanding data sets by placing data with similar attributes into similar groups or "clusters."
	• Ensemble Methods:
		○ Combines different algorithms to make a data model more accurate
	• Bagging:
		○ Breakdown data set into smaller randomly generated data sets that can be more easily analyzed, then aggregate the results. (Parallel Training Method)
	• Boosting:
		○ First algorithm is trained on the data set. Every subsequent algorithm is modified to correct the previous versions mistakes. (Sequential Training Method)
	• Random Forest:
		○ Create data subsets, use different features for every set, then analyze and aggregate the results (similar to Bagging)
	• Epoch:
		○ Pass / Train the entire dataset through the neural network once

### Explanations:
	• AI -> ML -> Deep Learning
	
	• Neural Network:  Input Layer -> Hidden Layer -> Output Layer
		o Hidden layer nodes have different weights that help determine output
		
	• Neural Network Example:
		o We will be using  Fashion MNIST dataset (contains 70,000 images of clothing)
		o The neural network will be able to determine the clothing item inputted into the code
			
		o This neural network will divide the Fashion MNIST dataset between training & test sample (ratio - 6:1)
		○ Dataset has 10 classes of items:
			• 0 T-shirt/top
			• 1 Trouser
			• 2 Pullover
			• 3 Dress
			• 4 Coat
			• 5 Sandal
			• 6 Shirt
			• 7 Sneaker
			• 8 Bag
			• 9 Ankle boot
		○ Each image has image size (28 x 28) and color intensity (0 - 255)
		
		o The neural network can only make determinations based on the above numerical factors (i.e. the neural network can't "see" the image only its details)

		o Architecture of the Fashion MNIST Neural Network
			•  Input Layer:  Will transform images from 2d to 1d
			•  Hidden Layer:  Training will be performed here
			•  Output Layer:  Will predict what class the image belongs to
		
		○ Training Method:
			•  Back Propagation Algorithm:  neural networks guesses then answer is checked and graded; repeat as needed
				o If the model predicted correctly, weights increase.
				o If the model was wrong, weights decrease.


___________
## Sources:

https://www.udemy.com/course/introduction-to-ai-machine-learning-and-python-basics/

https://www.kaggle.com/c/titanic

https://www.kaggle.com/zalando-research/fashionmnist
