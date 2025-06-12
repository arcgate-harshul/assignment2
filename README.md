Git Assignment part 2

This project documents my learning journey using Git and GitHub for version control and team collaboration. It covers setting up a repository, working with remotes, cloning, pushing and pulling changes, and handling merge conflicts in a group of 2–4 people.


opics Covered

- Initializing and connecting to a remote repository
- Cloning a repository
- Pulling and pushing changes (origin main)
- Collaborating as a team
- Detecting and resolving merge conflicts



Setting Up a Git Repository

Initialize a local Git repo:

bash
git init
Add a remote repository:
git remote add origin https://github.com/username/repo-name.git
Rename the default branch to main (if needed):
git branch -M main
Push the initial commit to the remote repository:
git push -u origin main

2. Cloning the Repository
Team members can clone the repository with:
git clone https://github.com/username/repo-name.git
This creates a local copy and automatically sets the origin remote.

3. Pulling and Pushing Changes
Pulling Latest Changes from Remote:
To get the latest changes from the main branch, run:
git pull origin main
Making Changes and Pushing to Remote:
    1. Stage the changes:
       git add .
    2. Commit the changes with a message:
       git commit -m "Description of changes"
    3. Push the changes to the remote:
       git push origin main

4 Collaborating as a Team
    1. Each team member clones the repository.
    2. Everyone works on separate files or features to minimize conflicts.
    3. Frequently run:
       git pull origin main
       ...to keep your local repository up-to-date with others.
    4. Push your updates with:
       git push origin main

5 Handling Merge Conflicts
Merge conflicts occur when multiple people edit the same line or section of a file. When you pull from the remote repository, Git will try to merge the changes, and if there’s a conflict, it will notify you:
CONFLICT (content): Merge conflict in <filename>
Resolving Conflicts:
    1. Open the conflicting file. Git will show conflict markers:
       <<<<<<< HEAD
       Your local changes
       =======
       Changes from the remote repository
       >>>>>>> origin/main
    2. Manually edit the file to keep the correct version (or combine changes if necessary).
    3. After resolving the conflict:
       git add <filename>
       git commit -m "Resolved merge conflict in <filename>"
       git push origin main

 Project Structure
/git-learning-project/
├── README.md
├── git.pdf
├── 
└── 

   Summary
    • Initialized and connected a remote repository
    • Cloned a repository to local machines
    • Worked as a team by frequently pulling and pushing changes
    • Detected and resolved merge conflicts
    • Gained a deeper understanding of Git workflows

 Contributors
    • Your Name (@arcgate-harshul)
    • @arcgate-gaurav
    • @harshul101
