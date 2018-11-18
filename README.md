# Welcome to your NumEconCPH repository

We have provided you with the following repository that contains the required structure for this course. You should not change any folders in the root directory.  

A short description of the files and folders:

* [README.md](/README.md): gives a short introduction to your project. You should change this file so it gives an introduction to what your repository consists of, and how to run the code to get your output. The present README file is always present on [github](https://www.github.com/numeconcopenhagen/numeconcopenhagen-2018/blob/master/README.md).
* [/binder](/binder/): The folder is used by mybinder.org to setup an online jupyter notebook. The far most file to understand is [environment.yml](/binder/environment.yml)<sup>[1](#myfootnote1)</sup> that contains all the dependencies your project requires. You can read more about this [here](https://www.earthdatascience.org/workshops/setup-earth-analytics-python/setup-python-anaconda-earth-analytics-environment/#about-the-conda-environment). We have supplied you with such a file, and you should just add further dependencies to the file.
The second file named [postBuild](/binder/postBuild) just activates some plugins to jupyter notebook. You shouldn't change this file unless you do understand what you are doing.
* [/dataproject](/dataproject): The structure is as follows: it contains a jupyter notebook where all the results should be presented. Furthermore, there is a python module named the dataproject where you can write and structure all your code.
* [/examproject](/examproject): Same structure as above.
* [/modelproject](/modelproject): Same structure as above.
* [.gitignore](/.gitignore): A textfile specifying files and folder that will not be uploaded to github, and will not be tracked by git.  
---
<a name="myfootnote1">1</a>: If you haven't seen a `.yml`/`.yaml` file before please take a look [here](https://en.wikipedia.org/wiki/YAML#Basic_components)