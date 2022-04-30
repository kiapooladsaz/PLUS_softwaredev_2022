# PLUS_softwaredev_2022
# Assignment 2
## Creating a new python environment
After installing anaconda on the local computer, it is possible to create new conda environments using anaconda powershell prompt(anaconda3):
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
 ## Recreating an existing environment
 The recreate_me.yml conda file has been used after cloning the forked depository ("PLUS_softwaredev_2022")[https://github.com/augustinh22/PLUS_softwaredev_2022] on local. recreate_me activated and new packages installed in it as below:
 ```
 conda activate recreate_me
 conda install -c conda-forge rasterio
 conda install scikit-learn
  ```
 Then, the environment updated and I exported to the new environment and pushed to the repositories.
  ```
 conda env update --file recreate_me.yml
 conda env export --name recreate_me > recreate_me2.yml
  ```
 ![image](https://user-images.githubusercontent.com/98283630/166112354-b8e32144-e4ca-45a1-8665-50ef52071ea9.png)
![image](https://user-images.githubusercontent.com/98283630/166112372-dc201cb6-9890-493b-a229-ec3f6a45424e.png)
![image](https://user-images.githubusercontent.com/98283630/166112385-47975ad3-5d4d-46fc-ac8b-176f13affbd9.png)
