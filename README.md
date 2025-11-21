# lars_heron
Demos for 
1. Least angle regression (LARS)
2. Heron's method generalized to the nth root

## Instructions
please use the jupyter notebook (`lars_heron.ipynb`) to see the LARS method 
applied to the diabetes data and a simple calculation of nth roots using the 
generalized Heron's method. 

### Codespaces
The easiest way to use this notebook is to start a Github codespace.
1. Go here https://github.com/lukeamyers/lars_heron
2. click Code (the big green button) > Codespaces > Create codespace on main
3. wait for the codespace to build This will take maybe 3-4 minutes
4. It may seem like its ready, but please wait longer for the postCreate 
command to finish installing conda. This will take another minute or two
5. open the `lars_heron.ipynb` file
6. you may be prompted to install an extension for python. Do so if you wish.
6. click select kernel
7. click install kernel suggestions extension
7. select python enivronments and choose "venv"

You should now be able to run the jupyter notebook.

### Conda
Alternatively you can run the notebook however you like as long as you have 
the dependencies in the envrionment.yml file installed. You can do this using 
conda with the following line
`conda env create -f environment.yml`
