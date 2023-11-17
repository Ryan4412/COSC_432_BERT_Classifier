# COSC_432_BERT_Classifier
**Step 1: Installing Miniconda**    
Miniconda is a package handeler that allows you to create a mini virtual enviornmant to run applications in and can be helpful for keeping project dependencies separate from your physical device and ensure that you will not ruin other projects that you have by downloading an out-dated dependency.    
https://www.youtube.com/watch?v=P6eGTN9QN2Q    
this video is a helpful guide to follow to get started with Miniconda. Once you have created a conda enviormnet like how the video shows you can move on to the next step which is setting up dependencies for your conda enviornment.    

**Step2: Installing python and pip**    
You will need to have Python and pip installed on your device in order to get the python packages required to run the program. pip the package manager for python. If you have ever used Javascript and used npm this should be a familiar concept for you.    
https://www.python.org/downloads/      
Use this link to get python on your device.    
https://pip.pypa.io/en/stable/installation/    
This is a short guide you can follow for installing pip on your device.        
https://www.youtube.com/watch?v=fJKdIf11GcI    
This video is a helpful guide for installing pip on windows.    

**Step 3: downloading dependencies**    
once you have pip installed and you have entered your conda enviornment you can begin downloading the dependencies required for the program.   
![image](https://github.com/Ryan4412/COSC_432_BERT_Classifier/assets/103439799/9157cb25-8c38-4690-acd0-38a32c7e2b46)   
the following is a list of commands you can paste into your terminal to download all dependencies required:   
  
pip3 install torch     
pip install pandas    
pip install transformers   
pip install numpy   
pip install scikit-learn    
pip install ipykernel     
pip install matplotlib     
pip install tqdm    

**Step 4: Selecting kernel on vscode**     
Once you have all dependencies installed, the last step is to select the kernel you would like to use to run the program. Open COSC_432_BERT_Classifier.ipynb file in vscode and in the top right you will see the select kernel button.     
![image](https://github.com/Ryan4412/COSC_432_BERT_Classifier/assets/103439799/6e3ce1ad-0471-4899-8b1d-bc965b8b6e18)     
Click on it and select "Python Enviornments..." in the dropdown and then select the conda enviornment you just created. once it loads you will be ready to run the code.

