    This is a repo that contains some basic knowledge of ml.

1. how to config jupyter home: https://www.jianshu.com/p/91365f343585

(1)cmd: jupyter notebook --generate-config (Find the config file's path)

Normally, 

Windows：C:\Users\<user_name>\.jupyter\
Linux/macOS: /Users/<user_name>/.jupyter/ or ~/.jupyter/

config file name：jupyter_notebook_config.py

(2)search the ley word "c.NotebookApp.notebook_dir" in jupyter_notebook_config.py

(3)edit and uncomment

2. how to connect to github when the connection is timeout:443

    https://blog.csdn.net/natahew/article/details/81387885