# Ball and Platform Game

### General Information

> This game was created utilizing Brian2 simulator and Pygame. It's meant to be a simple yet fun game to showcase how a spiking neural network functions in a gaming retrospect. The goal for the user is to stay on the platform as long as possible without being thrown off by the neural network. The network's goal is to rotate its platform with an intention to make the ball hit the edge of the screen.

### Installation

To get started with building an environment to run my game, you need to have a recent version of `Python3` installed. To simplify things, you can create a new directory and create a virtual environment using `venv`.

```
pip install virtualenv
pip install ipynotebook
venv ..
source ..
```

After installing jupyter notebook, if not already installed, you can create a kernel inside of your virtual environment.

```
ipynb ..
```

Now you will need to install the required packages within Brian2, Brian2, and Pygame. These can be found in the repository, but I will reiterate them below.

```
pip install Brian2
pip install ..
```

You can now run the ipynb file in the repository inside of your jupyter notebook by using the command `jupyter notebook` and then opening up the file. From here, you just need to run the file and then enjoy playing the game.

> If your getting an error, make sure you have properly installed all packages and insure you have selected the kernel you created earlier to run the file.

### Future Plans

I plan to make the game take into account the velocity of the ball when it is deciding the angle to move the platform too as well as change the SNN to move the platform left and right in addition to the current rotation feature. I would also like to experiment with using reinforcement learning to train the neural network with a reward function of making the ball hit the edge of the screen.

- [ ] Use a different model to take into account the ball's velocity.
- [ ] Use the SNN's spiking feature by implementing an activation and reset value.
- [ ] Try basing the code off of the solution for **inverted pendulum** problem.
- [ ] Train neural network with RL and implement a reward function
- [ ] Allow SNN to move the platform left and right to best knock off the ball.
