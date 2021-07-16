# Linear-Regression 

Linear Regression is a machine learning algorithm based on supervised learning. In the algorithm we aim to predict the real valued output. The hypothesis function for linear regression is given by:  

  

![alt text](https://www.jeevora.com/wp-content/uploads/2020/05/image-66-300x82.png)   

  

Where, h is the predicted value of the output. The aim of linear regression is to choose the values of theta_0 and theta_1 such that the value of h is as close to the value of Y i.e., the actual output as possible. That means the deviation of the predicted value and the actual value must be minimal, this deviation is called Cost function. The cost function is given by:  

  

![alt text](https://www.jeevora.com/wp-content/uploads/2020/05/image-67-768x150.png)  

  

Gradient descent is an iterative optimization algorithm to find the minimum of the Cost Function. It converges to find the global minimum. The algorithm finds the minimum value of function and determines the value of thetas corresponding to the minimum value of function. It is given by: 

  

![alt text](https://miro.medium.com/max/968/1*lIthvknHt9Tok5aIj4e__g.png) 

  

α is the learning rate that means the length of the steps down hill. If α is very small the gradient descent will take time to converge whereas if α is very large gradient descent may diverge from the global minimum. So rather we vary α w.r.t the derivative term i.e., slope then, we will converge to local minimum.
