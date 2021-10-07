
# html_study
Personal study of HTML
### basic git info
-Macbook Version 
“git pull origin (branch name)” - Bring the most updated file from github that you can work on. MUST DO FIRST

"clear" - Get rid of everything in the terminal and prepares a blank space

“git init”     .git

“git remote add origin (address)” 

“git remote -v”  - Tells where the git is connected to 

“git status” - Checks for any new updates to the git file

“git add . “ - File add and saves the file

“git commit -m “(title)”” 

“git push origin (branch name)” - Adds the newest updates to the original file on GitHub.com

“git config —global user.name (git id) ” - Connects everything to the typed id
“git config —global user.email (git email)” - Connects everything to the typed email
*If parentheses section is ommitted, the current id that is logged in will show. Same with email.
    If the parantheses section is ommitted, it will tell you which git id is connected.
    If the parantheses section is ommitted, it will tell you which git email is connected.

"git branch" - Tells which branches you have connected to this file
"git checkout (branch name)" - Changes to the specified branch name

-The difference between Mac version and Windows version
I was unable to save and update my git onto github because the default setting for Mac and Windows is different. 
Mac has the default branch - main
Windows has the default branch - master`

-for gitignore
1. git rm -r  --cached (file name folder name)
    1-1. git rm -r --cahced . (. = all)
2. git add .
3. git commit -m "(title)"
4. git push origin (branch name)