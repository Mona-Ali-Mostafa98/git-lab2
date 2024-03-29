## Deleting branch  
  
// Deleting a branch locally.  
git branch -d branch_name.  
  for example : git branch -d test  

If the branch contains changes that are not yet merged, Git will prevent the deletion by default. If you are sure you want to delete the branch regardless of its merge status, you can force the deletion using the -D option:  

  git branch -D branch_name    
 
//---------------------------------------------  
// Deleting a branch REMOTELY  
git push <remote> --delete branch_name.  
For example: git push origin --delete fix/authentication  
  
You can also use this shorter command to delete a branch remotely: git push <remote> :branch_name 

For example: git push origin :test  
//---------------------------------------------  
## Listing Tags    

To list all tags in your Git repository, you can use the following command:    
  
git tag  
  
//---------------------------------------------    
## Deleting Tags  
  
**To delete a tag locally, you can use the following command:  
    
    git tag -d tag_name
    
  **To delete a tag on the remote repository, you need to push the deletion after deleting it locally:  

   git push origin --delete tag_name  
   
//---------------------------------------------    

## Project Image

![Image Alt Text](index.PNG)



  
