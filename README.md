## Adding a gist to a repository using git submodule
### Command:
`git submodule add [Gist URL] [Some directory name that is easy to remember]`
### Example: 
`git submodule add https://gist.github.com/dcoleman21/9f844f1eb1325398eb1c34ecfdbc9e48 understanding_case_statements`
### Add, commit and push to repo
```ruby
git add .
git commit "Add case statements gist to repo"
git branch -M main (to change branch from Master to Main)
git push --set-upstream origin main
```
### Clone all gists
Use `--recurse-submodules` option to clone all submodule managed files
#### Example:
`git clone --recurse-submodules https://github.com/dcoleman21/cheatsheet`

**NOTE**: this will clone every submodule in the repo

[credit from](https://gist.github.com/YumaInaura/7a82df5a1dfe3bf90575191ea1ceee5a)
