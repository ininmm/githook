# Githook

This githook can take the current branch name as your commit's title message.

## Install

Go to your project's root directory and  run below script：

```script
mkdir -p .git/hooks && curl https://raw.githubusercontent.com/ininmm/githook/master/prepare-commit-msg.sh > .git/hooks/prepare-commit-msg && chmod u+x .git/hooks/prepare-commit-msg
```
