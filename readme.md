this is a test about how github manages my accounts
```ssh -T personal/study
mkdir abc && cd abc
touch readme.md && vim readme.md
(edit and save the file)
```

```git init
git config user.name [user] && git config user.email [email@example.com]

git add .
git remote add origin [URI]
git commit -am "commit message"
git push origin master
```

```
URI:
https://github.com/[user]/[repo].git
git@github.com:[user]/[repo].git
git@personal/study:[user]/[repo].git
```
Links:
[how to handle multiple accs](https://dev.to/raven404/managing-multiple-github-account-using-git-in-windows-2m0h)
[make sure the repo exists and you have access](https://stackoverflow.com/questions/30068298/git-fatal-could-not-read-from-remote-repository-please-make-sure-you-have-th)
[failed to push some refs](https://stackoverflow.com/questions/12452042/git-error-src-refspec-master-does-not-match-any-error-failed-to-push-some-refs)
[ssh-add: error connecting to agent: no such file or directory](https://unix.stackexchange.com/questions/464574/ssh-add-returns-with-error-connecting-to-agent-no-such-file-or-directory)
