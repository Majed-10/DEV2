# DEV2

# Set Up the Repository
bash
git init task-manager
cd task-manager

# for create file 
touch tasks.txt

#. Add Initial Tasks
echo " Learn Git basics" > tasks.txt
echo "Set up Git repository" >> tasks.txt

# Create and switch to a new branch

echo "- Practice Git branching" >> tasks.txt
git add tasks.txt
git commit -m "Add practice Git branching task"


# for remove Task

git checkout -b feature/remove-tasks

# here Fast-forward
git checkout master
git merge feature/add-tasks
git merge feature/remove-tasks


# Set Up the Repository
bash
git init task-manager
cd task-manager

# for create file 
touch tasks.txt

#. Add Initial Tasks
echo " Learn Git basics" > tasks.txt
echo "Set up Git repository" >> tasks.txt

# Create and switch to a new branch

echo "- Practice Git branching" >> tasks.txt
git add tasks.txt
git commit -m "Add practice Git branching task"


# for remove Task

git checkout -b feature/remove-tasks

# here Fast-forward
git checkout master
git merge feature/add-tasks
git merge feature/remove-tasks





# commit that undoes the changes
git revert HEAD


# Remote Repository

git remote add origin https://github.com/Majed-10/Dev2
git push -u origin master












# Remote Repository

git remote add origin https://github.com/Majed-10/Dev2
git push -u origin master
