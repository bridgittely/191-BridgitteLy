Discussion 3 activity 2

Use git status to see which branch you are on.
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

What does git log look like?
commit f8712d5c4df74fa0d49c8cc9ba3b1a5b2c571072 (HEAD -> master, origin/master, origin/HEAD)
Author: Frank Theile <ftheile@grundfos.com>
Date:   Mon Dec 9 10:30:13 2019 +0100

    Add missing shebang in squashing/setup.sh
    
    `setup.sh` should be executable according to the instructions given in README.md

commit e060df632bf4799da9aa1c0092640563acf84588
Author: Adam Matan <adamatan@users.noreply.github.com>
Date:   Wed Dec 4 07:46:31 2019 +0200

    Word ordering

commit 6ccb85882dc12fb0b26acd65bead2fc7da57a187
Author: Frank Theile <ftheile@grundfos.com>
Date:   Wed Nov 27 08:24:29 2019 +0100

    Mention `less` in SHELL-BASICS.md
    
    Helpful alternative to `cat` for long files.
:



Create a file

What does the output from git status look like now?
On branch master
Your branch is up to date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	file.txt

nothing added to commit but untracked files present (use "git add" to track)


add the file to the staging area

How does git status look now?
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	new file:   file.txt


commit the file to the repository

How does git status look now?
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean


Change the content of the file you created earlier

What does git status look like now?
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   file.txt

no changes added to commit (use "git add" and/or "git commit -a")

add the file change

What does git status look like now?
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	modified:   file.txt


Change the file again
Make a commit

What does the status look like now? The log?
On branch master
Your branch is ahead of 'origin/master' by 2 commits.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	modified:   file.txt
  
  commit 8da1a539188a17670bb90e821bd2092c1d36e166 (HEAD -> master)
Author: Bridgitte Ly <bridgittely@gmail.com>
Date:   Fri Jan 24 15:00:30 2020 -0800

    new change

commit 73d25054043651476e6e5c16bf2976752a0ede03
Author: Bridgitte Ly <bridgittely@gmail.com>
Date:   Fri Jan 24 14:57:21 2020 -0800

    first commit

commit f8712d5c4df74fa0d49c8cc9ba3b1a5b2c571072 (origin/master, origin/HEAD)
Author: Frank Theile <ftheile@grundfos.com>
Date:   Mon Dec 9 10:30:13 2019 +0100

    Add missing shebang in squashing/setup.sh
    
    `setup.sh` should be executable according to the instructions given in README.md

commit e060df632bf4799da9aa1c0092640563acf84588
Author: Adam Matan <adamatan@users.noreply.github.com>
:

Commit the newest change
