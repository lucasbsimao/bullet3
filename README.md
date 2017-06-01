
# Bullet mod

This bullet source code replace the original Vehicle dynamics, which uses Jacobian to calculate the physics, by one that uses simple uniform circular motion. The goal is to adapt the environment
to one that the cars used in IEEE VSSS category would act. An example of the model adapted is shown below.

![alt text](https://github.com/lucasbsimao/bullet3/blob/master/images/vss1.png "Logo Title Text 1")

It was necessery because jacobian is not the right way to calculate the physics for this model, as explained in my graduation final project [here](https://github.com/lucasbsimao/simVSSS/blob/master/doc/simVSSS%20and%20Reinforcement%20Learning.pdf).

It was used to develop the simVSSS, which is a physics simulator for IEEE Very Small Size Soccer.

The original Bullet Physics project is [here](https://github.com/bulletphysics/bullet3).
