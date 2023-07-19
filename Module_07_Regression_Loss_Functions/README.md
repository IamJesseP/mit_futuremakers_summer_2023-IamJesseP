# Regression Loss Functions

## Topics covered in today's module
* Mean Squared Error
* Mean Absolute Error
* Mean Squared Logarithm Error

## Main takeaways from doing today's assignment
* Mean Squared Error (MSE): Squares the errors before averaging them, placing a larger penalty on larger errors. It's more sensitive to outliers than MAE.
  
* Mean Absolute Error (MAE): Takes the absolute value of the errors before averaging them, placing an equal penalty on all errors. It's less sensitive to outliers than MSE.
  
* Mean Squared Logarithmic Error (MSLE): Applies a logarithm to each error, squares the result, and then averages them. It places a smaller penalty on larger errors compared to MSE, and a larger penalty on smaller errors compared to MAE. It's useful when the target variable has a wide range of values.
  
* Huber Loss: Combines the best properties of MSE and MAE. It behaves like MSE for small errors and MAE for large errors, making it less sensitive to outliers than MSE but more sensitive than MAE.
The choice of loss function depends on the specific problem and the nature of the data. It's always a good idea to experiment with different loss functions and choose the one that gives the best performance on a validation set or test set.

## Challenging, interesting, or exciting aspects of today's assignment
Learning regression functions through visualization is very helpful!

## Additional resources used 
[Common Loss Functions Article](https://towardsdatascience.com/common-loss-functions-in-machine-learning-46af0ffc4d23)
