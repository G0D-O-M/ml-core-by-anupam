# ml-core-by-anupam
Built a binary classification model using only NumPy,Pandas,Matplotlib — no libraries like scikit-learn. Implemented sigmoid activation, cost function, gradient descent, and prediction logic step-by-step. Added visualization and code comments to help others understand the logic deeply.
1.  What Logistic Regression Does (Simple + Powerful)
Logistic Regression is a binary classification algorithm.
It predicts whether something belongs to class 0 or class 1 based on input features.

Instead of giving a direct class like 0 or 1, it outputs a probability between 0 and 1.

It uses a sigmoid function to map any real value to this probability range.

If the probability is > 0.5 → it predicts class 1, else class 0.

📦 Example use-cases:

Will this email be spam? (Yes/No)

Is this tumor malignant? (Yes/No)

Will a student pass the exam based on hours studied?

2.  Steps in Code
Here’s how your logistic regression model works from scratch:

Step	Code Logic	Purpose
1.	sigmoid(z)	Maps real numbers into probabilities (0–1)
2.	Initialize weights w and bias b	Start the model with zeros or random
3.	For each epoch (loop):	Train the model by improving prediction
4.	→ Calculate prediction: y_hat = sigmoid(X @ w + b)	Make prediction using current weights
5.	→ Compute cost: -1/m * Σ(y * log(y_hat) + (1 - y) * log(1 - y_hat))	Measures how wrong the prediction is
6.	→ Compute gradients: dw, db	Find how to update weights to reduce error
7.	→ Update weights: w -= learning_rate * dw	Improve the model by learning
8.	predict() function	Makes final prediction using trained model


Here is the Accuracy Graph 
