# git-learnings

## Interactive Rebase:

1) Pick - make this as root when you want to do squash or fixup
2) Squash - make the commits as Squash if you want to merge commit with parent Pick
3) reword - make the commit as reword if you want to edit the  commit message
basically this will not allow you to alter files.
alternate for editing last commit message is git commit --amend --no-edit.
4) edit - make the commit as edit if you want to edit the file as well as commit message
basically it will stop rebase and ask you to change file and once done give git rebase --continue
alternate for editing last commit message is git commit --amend.(only last commit message).
5) drop - make commit as drop if you want to completely drop that commit from history along with file changes.