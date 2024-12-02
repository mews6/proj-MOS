# proj-MOS
Little mathematical modeling problem, made in Pyomo

### Project structure

- src: where the main project is located, shows 

### Configuring Anaconda.

For the purposes of this repository, you can get by with the installation guide provided for either [Anaconda](https://docs.anaconda.com/anaconda/install/) or [Miniconda](https://docs.anaconda.com/miniconda/miniconda-install/), these installation instructions will depend on your operating system and as such, you will have to follow the corresponding guide. However, once you have set up anaconda in your system, you can make a virtual environment for you to work on by inputting the following commands while having your terminal in the repository:

```
conda init 
conda create --name myenv
```

'myenv' can be changed to whatever name you want your environment to have, and shouldn't have any bearing on the execution of such profiles. Once you have that sorted out, it can be then initialized with the following command:

```
conda activate myenv
```

to install all relevant dependencies, go to the root of your project and run:

```
conda install -c conda-forge --file requirements.txt
```