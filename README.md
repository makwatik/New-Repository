# New-Repository
# Repository exercise 
# Learning git
git clone https://github.com/makwatik/New-Repository
#
git add hello.txt
git commit -m "Added hello.txt"
git push origin main
#
git branch feature-branch
git checkout feature-branch
echo "New feature" >> feature.txt
git add feature.txt
git commit -m "Added a new feature"
# git push origin feature-branch