## Creating a feature branch

* Checkout `master` branch
* Pull any changes
* checkout your feature branch `git checkout -b turtle-model`
* Commit some code

### Handling updates on master

* checkout the `master` branch
* pull any changes from github that someone else made
* checkout my feature branch
* `git merge master`

### Getting your feature onto master

#### Pull Request

* The way you should do it
* ask a mentor if you need help
* it's a github thing not a git thing

#### merge straight onto master

* Not recommended
* a little easier
* `git checkout master`
* `git merge --no-ff feature`
* `git push`

After your feature is merged, there is NO reason for you to keep your feature branch. Delete the branch

Safe:
`git branch -d turtle-model`

Will make sure you've merged the code before deleting.

Dangerous:
`git branch -D turtle-model`