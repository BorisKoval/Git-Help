# Git-Help
Useful git commands and tips

Initial settings:

git config --global user.name <"John Doe">             |  git config --local user.name <"John Doe">
----
git config --global user.email <johndoe@example.com>  |  git config --local user.email <johndoe@example.com>
----
_________________________________________

git init
----
git add | git add -A
----
git commit -m <"Initial commit">
----

___________________________________________


git remote add origin \<URL\> -- Add remote repository
----
git push origin master               -- Push your branch to Github
----
git remote -v                        -- Get all remote repositories
----
git remote rm destination            -- Delete all remote repositories
----
git push \<repository name\> \<branch\>  -- Send changes to remote server
---
git push \<origin\> \<master\>              

  
git clone https://<'login'>:<'pass'>@github.com/<'login'>/<'project'>.git -- Private repository copying
---
git status / git show   --- Show some git changes
---
https://htmlacademy.ru/blog/useful/git/how-to-squash-commits-and-why-it-is-needed --- Squash commits help
---

git reset --soft HEAD~1           --Undo last commit (Note the --soft flag: this makes sure that the changes in undone revisions are preserved. If you don't want to keep these changes, simply use the --hard flag)
---- 
