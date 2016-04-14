# This is a method for git beginner who wants to upload code to his own github on Mac OS.
# First, we should login our github and establish a repository on our account. I think this process can be ignored because we can find on the offical website https//github.com
# Warning, we should check the initialize this repository with a README, when we establish a new respository.
# Installing Git (without mac users)
# Getting into the current folder that you want to operate and upload the codes
# ssh-keygen -t rsa -C "your_email@youremail.com"
# click enter, ssh key will be produced and saved in the file id_rsa
# click enter, which represent that we cannot set the password
# Then, we should login the website of github https://github.com, click Account Settings, choose SSH Keys, Add SSH Key
# testing the success. 
# ssh -T git@github.com
# click enter, if we see the hint  You've successfully authenticated, but GitHub does not provide shell access,  we can connect to the github successfully.
# git config --global user.name "your name"
# git config --global user.email "your_email@youremail.com"
# we can clone the exist repository to the localization.
# git clone https://github.com/your_account/your_repository.git
# Then, upload README.md
# git init
# touch README.md
# git add README.md
# git commit -m 'first_commit'
# git remote add origin https://github.com/your_account/your_repository.git
# git push origin master
# if we see the warnings: fatal: remote origin already exists
# we should execute the following command
# git remote rm origin
# then execute the command: git remote add origin https://github.com/your_account/your_repository.git
# git push origin master
# if we see the error: failed to push som refs to ......
# then we execute the following command
# git pull origin master




