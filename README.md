# git
Install and configure git version 2.9.5 on RHEL machine .
You can change the variabled and workplace which is the destination acc to your will .
After installation generate the SSH keys and add them to your public/private repository on GITHUB.
Then follow these commands to push your code from the local git server to GITHUB .
-- ssh -T git@github.com
-- git init
-- git remote add origin git@github.com:profilename/--githublink--
-- git pull orgin master 
-- git add your_repos_name
-- git commit -m "your_repos_name"
-- git push orgin master
