ssh-keygen -t rsa -C "e@email.com"
touch config
>>>
Host github-xinzhanguo
 HostName github.com
 User git
 IdentityFile ~/.ssh/id02_rsa
