# Working as a team

Use the following workflow with the others in your team (the others in this room) to create a collection of poems, quotes and short stories.

## Workflow

1. Copy the clone link from a challenge
- (In the terminal:) git clone \<paste the clone link here\>
- cd \<repository name\>
- git checkout -b sam-changing-things
- Make some changes
- git status (to see what has changed)
- git add \<file name that has changed\>
- git commit -m “a message describing the changes”
- Repeat 5-8 until finished with work
- git checkout master (checkout to the master branch)
- git pull (retrieve any changes from the remote repository)
- git checkout sam-changing-things (checkout back to your branch)
- git merge master (merge any new additions from master into your branch)
- git push origin sam-changing-things (push your change to a branch on the remote)
- Navigate to your branch on the repository on GitHub
- Click on the green “New Pull Request” button
- Ensure master is the base branch and your branch is the compare branch
- Tag the appropriate people and write a concise description about the work you want merged into the master branch
- Click on the “Create Pull Request” button
- Wait for the people you tagged to check your work and merge your pull request.
