### Creating branch and pushing to branch
1. git clone <repo>
2. git pull
3. Createnew branch `git checkout -b "<branchname>"`
4. `git branch`: to check branch. will give result: `*"<branchname>" and master`
5. Command line: Create a folder :`mkdir raw_data` under your branch 
6. On command  type `echo “raw_data/“ >> .gitignore` (include files or folders that you dont what to push)
7. Command line:`start .gitignore - u `will see the file name in it 
8. Touch new Fil to test your branch 
9. Usual commands for pushing into branch 
  
  `git add .`
  
  `git commit -m "<update message>"`
  
  `git push origin <branchname>`
 
10. Do git pull everytime before anything else