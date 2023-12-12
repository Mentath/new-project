mkdir new-project  
cd new-project  
git init  
echo "init" > README.md  
git add README.md  
git commit -m "init"
git branch -M main 
git checkout -b development
nano README.md
git add README.md
git commit -m "Add instructions to the README.md"
git checkout main
git merge development
git remote add origin https://github.com/Mentath/new-project.git
git push --all
