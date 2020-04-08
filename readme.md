install git

create git repo
get remote link : eg . https://github.com/ashish-cora/test.git

//(initilaize git repo) only first time if .git file not exist
git init 

// link your folder to remote git repo
git remote add origin https://github.com/ashish-cora/test.git 


git add { . / folder_name / filename} 

git commit -m "message here"

//update repo with your commited files
git push origin master

//update your foler with repo
git pull origin master
