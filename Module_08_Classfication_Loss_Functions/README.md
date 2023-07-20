# Classification Loss Functions

## Topics covered in today's module
* Kullback Leibler Divergence Loss
* Binary Cross-Entropy
* Categorical Cross-Entropy
* Sparse Categorical Cross-Entropy

## Main takeaways from doing today's assignment
- **Multi-class Classification**: 
  - Each instance belongs to exactly one class.
  - Commonly uses categorical cross-entropy loss.
  - Typically uses a softmax activation function in the output layer.

- **Multi-label Classification**: 
  - Each instance can belong to multiple classes.
  - Commonly uses binary cross-entropy loss.
  - Typically uses a sigmoid activation function in the output layer.

- **Binary Cross-Entropy vs Categorical Cross-Entropy**: 
  - Binary Cross-Entropy is used for two-class problems.
  - Categorical Cross-Entropy is a generalization of Binary Cross-Entropy for multi-class problems.

- **Categorical Cross-Entropy vs Sparse Categorical Cross-Entropy**: 
  - Categorical Cross-Entropy is used when the labels are one-hot encoded.
  - Sparse Categorical Cross-Entropy is used when the labels are integers.

## Challenging, interesting, or exciting aspects of today's assignment
Implementing CCE from scratch is challening and confusing!

