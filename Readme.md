# How to setup jupyter notebook on windows using "pip".
## Folder
* ### Create a folder where you want to save all your jupyter-notebook files, then open your command prompt in that same folder.
***
## Make Files
* ### 1.  `installJupyter.bat`
* ### 2.  `runJupyter.bat`
***
## Write these.
* ### 1.  `cmd /k "python -m venv jupyterEnv & jupyterEnv\Scripts\activate & pip install jupyterlab & pip install notebook"` in `installJupyter.bat`
* ### 2.  `cmd /k "jupyterEnv\Scripts\activate & jupyter notebook"` in `runJupyter.bat`
***
## Run
* ### 1. Run  `installJupyter.bat`
* ### 2. Run  `runJupyter.bat`
