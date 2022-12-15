
<br>

<center><img src="Img/Machine-Learning.jpeg"></center>

<br>

<div align="center">
<center><h1>MACHINE LEARNING AND STATISTICS</h1></center>
</div>

***

_This repository contains the 'MACHINE LEARNING AND STATISTICS' module project and exercises. The **README** describes step by step what software was used and how to launch the project._


<div align="center">
<center><h2>SetUp</h2></center>
</div>

###  Windows Subsystem for Linux (WSL) terminal

- Download from Microsoft Store - Ubuntu 20.04 LTS.


### Jupyter Notebook in Windows Subsystem for Linux|WSL

- Installing Jupyter Notebook

```sh
pip3 install jupyter
```

- Open your bash configuration

```sh
vim ~/.bashrc
```

- Add to the end of the file and save/exit

```sh
alias jupyter-notebook="~/.local/bin/jupyter-notebook --no-browser"
```

- Run a jupyter server

```sh
jupyter-notebook
```
```sh
jupyter lab
```

- Install the required packages:

```sh
pip install -r requirements.txt
```
<br>

###  Visual studio code + Windows Terminal (Connect with WSL)

#### VS Code

- Download Visual studio code: https://code.visualstudio.com/download/

#### Windows Terminal

- Download Windows Terminal: https://docs.microsoft.com/en-us/windows/terminal/

***
### Quick view

The Jupyter notebook can be seen through the URL links:

|    Description                      |                                                                  Link                         | 
|:------------------------------|:-------------------------------------------------------------------------------------------------------|
| *nbviewer* in static form:                    |  [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/Denio13/MACHINE_LEARNING_and_STATISTICS/tree/main/)                           |
| *binder* in dynamic form:                   | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Denio13/MACHINE_LEARNING_and_STATISTICS/HEAD) 


> **_NOTE:_** We cannot use the public _mybinder.org_ and  _nbviewer.org_ instances with a private repository

---

<div align="center">
<center><h2>Exercises</h2></center>
</div>

In this *Exercises* folder, all the topics that we have covered in this ML and Statistics module. 

Topic I:
- [The lady tasting tea experiment](https://github.com/Denio13/MACHINE_LEARNING_and_STATISTICS/blob/main/Exercises/Exercise_week_01.ipynb)

Topic II:
- [Models](https://github.com/Denio13/MACHINE_LEARNING_and_STATISTICS/blob/main/Exercises/Exercise_week_02.ipynb)

Topic III:
- [Parameters](https://github.com/Denio13/MACHINE_LEARNING_and_STATISTICS/blob/main/Exercises/Exercise_week_07.ipynb)

Topic IV:
- [Machine Learning](https://github.com/Denio13/MACHINE_LEARNING_and_STATISTICS/blob/main/Exercises/Exercise_week_09.ipynb)
---



<div align="center">
<center><h1>Project</h1></center>
</div>
<br>

<center><img src="Img/keras.png"></center>

<br>

The Jupyter notebook [Project_anomaly-detection](https://github.com/Denio13/MACHINE_LEARNING_and_STATISTICS/blob/main/Project_anomaly-detection.ipynb) contains the final project of the Machine Learning and Statistics module.
In this project, I have to recreate the **Timeseries anomaly detection** example from the [keras site](https://keras.io/examples/timeseries/timeseries_anomaly_detection/) in my Jupyter notebook, explaining all the concepts.


### Support
You can ask questions and join the development discussion:

- In the [TensorFlow forum](https://discuss.tensorflow.org/).
- On the [Keras Google group](https://groups.google.com/g/keras-users).

<br>

### Summary and Conclusion

Learning the ML and Statistics module, and especially working on practical exercises, gave me the knowledge of how to describe the stochastic nature of real-world measurements, choose an appropriate mathematical model of a real-world problem, and also choose an appropriate cost function for a given machine learning
task and apply optimization methods to the model parameters.