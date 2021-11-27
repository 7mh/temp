# Cifar Fine Tune
## Description of Code


- Validation during Training
  1 I am running validation using test dataset after couple of epochs
  2 Upon acheiving better validation error 
    - I save the current model in file named "trained_model.pt"
    - Retain the new value for lambda (L2 regularization value)
  3 Prints out the best value for lambda

- After Training
  1 Read the best trained model from file named "trained_model.pt"
  2 Run Accuracy test using test data.
  3 Prints Accuracy  
     
## To Run the Code
From terminal run:
`python3 cifar_finetune.py`

