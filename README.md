# Assignment_4
Name : Dheeraj Kodakandla
ID:700738796
Drive video link:https://drive.google.com/file/d/1qZ8N4ke2vrKmZAj0oQ_RL6hC_Yw3Z1Ck/view?usp=sharing

1.	Add one more hidden layer to autoencoder.
We have executed the code given in the assignment and then we have added more hidden layer to  encode(the encoded representation of the input) and in decode(the lossy reconstruction of the input)  and this model plots an input to its reconstruction and also the encoder for its encoded representation and then compiling the model and loading the MNIST dataset after that normalize and flatten the data then train the autoencoder.
 ![image](https://github.com/dheeraj3119/Assignment_4/assets/83443076/c2ee6e9d-2bea-43ed-9137-75880bea3906)

2.	Do the prediction on the test data and then visualize one of the reconstructed version of that test data. Also, visualize the same test data before reconstruction using Matplotlib.
Here we are using the matplotlib library and then getting the reconstructed images for the test set and choosing a random image from the test set based on the index of the image to be plotted. Here we’re plotting the original image as well as plotting the reconstructed image by using an imshow() function.
![image](https://github.com/dheeraj3119/Assignment_4/assets/83443076/bb4a612e-1fa1-4ff7-902d-c6396a86e39b)
 
3.	Repeat the question 2 on the denoisening autoencoder.
Here we are repeating the step 2 in which we have done for autoencoder, in this first we have executed the code which is given and then added plotting the original noisy and reconstructed image by getting the reconstructed images for the test set and then choosing a random image from the test set.
 
![image](https://github.com/dheeraj3119/Assignment_4/assets/83443076/e2744638-3f8e-4495-8cf3-632cc3c90ef6)

4.	plot loss and accuracy using the history object
Importing the matplotlib and here we are training the autoencoder by using the autoencoder.fit() function and then plotting the both loss and accuracy by using the plot() function.
 ![image](https://github.com/dheeraj3119/Assignment_4/assets/83443076/4dd06eed-4009-40e3-b492-a8859605a4f9)
![image](https://github.com/dheeraj3119/Assignment_4/assets/83443076/e606195c-eb19-45e6-97df-8923a39d5691)
![image](https://github.com/dheeraj3119/Assignment_4/assets/83443076/fce2bb21-1b3a-4885-a141-99c3fa2c8b70)

 
