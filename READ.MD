Open Terminal.

Change the current working directory to your local repository.

To remove the file, enter git rm --cached:

git rm --cached giant_file
# Stage our giant file for removal, but leave it on disk
Commit this change using --amend -CHEAD:

git commit --amend -CHEAD
# Amend the previous commit with your change
# Simply making a new commit won't work, as you need
# to remove the file from the unpushed history as well
Push your commits to GitHub:

git push
# Push our rewritten, smaller commit
 Contact a human
Article versions
GitHub.com
GitHub Enterprise 2.12
GitHub Enterprise 2.11
GitHub Enterprise 2.10
GitHub Enterprise 2.9
