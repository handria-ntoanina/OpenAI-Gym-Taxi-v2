# Taxi-V2
This repository contains an implementation of SARSA, SARSA-MAX, and Expected SARSA to solve the Taxi-v2 environment of OpenAI.
The result is published [here](https://github.com/openai/gym/wiki/Leaderboard#taxi-v2).
## Content of this repository
* __openai-gym-taxi-v2.ipynb__: the jupyter notebook that contains the implementation
## Requirements
To run the codes, follow the next steps:
* Create a new environment:
	* __Linux__ or __Mac__: 
	```bash
	conda create --name taxi_v2 python=3.6
	source activate taxi_v2
	```
	* __Windows__: 
	```bash
	conda create --name taxi_v2 python=3.6 
	activate taxi_v2
	```
* Perform a minimal install of OpenAI gym
	```bash
	pip install gym
	```
* Create an IPython kernel for the `taxi_v2` environment
```bash
	python -m ipykernel install --user --name taxi_v2 --display-name "taxi_v2"
```
* Start jupyter notebook from the root of this python codes
```bash
jupyter notebook
```
* Once started, change the kernel through the menu `Kernel`>`Change kernel`>`taxi_v2`

