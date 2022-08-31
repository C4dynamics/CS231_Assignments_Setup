# CS231_Assignments_Setup

How did I run Assignment1 in Stanford's Computer Vision CS231n? 
Stanford Computer Vision
 
Windows users who encounter errors when trying to install requirements.txt can do the following:
 
Isntall ubuntu with wsl (cmd: wsl –install) https://docs.microsoft.com/en-us/windows/wsl/install .
Make new folder named ‘projectes’ in the user folder: \\ wsl$\Ubuntu\home\USERNAME\projects\
Extract the assignment1 folder in the new folder (notice to take the jupyter version). https://github.com/cs231n/cs231n.github.io/tree/master/assignments/2020

Open vs code in remote mode connected to wsl (terminal: ‘code .’) 

Install pyenv (link to procedure. scroll to linux) . https://k0nze.dev/posts/install-pyenv-venv-vscode/

Pyenv install 3.7.13
Install the following file (pip install -r requirements.txt) - may take some time.
Reload vs code. 
Go to cd \cs\cla: 
Run sudo .\*.sh
Open ipp.ivnpy
Continue according to the instructions in the page. 

Leave commnet for any error. 
