Git Assignment – Part 2
Prepared by: Harshul Nihalani

Overview
This project demonstrates a complete collaborative Git workflow, simulated by a single user (Harshul) using multiple GitHub accounts. The exercise covers key concepts such as repository setup, collaboration, commits, pushing/pulling, merge conflicts, and conflict resolution — mimicking a real-world team development environment.

Activities Practiced
1. Repository Creation
A public GitHub repository was created:
 https://github.com/arcgate-harshul/harshul

2. Initial Setup
Created local folder and linked it to the GitHub repository using git remote add origin.

Initial commit and push done using:

bash
Copy
Edit
git add .
git commit -m "Initial commit"
git push -u origin main

3. Simulated Collaboration
Added other GitHub users (my own alternate accounts) as collaborators.

Cloned the repository using other accounts to simulate teamwork.

4. Commit Workflow
Made changes from multiple user terminals.

Added and committed new files.

Verified updates using git log.

Pulled and pushed changes across accounts to test real-time synchronization.

5. Push Conflicts
Simulated a scenario where two users raced to push changes.

Observed how the first pusher succeeds, while the other receives a rejection error.

Used git pull and merge to resolve conflicts.

6. Merge Conflict Resolution
Created conflicting changes in the same line from different accounts.

Simulated Git’s auto-detection of conflicts.

Manually resolved the conflict and committed the merge.

Key Learnings
Git tracks commits with unique SHA-1 IDs — the same across all clones for identical commits.

Real-time collaboration depends on pulling before pushing to avoid sync issues.

Merge conflicts are a normal part of collaborative development, and Git provides powerful tools to resolve them

