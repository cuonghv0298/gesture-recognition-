# Aims
You need to accomplish the following in the project:

* Generator:  The generator should be able to take a batch of videos as input without any error. Steps like cropping, resizing and normalization should be performed successfully.

* Model: Develop a model that is able to train without any errors which will be judged on the total number of parameters (as the inference(prediction) time should be less) and the accuracy achieved. As suggested by Snehansu, start training on a small amount of data and then proceed further.

* Write up: This should contain the detailed procedure followed in choosing the final model. The write up should start with the reason for choosing the base model, then highlight the reasons and metrics taken into consideration to modify and experiment to arrive at the final model. 
# Evaluation Rubric
![Build Status](<imgs/Evaluation Rubric.PNG>)

# TODO list
1. Implement Generator 
2. Choose models and finetune. 
3. Write up 

# Work flow
1. Generator implementation as one notebook (ipynb1)
2. From ipynb1 => code experiment 
    * conv3D
    * Time Distributed + other model
    * CNN + LSTM + other
3. Fill in writeup file
4. Write the conclusion