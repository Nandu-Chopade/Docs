# This Repository contain the command which will helps the developer use git command so continue.....



Settings → Developer settings → Generate new token.
git remote set-url origin https://[APPLICATION]:[NEW TOKEN]@github.com/[ORGANISATION]/[REPO].git

git remote set-url origin https://Attaywalebaba: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@github.com/TQ-Mech-Tech/Attaywalebaba.git

# APPLICATION MEANS
Repository Name Attaywalebaba 

# ORGANISATION Means
 --> USER Name 
# Repo Means
Name of the Repository.



# Git Commands 

1) git branch 
2) git checkout 
3) git checkout [Branch Name]
4) git add .
5) git commit -m "This is New and first Commit"
6) …or create a new repository on the command line
echo "# sample" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Nandu-Chopade/sample.git
git push -u origin main



# Git Command for merging the branches
if you want to merge feature branch (newly working) in Main or Master Branch then You need run following command.

git merge [feature branch name ] 

after this if get error like :-- 
          fatal: refusing to merge unrelated histories Then Run following command
          git merge [Branch Name] --allow-unrelated-histories
          
          
          #Thank You

