# Practical2

 -Create a branch from the master branch and make changes and commit changes

- Create a new branch from the master.

- Create a pull request for the first branch and merge it to the master.

- Rebase the second branch with the master branch and make changes in the second branch and commit changes.

      git init
    
      touch .gitignore

      git status

      git add .

      git commit -m "Initial commit -M"
      
      git remote add origin git@github.com:hinal-pachori-18/Practical2.git

      git remote -v
    
      git push -u origin master

      git checkout -b firstbranch

      git status
  
      git add .
      
      git commit -m "firstbranch -branch1added"
      
      git checkout master
      
      git checkout firstbranch
      
      git push origin firstbranch
      
       git checkout master

      git checkout -b secondbranch.
      
      git branch
          firstbranch
          master
          *secondbranch
        
        
       git checkout master
        
       git pull
        
       git checkout secondbranch
        
       git rebase master
            Successfully rebased and updated refs/heads/secondbranch.
            
       git status
       
       git add .
       
       git commit -m "secondbranch -branch2 added"
       
       git checkout master.
       



       



        




    
