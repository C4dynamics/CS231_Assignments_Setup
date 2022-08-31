# CS231_Assignments_Setup

How did I run Assignment1 in Stanford's Computer Vision CS231n? 

Windows users who work on vs code and encounter errors while trying to install requirements.txt can do the following:

Install Ubuntu with WSL (cmd: wsl --install)
https://docs.microsoft.com/en-us/windows/wsl/install .

Make a new folder named ‘projects’ in the user folder: \\wsl$\Ubuntu\home\USERNAME\projects\ (USERNAME is the user name you entered when installed the wsl).

Store the file in the link in the projects folder.
https://github.com/tsipor/CS231_Assignments_Setup/blob/main/requirements.txt

Extract the zip file assignment1.zip in the projects folder (notice to take the jupyter version).
https://github.com/cs231n/cs231n.github.io/tree/master/assignments/2020

Open vs code in remote mode connected to wsl (press on the bottom left green box or enter ‘code .’ in the terminal)

Open the terminal.

Install pyenv (link to a procedure, scroll to Linux).
https://k0nze.dev/posts/install-pyenv-venv-vscode/

Install python version 3.7.13: pyenv install 3.7.13

Restart (or just reload the window, ctrl+R)

Make it the global version: pyenv global 3.7.13

In the terminal, navigate to the projects folder: cd projects

run: pip install -r requirements.txt (may take some time). 

Restart (ctrl+R) 

Navigate to the assignment folder: cd assignment1

Navigate to datasets: cd cs231n/datasets, and download the CIFAR-10 dataset: sudo ./get_datasets.sh 

Open vs code in the assignment1 folder, open knn.ipynb, and continue according to the instructions in the notebook.

https://www.youtube.com/playlist?list=PLf7L7Kg8_FNxHATtLwDceyh72QQL9pvpQ






