# git-demo

1. Create github account with turing email/ link it to your existing personal account
2. [Generate new ssh key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent#generating-a-new-ssh-key). You can click the [enter] key to skip through when prompted with `> Enter a file in which to save the key ...`, `> Enter passphrase ...`. 
3. [Add ssh key to ssh-agent](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent#adding-your-ssh-key-to-the-ssh-agent)
4. [Link your newly generated ssh key to git account](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account#adding-a-new-ssh-key-to-your-account)
5. Try and clone this repository using ssh.
  - In your terminal, navigate to home directory (`~/`) or wherever you want to save your cloned repository (e.g. `~/Desktop`) by doing `cd ~/Desktop` (`cd` is terminal shell command for 'change directory')
  - You're now ready to git clone!
   ```git clone git@github.com:alan-turing-institute/git-demo.git```
