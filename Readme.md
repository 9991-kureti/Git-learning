#Git learning process for begginers
first make a folder
ex:git-practice
cd git-practice
"touch Readme.md"

and then

"git init"
"git add ."
"git commit -m "first commit"

We need to configure our github account

"git config --global user.name "github user name"
"git config --global user.mail "emailid"

and then, we need to add local repo to our Github repo. otherwise we are unable to push the changes to Github.

for that need to create repo on github account.Then after there is link is available ex:"https://github.com/9991-kureti/Git-learning.git".

after this

"git remote add origin "https://github.com/9991-kureti/Git-learning.git"

then

by defalut branch name is "master" but latest versions Git is following be default is "main"

so change the name to from "master to main"

"git branch -M main"

then

"git push -u origin main"


