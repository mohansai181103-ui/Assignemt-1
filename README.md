this is my Assignment-2








PS C:\Users\mohan\OneDrive\Desktop\Git Practice\Assignment-1> git status
On branch master
nothing to commit, working tree clean
PS C:\Users\mohan\OneDrive\Desktop\Git Practice\Assignment-1> git add .  
PS C:\Users\mohan\OneDrive\Desktop\Git Practice\Assignment-1> git log --oneline
dec7e51 (HEAD -> master) Third Commit
a6b23d0 Second Commit
e7e8860 First Coomit
PS C:\Users\mohan\OneDrive\Desktop\Git Practice\Assignment-1> git remote add origin https://github.com/mohansai181103-ui/Assignemt-1.git
PS C:\Users\mohan\OneDrive\Desktop\Git Practice\Assignment-1> git remote -v
origin  https://github.com/mohansai181103-ui/Assignemt-1.git (fetch)
origin  https://github.com/mohansai181103-ui/Assignemt-1.git (push)
PS C:\Users\mohan\OneDrive\Desktop\Git Practice\Assignment-1> git push origin master
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 16 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (9/9), 879 bytes | 219.00 KiB/s, done.
Total 9 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), done.
To https://github.com/mohansai181103-ui/Assignemt-1.git
 * [new branch]      master -> master
PS C:\Users\mohan\OneDrive\Desktop\Git Practice\Assignment-1> git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.txt

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\mohan\OneDrive\Desktop\Git Practice\Assignment-1> git add .
PS C:\Users\mohan\OneDrive\Desktop\Git Practice\Assignment-1> git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   index.txt

PS C:\Users\mohan\OneDrive\Desktop\Git Practice\Assignment-1> git commit -m 'This is the text file'
[master 7259cc0] This is the text file
 1 file changed, 1 insertion(+)
 create mode 100644 index.txt
PS C:\Users\mohan\OneDrive\Desktop\Git Practice\Assignment-1> git log --oneline
7259cc0 (HEAD -> master) This is the text file
dec7e51 (origin/master) Third Commit
a6b23d0 Second Commit
e7e8860 First Coomit
PS C:\Users\mohan\OneDrive\Desktop\Git Practice\Assignment-1> git log --oneline
7259cc0 (HEAD -> master) This is the text file
dec7e51 (origin/master) Third Commit
a6b23d0 Second Commit
e7e8860 First Coomit
PS C:\Users\mohan\OneDrive\Desktop\Git Practice\Assignment-1> 
 *  History restored 

PS C:\Users\mohan\OneDrive\Desktop\Git Practice\Assignment-1> git add .
PS C:\Users\mohan\OneDrive\Desktop\Git Practice\Assignment-1> git status
On branch master
nothing to commit, working tree clean
PS C:\Users\mohan\OneDrive\Desktop\Git Practice\Assignment-1> git log --oneline
7259cc0 (HEAD -> master) This is the text file
dec7e51 (origin/master) Third Commit
a6b23d0 Second Commit
e7e8860 First Coomit
PS C:\Users\mohan\OneDrive\Desktop\Git Practice\Assignment-1> 
