# CMSC848F - Assignment 3

Name: Akashkumar Parmar   
UID: 118737430  
mail: akasparm@umd.edu


### Instructions to run the code

1. Open the workspace folder (assignment3) and run the below scripts.  
2. All the results are stored in images folder.

##  0. Setup

### 0.1 Environment setup
You can use the python environment you've set up for past assignments, or re-install it with our `environment.yml` file:

```bash
conda env create -f environment.yml
conda activate l3d
```

If you do not have Anaconda, you can quickly download it [here](https://docs.conda.io/en/latest/miniconda.html), or via the command line in with:

```bash
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
chmod +x Miniconda3-latest-Linux-x86_64.sh
bash Miniconda3-latest-Linux-x86_64.sh
```

### 0.2 Data

The data for this assignment is provided in the github repo under `data/`. You do not need to download anything yourself.

##  1. Differentiable Volume Rendering

## 1. Exploring loss functions

##  1.3. Ray sampling
### Visualization

You can run the code for part 1 with:

```bash
python main.py --config-name=box
```

##  2. Optimizing a basic implicit volume

##  2.2. Loss and training

You can train the model with..

```bash
python main.py --config-name=train_box
```

##  3. Optimizing a Neural Radiance Field (NeRF) (30 points)


### Visualization
You can train a NeRF on the lego bulldozer dataset with

```bash
python main.py --config-name=nerf_lego
```
