# git_workshop

# To create a new repository on the command line
echo "# any_name_without_space" >> README.md

git init
//git add README.md

git commit -m "first commit"

git remote add origin https://github.com/ani37(username)/git_workshop.git

git push -u origin master

# or push an existing repository from the command line

git remote add origin https://github.com/ani37/git_workshop.git

git push -u origin master
.
.
.
# TO set Proxy in nits lan :

1) git config --global https.proxy http://172.16.30.20:8080
2)  git config --global http.proxy http://172.16.30.20:8080


# to set account's default identity

git config --global user.email "you@example.com"

git config --global user.name "Your Name"

# To check status 

git status

# commit

git commit -m "first commit"

# to add

git add *
.
.
# other commands

git log : to show logs

git branch : to show branches

git branch test(name): to create branch

git checkout test(name):to switch to other branch


