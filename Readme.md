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
![Screenshot_20221129_110023](https://user-images.githubusercontent.com/73807910/204602002-a2246b0c-cff8-4383-bea6-a98bd7574c20.png)
* ### 2. `cmd /k "jupyterEnv\Scripts\activate & jupyter notebook"` in `runJupyter.bat`
![Screenshot_20221129_110034](https://user-images.githubusercontent.com/73807910/204602061-df7f026f-b23e-4e72-ab0d-74a8b867ca26.png)
***
## Run
* ### 1. Run `installJupyter.bat`
![Screenshot_20221129_110241](https://user-images.githubusercontent.com/73807910/204602109-b42a3f29-97fc-4672-b188-74a2dd4bc530.png)
* ### 2. Run `runJupyter.bat`
![Screenshot_20221129_110438](https://user-images.githubusercontent.com/73807910/204602150-d915d4f1-bbbd-4aa8-aa3b-407d102e0142.png)
***
# Jupyter Notebook Interface
![Screenshot (30)](https://user-images.githubusercontent.com/73807910/204603815-94e2a7f8-3cb4-4597-bda9-742f7cbbd325.png)
