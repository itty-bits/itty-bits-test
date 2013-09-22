Initial setup of git repository
-------------------------------------
md itty-bits-test

cd itty-bits-test

touch README.md

git init

git add README.md

git config --global user.email "ian.macrae@rogers.com"

git config --global user.name "Ian MacRae"

git commit -m "first commit"

git remote add origin https://github.com/itty-bits/itty-bits-test.git

git push -u origin master

Update
-------------------------------------
git add README.md

git commit -m "update README"

git push origin master

