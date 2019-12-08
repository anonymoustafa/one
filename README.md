### what i learned about using git?
how to host gh-pages on an orphan branch? <br>
`git checkout --orphan orphan_name` <br>
how to delete a branch locally and remotely?
1. remotely: <br> `git push -d <remote_name> <branch_name>`
2. locally: <br> `git branch -d <branch_name>`

*please be noted: you can delete a specific branch, __if and only if__ you are on another branch!*  