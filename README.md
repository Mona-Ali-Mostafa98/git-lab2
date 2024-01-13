// Deleting a branch locally.
git branch -d <branch>.
for example : git branch -d test

//---------------------------------------------
// Deleting a branch REMOTELY
git push <remote> --delete <branch>.
For example: git push origin --delete fix/authentication
//****
You can also use this shorter command to delete a branch remotely: git push <remote> :<branch>

For example: git push origin :test
