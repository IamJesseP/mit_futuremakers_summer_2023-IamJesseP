# Classification Loss Functions

## Topics covered in today's module
* Understand what optimization algorithms are, and how they are used in the context of deep learning.
* Understand gradient descent, stochastic gradient descent, and mini-batch stochastic gradient descent.
* Understand the roles of batch size, learning rate and other hyper-parameters.
* Implement, using TF2.0, gradient descent and a few variations of it.
* Understand the strengths and weaknesses of the various optimization algorithms covered in this practical.


## Main takeaways from doing today's assignment

1. **Optimization Methods**: Gradient Descent is the basis of many optimization methods that use step movements. There are many other optimization algorithms, including Stochastic Gradient Descent (SGD), Mini-Batch Gradient Descent, Momentum, AdaGrad, RMSProp, and Adam. There are also methods like Genetic Algorithms, Simulated Annealing, Particle Swarm Optimization, Differential Evolution, Random Search, and Grid Search that do not fundamentally rely on gradients.

2. **SGD vs BGD**: SGD can be better than Batch Gradient Descent when the dataset is very large, noisy updates can be beneficial, when faster convergence is needed, or in memory-limited situations.

3. **Activation Functions and Optimization**: Activation functions introduce non-linearity, which can significantly impact the optimization process. Activation functions also hepl with the 'vanishing' or 'exploding' gradient problem.




## Challenging, interesting, or exciting aspects of today's assignment
It can be challenging understanding when to use which optimizer, and it can be more about trying different optimizers and seeing what works best.

## Additional resources used 

[Data science thread on other optimizers](https://datascience.stackexchange.com/questions/47142/is-gradient-descent-central-to-every-optimizer)

[Mediun: How do activation functions impact the gradient descent optimization algorithm during training?](https://medium.com/aaweg-i-nterview/how-do-activation-functions-impact-the-gradient-descent-optimization-algorithm-during-training-378cd679e5dd)

[Medium: Activation Functions, Optimization Techniques, and Loss Functions](https://medium.com/analytics-vidhya/activation-functions-optimization-techniques-and-loss-functions-75a0eea0bc31)
