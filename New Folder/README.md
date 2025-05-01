# Brain Tumor Segmentation (via VSCODE AND STREAMLIT)

I am S.Sakthinayagam 2023305519 Studying at Anna Univerrsity. I pursue IBT and currently studying 2nd year.  

I have created a software which helps to predict the tumor region segmentation in streamlit(via VS code)
this app includes 

i) a set of requirement modules like tensorflow, matplotlib , opencv-python and various other .

ii)tumor_model.h5 is a file that consists of various binary datas which uses the set of libraries from the required modules and use it.

iii)the unet_model.py is a python file which is used to train the tumor model by comparing with other datas

iv)main.py is the main operating file which contains a wide amount of data

v)app.py is the code which is integrated with the streamline app


Steps:
1)Create a separate folder and make it as a virtual environment

2)Add all these files

3)Download all the requirements using pip installer in the terminal(ctrl+shift+`)

4)Check or the data files and make sure their path are connected properly with the main.py

5)now create a seperate folder named .streamlit and create a seperate file named .concig.toml and modify it according to fonts , colors and other requirements 

EX:[theme]
base="dark"
primaryColor="#a503fc"
backgroundColor="#a503fc"
secondaryBackgroundColor="#1e1e1e"
textColor="#ffffff"
font="Times New Roman"

6)Now go to app.py and try to run, check if all the modules are installed. If not, install all the packages using pip installer.

7)Incase Some modules like tensorflow kerans will not able to be accesed. U can go to Settings icon> Settings. On the right corner you will see a doc symbol mentioning.json. Click it and run this code

{
    "files.autoSave": "afterDelay",
    "code-runner.runInTerminal": true,
    "editor.minimap.enabled": false,
    "liveServer.settings.donotVerifyTags": true,
    "explorer.confirmDelete": false,
    "explorer.confirmPasteNative": false,
    "python.analysis.extraPaths": ["C:/path/to/venv/Lib/site-packages"],
    "python.analysis.diagnosticSeverityOverrides": {
        "reportMissingImports": "none",
        "reportUndefinedVariable":"none"
}
} 

8)Now if all the packages are installed. Open the terminal againa and enter python -m streamlit run app.py

9)This will enter into a new page in your webbrowser(incase of module errors try to download those)

10)Now the app is ready. Please add a MRI image and you will get the predicted result

