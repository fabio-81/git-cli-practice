Assuming that you aren't sure whether you're currently inside of a Git repository, write the command (or commands) that will give you this information.

Git status

Assuming that you are currently within a Git repository, write the command (or commands) that will cause the file 'hello-world.txt' to be committed.

git add hello-world.txt followed by
git commit -m "hello-world

Assuming that you are currently within a Git repository, write the command (or commands) that will display any uncommitted changes made to the file named 'README.md'.

Git diff README.md

Assuming that you are currently within a Git repository, write the command (or commands) that will display the changes from the commit with the ID of abc123.

Git show abc123.   
in my case:
 git show 17ac160ff802e73a0251604d092d24ca4166a165
or git show --abbrev-commit 17ac160

Assuming that you are currently within a Git repository, write the command (or commands) that will display the ID and commit message for the 3 most recent commits.


Git log -n3