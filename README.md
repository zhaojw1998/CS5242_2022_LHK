# CS5242_2022_Spring
Neural Networks and Deep Learning, NUS CS5242, 2022 Spring. 

PyTorch is required for the quiz and project of this module. This repo guides you to set up the pytorch environment for both quiz and project.


<br><br>

### Set Environment for OSX & Linux

* Open a Terminal and type


```sh
   # Conda installation (skip this if you've already had Anaconda/Miniconda installed)
   curl https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh -o miniconda.sh -J -L -k # Linux
   curl https://repo.continuum.io/miniconda/Miniconda3-latest-MacOSX-x86_64.sh -o miniconda.sh -J -L -k # OSX
   chmod +x miniconda.sh
   ./miniconda.sh
   source ~/.bashrc

   # Clone GitHub repo
   git clone https://github.com/zhaojw1998/CS5242_2022_Spring.git
   cd CS5242_2022_Spring

   # Install python libraries
   conda env create -f environment.yml
   source activate deeplearn_course

   # Run the notebooks
   jupyter notebook
   ```




### Set Project and Quiz Environment for Windows 

```sh
   # Conda Installation (skip this if you've already hav Anaconda/Miniconda installed)
   https://repo.anaconda.com/miniconda/Miniconda3-latest-Windows-x86_64.exe

   # Open an Anaconda Terminal 
   Go to Application => Anaconda3 => Anaconda Prompt 

   # Install git : Type in terminal
   conda install git 

   # Clone GitHub repo
   git clone https://github.com/zhaojw1998/CS5242_2022_Spring.git
   cd CS5242_2022_Spring

   # Install python libraries
   conda env create -f environment_windows.yml
   conda activate deeplearn_course

   # Run the notebooks
   jupyter notebook
   ```


### Credit
This repo is credited to Prof. Xavier Bresson. The origional repo is https://github.com/xbresson/CS5242_2021.


<br><br><br><br><br><br>