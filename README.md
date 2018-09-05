### Flocking, Swarm, Herd Behvaiour

This project invesigates modelling the animal behaviour of flocking, swarming and herding using the same approach as the artifical life program Boids, created by Craig Reynolds in 1986. The term agent will be used to refer to a single entity/animal. In the described model each agent in our simulation maneuvers based on three behaviours:

	- Alignment: steering towards the average heading of other agents in a local radius
	- Cohesion: steering towards the average position of other agents in a local radius
	- Separation: steering to avoid crowding other agents

Expansions to this model can be built to avoid obstacles, goal seek and escape capture from predatory agents. The repository is split into two section; python modelling of the behaviour, and an interactive simulation built in d3.js.

#### Python Modelling: Launching a new environment
The following command will launch a new environment with the relevant dependencies:
```
conda env create -f environment.yml -n swarm
```
Once created, the new environment can be activated and deactivated using the following commands:
```
source activate swarm
source deactivate swarm
```
To remove the environment after deactivation run:
```
conda env remove -n swarm
```

#### Python Modelling: Observations


#### Simulation Modelling: