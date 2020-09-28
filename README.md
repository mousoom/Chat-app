
## Available Scripts

Clone the Project :`https://github.com/mousoom/Chat-app.git`

In the project directory, you run:

#### `npm install`

Install the dependencies in the local node_modules folder

#### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Git Workflow that we will use 

#### `git pull` 

It updates the local version of a repository from a remote.

#### `git branch`

List all of the branches in your repository.

#### `git branch yourBranchName`

Creates a branch.

#### `git checkout yourBranchName`

Lets you navigate between the branches created by git branch.

#### `git status`

Lets you see which changes have been staged, which haven't, and which files aren't being tracked by Git.

#### `git add .`

Adding several files to the staging area in one go.

#### `git commit -m " your message here "`

Immediately creates a commit with a passed commit message. 

#### `git push`

Uploads local repository content to a remote repository.

## Deleting Branch

#### `git branch -d yourBranchName`

Delete the specified branch locally. This is a “safe” operation in that Git prevents you from deleting the branch if it has unmerged changes.

#### `git push origin --delete yourBranchName`

This will push a delete signal to the remote origin repository that triggers a delete of the remote.
