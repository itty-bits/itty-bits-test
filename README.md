Initial setup of git repository
-------------------------------------
md itty-bits-test  
cd itty-bits-test  
touch README.md  
git init  
git add README.md  
git config --global user.email "i...m.....@r........"  
git config --global user.name "Ian MacRae"  
git commit -m "first commit"  
git remote add origin https://github.com/itty-bits/itty-bits-test.git  
git push -u origin master  

Update
-------------------------------------
git add README.md  
git commit -m "update README"  
git push origin master  

git config --global push.default simple  
git config --global credential.helper store  

Testing update w/o prompting
----------------------------
git clone https://github.com/itty-bits/itty-bits-test.git  
git commit -a -m "test update w timestamp"  
git status  
	# On branch master  
	# Your branch is ahead of 'origin/master' by 1 commit.  
	#  
	nothing to commit, working directory clean  
git push origin master  

