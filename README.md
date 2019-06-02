# Udacity's Deep Learning Nanodegree
## Reinforcement Learning
## Project: Teach a Quadcopter How to Fly
Build a quadcopter flying agent that learns to take off, hover and land using Reinforcement Learning

## Project Overview
The Quadcopter or Quadrotor Helicopter is becoming an increasingly popular aircraft for both personal and professional use. Its maneuverability lends itself to many applications, from last-mile delivery to cinematography, from acrobatics to search-and-rescue.

Most quadcopters have 4 motors to provide thrust, although some other models with 6 or 8 motors are also sometimes referred to as quadcopters. Multiple points of thrust with the center of gravity in the middle improves stability and enables a variety of flying behaviors.

But it also comes at a price–the high complexity of controlling such an aircraft makes it almost impossible to manually control each individual motor's thrust. So, most commercial quadcopters try to simplify the flying controls by accepting a single thrust magnitude and yaw/pitch/roll controls, making it much more intuitive and fun.

The next step in this evolution is to enable quadcopters to autonomously achieve desired control behaviors such as takeoff and landing. You could design these controls with a classic approach (say, by implementing PID controllers). Or, you can use reinforcement learning to build agents that can learn these behaviors on their own. This is what you are going to do in this project!

## Deep Deterministic Policy Gradients (DDPG)
You can use one of many different algorithms to design your agent, as long as it works with continuous state and action spaces. One popular choice is Deep Deterministic Policy Gradients or DDPG. It is actually an actor-critic method, but the key idea is that the underlying policy function used is deterministic in nature, with some noise added in externally to produce the desired stochasticity in actions taken.

The two main components of the algorithm, the actor and critic networks can be implemented using most modern deep learning libraries, such as Keras or TensorFlow.

## Software and Libraries
This project uses the following software and Python libraries:

* [Python](https://www.python.org/download/releases)

* [NumPy](http://www.numpy.org/)

* [Pandas](https://pypi.org/project/pandas/)

* [Matplotlib](http://matplotlib.org/)

* [Tensorflow](https://www.tensorflow.org)

* [Keras](https://pypi.org/project/Keras/)

You will also need to have software installed to run and execute a
[Jupyter Notebook](http://ipython.org/notebook.html).

If you do not have Python installed yet, it is highly recommended
that you install the [Anaconda](http://continuum.io/downloads)
distribution of Python, which already has many of the above packages and more included.
