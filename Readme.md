# How to setup jupyter notebook on windows using "pip".
## Folder
* ### Create a folder where you want to save all your jupyter-notebook files, then open your command prompt in that same folder.
***
## Make Files
* ### 1. `installJupyter.bat`
* ### 2. `runJupyter.bat`
![Screenshot_20221129_110450](https://user-images.githubusercontent.com/73807910/204601779-8149b80d-6452-443a-a2e1-5897deaf4e20.png)
***
## Write these.
* ### 1. `cmd /k "python -m venv jupyterEnv & jupyterEnv\Scripts\activate & pip install jupyterlab & pip install notebook"` in `installJupyter.bat`
* ### 2. `cmd /k "jupyterEnv\Scripts\activate & jupyter notebook"` in `runJupyter.bat`
***
## Run
* ### 1. Run `installJupyter.bat`
* ### 2. Run `runJupyter.bat`
