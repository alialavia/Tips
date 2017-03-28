# Tips
Various tips and tricks

## PYTHON
### Autoreload

Type this at the beginnig of your script 

    %load_ext autoreload
    %autoreload 2
    
Or, if you want to always enable this settings, modify your IPython configuration file ~/.ipython/profile_default/ipython_config.py and append:

    c.InteractiveShellApp.extensions = ['autoreload']     
    c.InteractiveShellApp.exec_lines = ['%autoreload 2']

If you don't find the ~/.ipython/profile_default/ipython_config.py file, create one by typing in the following command in the terminal:

    ipython profile create
