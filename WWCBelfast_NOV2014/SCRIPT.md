--Git-Hub Training

1. Check applications on all PCs a. GitHub account config? (https://github.com/) b. GitHub downloaded? (http://windows.github.com/ or http://mac.github.com/) 2. Fork my repo to your own (https://github.com/SMcCalden/GitHubTraining)

3. Initialising or cloning a Git repo

a. Initialise blank repo…

i. Demo online manual creation of repo

ii. Demo manually initialising a blank repo from MAC command line following on-screen init instructions

b. Clone the repo…

i. Direct clone from the browser demo

ii. Clone request from the GitHub Client demo

c. Create repo from existing files…

i. Generate repo from GitHub Client demo

d. Exercise…

i. Everyone clone the forked training repo from your own GitHub.com https://github.com/SMcCalden/GitHubTraining to a folder of your choice locally

4. Pull Requests

a. Important to keep local repo fresh & up-to-date

b. Regular pulls recommended & 100% before any branch or feature work is begun

c. Manually make a change to a file on the browser

d. Demo the file’s current state locally

e. Execute pull request

f. Confirm the file has updated

g. Exercise…

i. Everyone execute a pull request for your training repo

ii. Confirm the updated file has changed

5. Adding, Editing & Commiting

a. Add

i. Demo adding a new folder

ii. Demo adding a new file within that new folder

b. Editing

i. Demo editing an existing file

c. Committing

i. Demo commit of a file

1. Commit message important!!!

d. NB : Multiple users editing a common file may cause commit/merge problems so best to coordinate yourselves to only edit completely distinct file OR employ feature branching as file.txt can be edited within Branch1 and Branch2 perfectly fine.

e. Exercise…

i. Add a new root folder of your surname

ii. Add a “firstname”.txt file within that have “Hello World!”

iii. Stage all the changes made

iv. Commit all the changes made with unique commit messages

6. Push Requests

a. Demo pushing via command line

i. Explain the branch à branch confirmation

ii. Confirm the push success in the browser online

iii. Confirm the commit messages / files / etc. online

b. Exercise…

i. Push all of your local changes up into the training repo

ii. Confirm the changes online have been pushed successfully

7. Branching

a. Never work directly on the master branch

b. Always employ feature branching

c. Create a branch

i. Demo git checkout -b NEW_BRANCH

ii. Confirm changed to the new branch via git branch

iii. Edit an existing file with a personal & unique change

iv. Stage & commit the change

v. Push the change up to the training repo IN THE NEW BRANCH (*not master*) >> git push NEW_BRANCH

d. Exercise…

i. Create a new branch of your surname

1. NB : You may need to PULL the training repo again to get his/her new folder/file!!! ;-)

ii. Change to the branch

iii. Edit the ../surname/firstname.txt

iv. Stage, commit & push the file back up to the training repo IN YOUR BRANCH!!

v. Confirm via the browser that the master and new branches differ for this specific file

8. Merging

a. Always have merges executed by ANOTHER person – essentially a code review

b. Merge…

i. Demo online how to trigger a merge request

ii. Assign it to another person

iii. Examine the diffs in the merge request

iv. Execute the merge

v. Delete the old branch

c. Exercise…

i. *Probably no time for this but try in your own time to issue a merge request from Branch B into Branch A and confirm the merge is successful & Branch B deleted*

9. Miscellaneous

a. Gitignore

i. File at root level which holds extensions of files NOT to be included within commits

ii. Useful for different project IDEs (NetBeans vs Eclipse)

b. README.md

i. This is an intro file useful as a first port of call for new users

ii. Ideally should contain description, installation, execution info but really anything is possible

iii. Very precise coding standards so “m” to view the syntax available for layouts

iv. Multi-layered README files are good to explain complex nested sections within the code base

c. Stashing

i. This is any idea that a change is made locally but not ready to go up

ii. Stash it locally to exclude from the commit/push and return to later

iii. I’m not a fan as clearly this is an example where featured branching should’ve been employed

d. SSH keys

i. Private github ssh key can be added to the PC

ii. Public github ssh key can be uploaded to GitHub

1. Demo the SSH key location

iii. 2nd secure layer of confirming secure access to the repo e. Git Reference (http://gitref.org/index.html)

i. Online manual of command-line options if you need to automate the git pull, edit, commit process
