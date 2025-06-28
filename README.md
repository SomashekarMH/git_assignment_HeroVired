Q1

# git_assignment_HeroVired
Graded Assignment : Git &amp;amp; Github
git init git_assignment_HeroVired
cd git_assignment_HeroVired
git checkout -b dev
git add .
git commit -m "First calculator operations in dev branch"
git checkout main
git merge dev
git tag v1.0
git push origin --tags
git checkout -b feature/sqrt
# Uncomment and implement:
def square_root(self, x):
    return math.sqrt(x)
    git checkout dev
# Fix divide method:
def divide(self, a, b):
    if b == 0:
        raise ValueError("Cannot divide by zero.")
    return a / b
git commit -am "Fix division by zero bug"
git checkout feature/sqrt
git merge dev
git checkout dev
git merge feature/sqrt
git checkout main
git merge dev
git tag v2.0


===========================
Q2.
git lfs install
git checkout -b lfs
git lfs track "*.zip"
echo "*.zip" >> .gitattributes
git add .gitattributes
cp /path/to/large/file.zip .
git add file.zip
git commit -m "Add large file using Git LFS"
git push origin lfs
git clone https://github.com/your-username/git_assignment_HeroVired.git
git checkout lfs
git lfs pull

========================================================================================

Q3.

git checkout -b geometry-calculator
git checkout -b feature/circle-area
# Add circle code
git stash
git checkout -b feature/rectangle-area
# Add rectangle code
git stash
git checkout feature/circle-area
git stash pop
git add .
git commit -m "Implement circle area calculation"
git push origin feature/circle-area
git checkout feature/rectangle-area
git stash pop
git add .
git commit -m "Implement rectangle area calculation"
git push origin feature/rectangle-area
git checkout main
git merge dev
git tag v3.0


