# Neural Network from scratch

In the file NN_from_scratch you can see the application of the theory behind backpropagation, how it works and how it update the weights of the nodes.

# Chain rule

Is important to know that the chain rule in differentiation plays a fundamental role in this process, all of the calculations showed in the code (NN_from_scratch) are the specific gradients of the chain to obtain the weights gradients, because the goal is to update them based on how much each weight affect the output result.

# Stop iterations

In the code you can see that there is no epochs, it is because i want to shown just the application of the theory, so in this specific case i only stop the process when the weights doesn't update much more than a specific epsilon.
