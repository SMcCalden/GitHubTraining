#Git-Hub Training

##Prep
1. Check applications on all PCs a. GitHub account config? (https://github.com/) b. GitHub downloaded? (http://windows.github.com/ or http://mac.github.com/) 
2. Fork my repo to your own (https://github.com/SMcCalden/GitHubTraining)

##Initialising or cloning a Git repo
1. Initialise blank repo…
  - Demo online manual creation of repo
  - Demo manually initialising a blank repo from MAC command line following on-screen init instructions
2. Clone the repo…
  - Direct clone from the browser demo
  - Clone request from the GitHub Client demo
```
git clone FULL_REPO_URL
```
3. Create repo from existing files…
  - Generate repo from GitHub Client demo
###Exercise…
* Everyone clone the forked training repo from your own GitHub.com https://github.com/SMcCalden/GitHubTraining to a folder of your choice locally

##Pull Requests
1. Important to keep local repo fresh & up-to-date
  - Regular pulls recommended & 100% before any branch or feature work is begun
2. Manually make a change to a file on the browser
3. Demo the file’s current state locally
4. Execute pull request
```
git pull
```
5. Confirm the file has updated
###Exercise…
- Everyone execute a pull request for your training repo
- Confirm the updated file has changed

##Adding, Editing & Commiting
1. Add
  - Demo adding a new folder
  - Demo adding a new file within that new folder
2. Editing
  - Demo editing an existing file
3. Committing
  - Demo commit of a file
  - <i>Commit message important!!!</i>
  - <b>NB : Multiple users editing a common file may cause commit/merge problems so best to coordinate yourselves to only edit completely distinct file OR employ feature branching as file.txt can be edited within Branch1 and Branch2 perfectly fine.</b>
```
git add *
git commit -m "COMMIT MESSAGE HERE"
```
###Exercise…
- Add a new root folder of your surname
- Add a “firstname”.txt file within that have “Hello World!”
- Stage all the changes made
- Commit all the changes made with unique commit messages

##Push Requests
1. Demo pushing via command line
```
git push 
```
2. Explain the branch à branch confirmation
3. Confirm the push success in the browser online
  - Confirm the commit messages / files / etc. online
###Exercise…
- Push all of your local changes up into the training repo
- Confirm the changes online have been pushed successfully

##Branching
1. Never work directly on the master branch
2. Always employ feature branching
3. Create a branch
```
git checkout -b NEW_BRANCH
```
  - Confirm changed to the new branch via git branch
4. Edit an existing file with a personal & unique change
5. Stage & commit the change
6. Push the change up to the training repo IN THE NEW BRANCH (*not master*) >> git push NEW_BRANCH
```
git push ORIGIN NEW_BRANCH_NAME
```
###Exercise…
- Create a new branch of your surname
  - <i>NB : You may need to PULL the training repo again to get his/her new folder/file!!! ;-)</i>
- Change to the branch
- Edit the ../surname/firstname.txt
- Stage, commit & push the file back up to the training repo IN YOUR BRANCH!!
- Confirm via the browser that the master and new branches differ for this specific file

##Merging
1. Always have merges executed by ANOTHER person – essentially a code review
2. Merge…
3. Demo online how to trigger a merge request
4. Assign it to another person
5. Examine the diffs in the merge request
6. Execute the merge
7. Delete the old branch
###Exercise…
- Probably no time for this but try in your own time to issue a merge request from Branch B into Branch A and confirm the merge is successful & Branch B deleted
