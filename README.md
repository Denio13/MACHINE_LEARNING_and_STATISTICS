
<div align="center">
<center><h1>MACHINE LEARNING AND STATISTICS</h1></center>
</div>

***
## My Setup

###  Windows Subsystem for Linux (WSL) terminal

Download from Microsoft Store - Ubuntu 20.04 LTS.


### Jupyter Notebook in Windows Subsystem for Linux|WSL

Installing Jupyter Notebook

```sh
pip3 install jupyter
```

Open your bash configuration

```sh
vim ~/.bashrc
```

Add to the end of the file and save/exit

```sh
alias jupyter-notebook="~/.local/bin/jupyter-notebook --no-browser"
```

Run a jupyter server

```sh
jupyter-notebook
```
```sh
jupyter lab
```

Install the required packages:

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

The notebook can be seen through the URL links:

|    Description                      |                                                                  Link                         | 
|:------------------------------|:-------------------------------------------------------------------------------------------------------|
| *nbviewer* in static form:                    |  [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/Denio13/MACHINE_LEARNING_and_STATISTICS/blob/main/Exercises/Exercise_week_01.ipynb)                           |
| *binder* in dynamic form:                   | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Denio13/MACHINE_LEARNING_and_STATISTICS/blob/main/Exercises/HEAD?labpath=Exercise_week_01.ipynb) 


> **_NOTE:_** We cannot use the public _mybinder.org_ and  _nbviewer.org_ instances with a private repository

---


### Summary and Conclusion
