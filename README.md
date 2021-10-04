# Mnist-from-scratch
Note: Please download the training and test files from <a href="https://www.kaggle.com/oddrationale/mnist-in-csv?select=mnist_test.csv" target="_top">here</a>
and place in the same folder as the jupyter notebook if you want to run this on your own device

## About the project
This was my first project with neural networks and they have been something that have always interested me so i thought the best way to learn more about them was to throw myself in at the deep end and construct a simple one from scratch allowing me to better understand the maths invoved. Below I have compiled a list of resources I found particularly useful and how they helped me in the construction of this project. 

## Useful Resources

1. The first resource I found particularly useful and thought was a good starting point was <a href="https://youtu.be/w8yWXqWQYmU" target="_top">this video</a> by Samson Zhang. I thought Samson did a great job at broadly explaining the structure of a simple neural network and how to implement this into code. The implementation of the forward pass and backpropagation were particularly useful and inspired me to structure my network in a similar fashion. The explanation of the different parts of the network and what they did along with the maths was not as in depth as I had liked which propmpted me to find other resources: but overall this was a great simple introduction to a neural network. 

2. The next resource I used was this playlist by 3Blue1Brown and was great at covering the theory of a neural network and at explaining the forward and backpropagation mathematically as well as the different activations functions. It did not cover the translation into code but along with the previous resource provided a very holistic view on neural networks. The esxplanation of gradient descent was particularly good.

3. I found -<a href="https://machinelearningmastery.com/gradient-descent-optimization-from-scratch/#:~:text=Gradient%20descent%20is%20an%20optimization,a%20few%20lines%20of%20code." target="_top">this</a> post very helpful in expanding on the different types of gradient descents and their characteristics which make them suited to different situations

4. The following posts I found useful as they informed of the best cross loss to use for what type of problem and the appropriate activation function along with it.
-<a href="https://glassboxmedicine.com/2019/05/26/classification-sigmoid-vs-softmax/" target="_top">Blog post on the softmax vs sigmoid activation function and the type of problems suited to the function</a>
-<a href="https://machinelearningmastery.com/how-to-choose-loss-functions-when-training-deep-learning-neural-networks/" target="_top">Blog post on the different types of loss functions and the appropriate problems for them</a>


5. Another set of resources that were useful to me were the following websites, papers and videos. They helped with the derivation of the softmax functions and aided my understanding of the cross loss. 
-<a href="https://www.ics.uci.edu/~pjsadows/notes.pdf" target="_top">University of California Irvine notes on Backpropagation</a>
-<a href="https://youtu.be/5-rVLSc2XdE" target="_top">Youtube video of an explanation of the derivation of the cross entropy with the softmax</a>
--<a href="https://levelup.gitconnected.com/killer-combo-softmax-and-cross-entropy-5907442f60ba" target="_top">blog post of an explanation of the derivation of the cross entropy with the softmax</a>
