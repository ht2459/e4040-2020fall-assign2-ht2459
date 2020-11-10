# Assignment 2  - distributed in Github Repo e4040-2020Fall-assign2
The assignment is distributed as several jupyter notebooks and a number of directories and subdirectories in utils.

# Detailed instructions how to submit this assignment/homework:
1. The assignment will be distributed as a github classroom assignment - as a special repository accessed through a link
2. A students copy of the assignment gets created automaticaly with a special name - students have to rename the repo per instructions below
3. The solution(s) to the assignment have to be submitted inside that repository as a set of "solved" Jupyter Notebooks, and several modified python files which reside in directories/subdirectories
4. Three files/screenshots need to be uploaded into the directory "figures" which prove that the assignment has been done in the cloud


## (Re)naming of the student repository (TODO students) 
INSTRUCTIONS for naming the student's solution repository for assignments with one student:
* This step will require changing the repository name
* Students MUST use the following name for the repository with their solutions: e4040-2020Fall-assign??-UNI (the first part "e4040-2020Fall-assign??" will probably be inherited from the assignment, so only UNI needs to be added) 
* Initially, the system will give the repo a name which ends with a  student's Github userid. The student MUST change that name and replace it with the name requested in the point above
* Good Example: e4040-2020Fall-assign??-zz9999;   Bad example: e4040-2020Fall-assign??-e4040-2020Fall-assign??-zz9999.
* This change can be done from the "Settings" tab which is located on the repo page.

INSTRUCTIONS for naming the students' solution repository for assignments with more students, such as the final project. Students need to use a 4-letter groupID): 
* Template: e4040-2020Fall-Project-GroupID-UNI1-UNI2-UNI3. -> Example: e4040-2020Fall-Project-MEME-zz9999-aa9999-aa0000.


# Organization of this directory

TODO students: Run commands to create a directory tree, as described in previous assignments
```
|   .gitignore
|   Assignment2-intro.ipynb
|   predicted.csv
|   README.md
|   requirements.txt
|   task1-optimization.ipynb
|   task2-regularization.ipynb
|   task3_cnn.ipynb
|   task4-augmentation.ipynb
|   task5-kaggle.ipynb
|   
+---.ipynb_checkpoints
|       Assignment2-intro-checkpoint.ipynb
|       task1-optimization-checkpoint.ipynb
|       task2-regularization-checkpoint.ipynb
|       task3_cnn-checkpoint.ipynb
|       task4-augmentation-checkpoint.ipynb
|       task5-kaggle-checkpoint.ipynb
|       
+---data
|   |   cifar-10-python.tar.gz
|   |   
|   +---.ipynb_checkpoints
|   \---cifar-10-batches-py
|           batches.meta
|           data_batch_1
|           data_batch_2
|           data_batch_3
|           data_batch_4
|           data_batch_5
|           readme.html
|           test_batch
|           
+---KaggleModel
|       mymodel.h5
|       
+---logs
|   \---gradient_tape
|       +---.ipynb_checkpoints
|       +---20201109-060634
|       |   +---test
|       |   |       events.out.tfevents.1604901994.ecbme4040.29157.149.v2
|       |   |       
|       |   \---train
|       |           events.out.tfevents.1604901994.ecbme4040.29157.141.v2
|       |           
|       +---20201109-061352
|       |   +---test
|       |   |       events.out.tfevents.1604902432.ecbme4040.29157.2536079.v2
|       |   |       
|       |   \---train
|       |           events.out.tfevents.1604902432.ecbme4040.29157.2536071.v2
|       |           
|       +---20201109-063426
|       |   +---test
|       |   |       events.out.tfevents.1604903666.ecbme4040.30421.95.v2
|       |   |       
|       |   \---train
|       |           events.out.tfevents.1604903666.ecbme4040.30421.87.v2
|       |           
|       \---20201109-063823
|           +---test
|           |       events.out.tfevents.1604903903.ecbme4040.30421.2342975.v2
|           |       
|           \---train
|                   events.out.tfevents.1604903903.ecbme4040.30421.2342967.v2
|                   
+---screenshots
|       screenshot_1.PNG
|       screenshot_2.PNG
|       screenshot_3.PNG
|       
\---utils
    |   cifar_utils.py
    |   image_generator.py
    |   layer_funcs.py
    |   optimizers.py
    |   reg_funcs.py
    |   
    +---neuralnets
    |   |   kaggle.py
    |   |   mlp.py
    |   |   
    |   +---.ipynb_checkpoints
    |   +---cnn
    |   |   |   LeNet_trainer.py
    |   |   |   model_LeNet.py
    |   |   |   my_LeNet_trainer.py
    |   |   |   my_model_LeNet.py
    |   |   |   
    |   |   \---__pycache__
    |   |           LeNet_trainer.cpython-36.pyc
    |   |           LeNet_trainer.cpython-37.pyc
    |   |           model_LeNet.cpython-36.pyc
    |   |           model_LeNet.cpython-37.pyc
    |   |           my_LeNet_trainer.cpython-36.pyc
    |   |           my_LeNet_trainer.cpython-37.pyc
    |   |           my_model_LeNet.cpython-37.pyc
    |   |           
    |   \---__pycache__
    |           kaggle.cpython-37.pyc
    |           mlp.cpython-36.pyc
    |           mlp.cpython-37.pyc
    |           
    +---notebook_images
    |       task3_1.jpg
    |       task3_2_1.png
    |       task3_2_2.png
    |       Task3_2_2_metrics.png
    |       task3_2_answer.png
    |       
    \---__pycache__
            cifar_utils.cpython-36.pyc
            cifar_utils.cpython-37.pyc
            image_generator.cpython-36.pyc
            image_generator.cpython-37.pyc
            layer_funcs.cpython-36.pyc
            layer_funcs.cpython-37.pyc
            optimizers.cpython-36.pyc
            optimizers.cpython-37.pyc
            reg_funcs.cpython-36.pyc
            reg_funcs.cpython-37.pyc
            
