# git-demo
This is the repository for the live demo on git for SLO-Hacks Lite

## How to use Git

### Clone the repository
1. ``` git clone https://github.com/ctperry0301/git-demo.git ```
2. To test that it is working correctly, navigate to this code and try running it. 


### Making Changes
1. Before you start making changes, ```git pull``` (this will ensure that you have the most up to date version of the code)
2. Create a branch ```git checkout -b <name-of-branch>```
3. Make changes to the code 

### Commiting Changes
1. ```git add .``` (to stage all files) or ```git add <file-name>``` (to stage specific file)
2. ```git commit -m "short descriptive message describing chages"``` 
3. ```git push -u origin <name-of-branch>```

### Making Pull Requests
1. Find the repository on Github
1. Go to the Pull Requests tab
2. Find your Pull Request,
3. If the commited code looks good to you and your team, go ahead and Click on Merge.
4. At this point, your code will be added to the repository, and your team will be able to run your code by pulling changes.
