# TSAI-Backpropagation-and-Architectural-Basics

Part 1 

![Neural Network in Excel](https://user-images.githubusercontent.com/71637993/137791196-96ef929d-efe4-44d5-ad13-dd930d101a35.jpg)
 
 The Excel sheet helps us to create a simple Neural Network 
 The Neural Network Architecture comprises of the Following :
  1. Input Layers - We have considered only two fetaures as input [i1,12] 
  2. Hidden Layers - hidden layers comprises of two operation i,e( dot product between input vector and its weights(h1,h2) , Introducing Non-Linearity using a sigmoid activation(a_h1,a_h2))
  3. Output Layers - two neurons in the final layers which takes in inputs from the previous layers and produces two outputs using the operation mentined above i.e(o_1, o_2, a_o1 , a_02)
Weights are Initialized Randomly 
From the Output Layers we calculate the Losses Et1 =(t1-a_o1) and Et2=  (t2-a_o2). The total loss Etotal = Et1+Et2
We try to minimize this loss with the help of backward propagation where we try to adjust the weights to minimize the losses . 
Various Learning rates are used to understand the behaviour of convergence of the loss function to a minima 

We see that with increase in learning rate from [0.1, 0.2, 0.5, 0.8, 1.0, 2.0] , The loss function converging with fewer number of epochs 

![image](https://user-images.githubusercontent.com/71637993/137793187-380f0eef-79dd-406d-bead-1a03f3fe9828.png)

![image](https://user-images.githubusercontent.com/71637993/137793495-18024065-acef-4bdd-8556-5c49ee785ff2.png)

![image](https://user-images.githubusercontent.com/71637993/137793634-141ba2a8-5b02-4421-a38a-9ba6264a719e.png)

![image](https://user-images.githubusercontent.com/71637993/137793582-c522fefe-4ce7-4351-8476-74f82ef59e13.png)

![image](https://user-images.githubusercontent.com/71637993/137793411-215c0756-e15d-4daf-b9f0-657fcf0b686e.png)

![image](https://user-images.githubusercontent.com/71637993/137793459-0f029437-1709-4e2e-a010-8a189deea753.png)

![image](https://user-images.githubusercontent.com/71637993/137793803-741d503e-8110-4d82-8402-88f7b4129ba3.png)

