# SshKeyGenerated
# how can you create ssh key
by git bash command
1- ssh-keygen -t rsa -b 4096 -C "your github email here"
2- enter password and press enter
3- enter password again and press enter
// now we want computer know the key
4- eval $(ssh-agent -s)
5- ssh-add ~/.ssh/id_rsa
6- enter password
//now we want to clipboard to copy key to github
7-clip < ~/.ssh/id_rsa.pub
8- go to github account , setting , ssh key, then create a new key give it name then past it
in key field.
