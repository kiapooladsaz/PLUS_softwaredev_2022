# PLUS_softwaredev_2022

## Creating a new Conda environment:
After installing anaconda on the local computer, it is possible to create new conda environments using anaconda prompt:
```
conda create -n conda_env_k python=3.7 scikit-learn
conda activate conda_env_k

```
## Exporting the environment
In order to export the requirement file (.yml), I set the location into envs repository first and then follow as below:
```
conda env export --name conda_env_k > conda_env_k.yml
```
a scrrenshot of the command:

![conda command](https://user-images.githubusercontent.com/98283630/165188718-99125824-722b-4400-995f-1c3505862c60.JPG)
