# githubCommand
<br/>
<h1>git config</h1>
1. git config command - git config user.name "khairul2007"
<br/>
2. git config email command - git config user.email "khairul@gmail.com"
<br/>
<h1>git clone</h1>
1. git clone - git clone URL address such as - git clone https://github.com/khairul2007/react.git
<br/>
2. git status - display the state of the code - git status
<br/>
3. see normal files - ls 
<br/>
4. see hides file/all files - ls -a 
<br/>
5. git add specific file - git add file name such as - git add index.html
<br />
6. git add all files - git add .
<br/>
7. git commit - git commit -m "some message"
<br/>
8. git push - git push origin main
<br/>
<h1>local file to github</h1>
<br />
1. crate new git repository - git init 
<br/> 
2. git remote add - git remote add origin link - git remote add origin https://github.com/khairul2007/react.git 
<br />
3. git remote check - git remote -v
<br />
<h1> git branch code</h1>
4. git branch - git branch 
<br/>
5. git reanme branch - git branch -M branch name such as - git branch -M main 
<br />
 6. git push - git push origin main
<br />
7. git push upstream - git push -u origin main 
<br />
8. new git branch - git checkout -b branch name - git checkout -b feature1 
<br />
git branch navigate - git checkout branch name - git checkout feature1 
<br />
9. git branch delete - git checkout -d branch name - git checkout -d feature1 
<br />
10. git push on branch - git push origin branch name - git push origin feature1 
<br />
<h1> git marge code </h1>
<br />
1. git compare commits, beach, files and more - git diff branch name - git diff main 
<br />
2. git marge - git marge branch name - git marge main 
<br />
3. git pull request - git pull origin main 
<br />
<h1> marge conficts</h1>
1. using pull request - git pull origin main 
2. git marge - git marge 
<br />
<h1>undoing changes</h1>
<br />
1. stages changes for one file- git reset file name - git reset index.html 
<br />
2. stage changes for many files - git reset add . 
<br />
3. commited changes (for 1 commit ) - git reset HEAD~1
<br />
4. commited changes (for many commites)- git reset <-commit hash-> - find git commit hash in git log - git reset 5fab707a390f04db0395ec281e0169ec86c07645
<br />
5. commited changes (for many commites) in vs code - git reset --hard 5fab707a390f04db0395ec281e0169ec86c07645
<br />
<h1> fork</h1>
 <br />
1. github project rough copy - goto github -find porject - select frok - fork situated between star and watch
 <br />
2. write and modified code and then crate pull request 


