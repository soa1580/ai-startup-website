# ai-startup-website
## This is my first repository as a DevOps Engineer

PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website> git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website> git add index.html
PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website> git status        
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   index.html

PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website> git commit -m "This is my first commit"
>>
[main 6565378] This is my first commit
 1 file changed, 1 insertion(+)
 create mode 100644 index.html
PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website> git push origin main
>>
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 342 bytes | 171.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/soa1580/ai-startup-website.git
   d911b62..6565378  main -> main
PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website> cd ai-startup-website
cd : Cannot find path 'C:\Users\user\Desktop\3mtt\git-project\ai-startup-website\ai-startup-website' because it does not 
exist.
At line:1 char:1
+ cd ai-startup-website
+ ~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (C:\Users\user\D...startup-website:String) [Set-Location], ItemNotFoundExcept  
   ion
    + FullyQualifiedErrorId : PathNotFound,Microsoft.PowerShell.Commands.SetLocationCommand

PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website> git clone https://github.com/soa1580/ai-startup-website.git
Cloning into 'ai-startup-website'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 6 (delta 0), reused 3 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (6/6), done.
PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website> cd ai-startup-website
PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website\ai-startup-website> git push origin main
Everything up-to-date
PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website\ai-startup-website> git commit -m "This is my first commit"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website\ai-startup-website> git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website\ai-startup-website> git add index.html   
PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website\ai-startup-website> git status        
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website\ai-startup-website> git push origin main
>>
Everything up-to-date
PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website\ai-startup-website> cd ai-startup-website                       
cd : Cannot find path 'C:\Users\user\Desktop\3mtt\git-project\ai-startup-website\ai-startup-website\ai-startup-website' 
because it does not exist.
At line:1 char:1
+ cd ai-startup-website
+ ~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (C:\Users\user\D...startup-website:String) [Set-Location], ItemNotFoundExcept  
   ion
    + FullyQualifiedErrorId : PathNotFound,Microsoft.PowerShell.Commands.SetLocationCommand

PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website\ai-startup-website> cd ai-startup-website
cd : Cannot find path 'C:\Users\user\Desktop\3mtt\git-project\ai-startup-website\ai-startup-website\ai-startup-website'      
because it does not exist.
At line:1 char:1
+ cd ai-startup-website
+ ~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (C:\Users\user\D...startup-website:String) [Set-Location], ItemNotFoundExcept  
   ion
    + FullyQualifiedErrorId : PathNotFound,Microsoft.PowerShell.Commands.SetLocationCommand

PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website\ai-startup-website> cd ./
PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website\ai-startup-website> cd ../
PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website> git branch
* main
PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website> git checkout -b update-navigation
Switched to a new branch 'update-navigation'
PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website> git branch
  main
* update-navigation
PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website> git status
>>
On branch update-navigation
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ai-startup-website/

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website> git status
On branch update-navigation
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ai-startup-website/

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website> git add index.html
PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website> git status        
On branch update-navigation
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ai-startup-website/

PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website> git commit -m "Update navigation bar"
[update-navigation e5cf1b5] Update navigation bar
 1 file changed, 2 insertions(+)
PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website> git push origin update-navigation
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 376 bytes | 188.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'update-navigation' on GitHub by visiting:
remote:      https://github.com/soa1580/ai-startup-website/pull/new/update-navigation
remote:
To https://github.com/soa1580/ai-startup-website.git
 * [new branch]      update-navigation -> update-navigation
PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website> git checkout main                
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website> git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ai-startup-website/

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website> git pull origin update-navigation
From https://github.com/soa1580/ai-startup-website
 * branch            update-navigation -> FETCH_HEAD
Updating 6565378..e5cf1b5
Fast-forward
 index.html | 2 ++
 1 file changed, 2 insertions(+)
PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website> git checkout -b add-contact-info
Switched to a new branch 'add-contact-info'
PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website> git branch
* add-contact-info
  main
  update-navigation
PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website> git add index.html
PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website> git commit -m "Add contact information"
[add-contact-info 73ae9bb] Add contact information
 1 file changed, 2 insertions(+)
PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website> git push origin add-contact-info
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 329 bytes | 164.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'add-contact-info' on GitHub by visiting:
remote:      https://github.com/soa1580/ai-startup-website/pull/new/add-contact-info
remote:
To https://github.com/soa1580/ai-startup-website.git
 * [new branch]      add-contact-info -> add-contact-info
PS C:\Users\user\Desktop\3mtt\git-project\ai-startup-website> 
