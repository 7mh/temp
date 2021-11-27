# Cifar Fine Tune
## Description of Code


- Validation during Training
  * I am running validation using test dataset after couple of epochs
  * Upon acheiving better validation error 
    - I save the current model in file named "trained_model.pt"
    - Retain the new value for lambda (L2 regularization value)
  * Prints out the best value for lambda

- After Training
  * Read the best trained model from file named "trained_model.pt"
  * Run Accuracy test using test data.
  * Prints Accuracy  
     
## To Run the Code
From terminal run:
`python3 cifar_finetune.py`

