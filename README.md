## Video of trained agent exploiting the environment

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/8xcRQOdx3u4/0.jpg)](https://www.youtube.com/watch?v=8xcRQOdx3u4)

## Dependencies

To set up your python environment to run the code in this repository, follow the instructions below.

1. Create (and activate) a new environment with Python 3.6.

	- __Linux__ or __Mac__: 
	```bash
	conda create --name drlnd python=3.6
	source activate drlnd
	```
	- __Windows__: 
	```bash
	conda create --name drlnd python=3.6 
	activate drlnd
	```
	
2. Clone the repository and navigate to the `unity_environment/` folder.  Then, install several dependencies.
```bash
git clone https://github.com/JuliuszB12/unity-ml-agent-with-deep-q-learning.git
cd unity-ml-agent-with-deep-q-learning/unity_environment
pip install .
```

3. Download ready Unity ML-Agent environment and place it in repository folder.
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

4. Create an [IPython kernel](http://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the `env_name` environment.  
```bash
python -m ipykernel install --user --name env_name --display-name "env_name"
```

5. Before running code in a notebook, change the kernel to match the `env_name` environment by using the drop-down `Kernel` menu. 

## Ref

Unity ML-Agent Environment: https://github.com/Unity-Technologies/ml-agents  
Deep Q-Learning algorithm:
Udacity Deep Reinforcement Learning Nanodegree: https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893
