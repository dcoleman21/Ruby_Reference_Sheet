## Adding a gist to a repository using git submodule
#### Command:
`git submodule add [Gist URL] [Some directory name that is easy to remember]`
#### Example: 
`git submodule add https://gist.github.com/dcoleman21/9f844f1eb1325398eb1c34ecfdbc9e48 understanding_case_statements`
#### Add, commit and push to repo
```ruby
git add .
git commit "Add case statements gist to repo"
git branch -M main (to change branch from Master to Main)
git push --set-upstream origin main
```
#### Clone all gists
`git clone --recurse-submodules https://github.com/[User_Name/cheatsheet`
NOTE: this will clone every submodule in the repo
