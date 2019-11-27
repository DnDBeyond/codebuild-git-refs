# codebuild-git-refs
Additional references to Git variables (branch, tag, author, etc) for use in Codebuild 

```yml
phases:
  install:
    commands:
      - curl -fsSL https://raw.githubusercontent.com/Curse/codebuild-git-refs/master/main >> git_refs.sh
      - . ./git_refs.sh
```
