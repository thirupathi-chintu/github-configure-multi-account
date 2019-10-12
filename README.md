# github-configure-multi-account



# Work GitHub account

# go to .ssh ==> open config file. Add the below to configure the git pofile. (jenit = newly created sshprivate)

# Put the public key on the github, 

Host work.github.com

HostName github.com

PreferredAuthentications publickey

IdentityFile ~/.ssh/jenit

# Pulling  a repository

git clone git@work.github.com:it-incloud/tr-terraform.git

# Pushing to a repo

git remote add origin-push git@work.github.com:it-incloud/tr-terraform.git

git push origin-push BRANCH-NAME

