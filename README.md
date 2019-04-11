# Quadcopter Project

Objective is to design an agent to fly a quadcopter, and then train it using a reinforcement learning algorithm of your choice!

## How to read the files in this project?

The files in the directory are structured in the following manner:

> **data.txt:** Data to train the agent

> **task.py:** Define your task (environment) in this file.

> **agents/:** Folder containing reinforcement learning agents.

	> policy_search.py: A sample agent has been provided here.	

	> agent.py: Develop your agent here.

> **physics_sim.py:** This file contains the simulator for the quadcopter. **DO NOT MODIFY THIS FILE.**

> **rewards.txt:** This is the output of total rewards collected by the trained agent over a 1000 episodes.


For this project, you will define your own task in **task.py**. Although we have provided a example task to get you started, you are encouraged to change it. Later in this notebook, you will learn more about how to amend this file.

You will also design a reinforcement learning agent in agent.py to complete your chosen task.

You are welcome to create any additional files to help you to organize your code. For instance, you may find it useful to define a **agent.py** file defining any needed neural network architectures.

You will need a software installed to run and execute a Jupyter Notebook. If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included. 

## **Why does this all matter?**

This was the 2nd last project from Udacity's machine learning nanodegree course which sets you to familarize how to develop a deep learning model to train an agent to fly and develop a reward function which ensures agent is constantly aiming to optimally maximize the reinforcement function. Understanding the impact of various hyperparameters to train and reward an agent becomes uptmost importance when we look for incremental lift from a model.


## FAQ

**What if Quadcopter_Project.ipny is not loading?**
> Try downloading the file and running on Jupyter Notebook.

