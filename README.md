# LAB:
# SEQUENCE-1
# Python and ML libraries in Windows platform 
----------------------------------------------------------------------------------------------------------------------------------------------------
1. Go to the following link:

https://www.python.org/downloads/release/python-3112/


2. Download and install the following python installer for 64-bit windows ( at the bottom of the page):
Windows installer (64-bit)


Install it in admin mode (right click and run as administrator). Click on Add Python 3.11 to PATH checkbox to set up path or environment variable.


3. Restart your windows once the setup is done.


4. Check the Python Version [Python 3.11.2] with the following command in cmd
>python --version

If the above command print the python version then your set up is completed.


5. Set environment variables (If not set in STEP 2. That means, if Add Python 3.11.2 to PATH checkbox were unchecked)
Go to the startup panel of the windows. Then type "system environment variable" and open up the system properties panel. Click environment variables
Then set the following two lines if not already set.


C:\Users\Admin\AppData\Local\Programs\Python\Python311\Scripts\
C:\Users\Admin\AppData\Local\Programs\Python\Python311\

 
6. Check the Python Version [Python 3.11.2] with the following command in cmd
>python --version

7. Now install Jupyter notebook using the following command:

pip install jupyterlab
It will install Jupyter notebook with all dependencies.

8. You can install any python machine learning libraries using the pip command. For example:
pip install pandas
pip install keras
pip install scikit-learn
9. If you want to use any IDE, then download and install the pycharm community edition
https://www.jetbrains.com/pycharm/

You can also download and install vscode instead of PyCharm
https://code.visualstudio.com/download

10. To open Jupyter notebook, run the following command:

Finally, you are ready to explore a new world