# How to connect GitHub from local PC
## created ssh key first
   - Make sure you have git bash installed on windows pc
   - https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent
   - ssh-keygen -t ed25519 -C "your_email@example.com"
   - you will get two files in your c:\{UserName}\.ssh folder
   - open pub file and copy the contents


## Add your public key to Github.com
   - Login into your github.com
   - create a repository
   - Navigate to https://github.com/settings/keys
   - Click SSH and GPG keys from left
   - Add your ssh key (copied in previous step)

## Test your ssh connection
   - ssh -T git@github.com
   - https://docs.github.com/en/authentication/connecting-to-github-with-ssh/testing-your-ssh-connection

## Configure VSCODE for git
   - git config user.email wingsphp@gmail.com
   - git config user.name wingsphp
   - git clone <your repository>

   

