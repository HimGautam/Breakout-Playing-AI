# Breakout-Playing-AI
This project is implementation of [Double Deep Q Learning paper](https://arxiv.org/pdf/1509.06461.pdf) by Hado van Hasselt and Arthur Guez and David Silver.


&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;![ezgif com-gif-maker](https://user-images.githubusercontent.com/70597091/122637291-6ab4a080-d10b-11eb-9b19-f6c6542e69f7.gif)

# Overview
Deep Q Learning is the combination of Deep Learning and Reinforcement Learning. In simple words, the Convolutional Neural Network learns to play the atarti game breakout like humans by Trial and Error.

Reinforcement Learning is Learning Optimal Decision Making by Rewards and Punishment.
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;![image](https://user-images.githubusercontent.com/70597091/122637872-92f1ce80-d10e-11eb-9e30-ea353aabc2dc.png)

It has different names in the differnet fields.
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;![image](https://user-images.githubusercontent.com/70597091/122637753-fb8c7b80-d10d-11eb-995f-b8d6c67005b5.png)

# Requirements

This code was tested on a GPU powered laptop with:
1. Python v3.8.5
2. Jupyter Notebook v6.2.0
3. OpenAI Gym v0.18
4. Tensorflow GPU v2.3.2
5. Numpy v1.19.2
6. Matplotlib v3.3.2

# Training

If you want to train the CNN from the random weights then run [Breakout_train](https://github.com/HimGautam/Breakout-Playing-AI/blob/main/Breakout_train.ipynb).
This will create new weights file named Breakout_new.hdf5.

# Testing 
If you dont want to train the CNN and just see the results then run [Breakout_test](https://github.com/HimGautam/Breakout-Playing-AI/blob/main/Breakout_test%20.ipynb). This will run the code with the given [weights](https://github.com/HimGautam/Breakout-Playing-AI/blob/main/Breakout.hdf5) file.

# Results and Conclusion

https://user-images.githubusercontent.com/70597091/122638527-2d9fdc80-d112-11eb-817c-0d45d38f76aa.mp4

The results of the experiment can be seen in the video above. The performance of the agent is not reached to the level of agent mentioned in the [DDQN paper](https://arxiv.org/pdf/1509.06461.pdf). This could be due to the memory constraints of the machine on which the simulation was done.

The results can be improved by training the agent in a Good Performing Machine for longer time.
