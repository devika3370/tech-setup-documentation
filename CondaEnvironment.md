## Create a new conda environment
```
conda create --name <my-env> python=3.10
```

## Creating a new environment from a YAML file
```
conda env create -f environment.yml
```

## List the environments
```
conda info --envs
conda info list
```

## Activate and Deactivate the environment 
```
conda activate <my-env>
conda deactivate <my-env>
```

## Cloning the environment 
```
conda create --name myclone --clone myenv
```

### Reference
https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#activating-an-environment
