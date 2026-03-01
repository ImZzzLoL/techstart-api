# Remote Repository Setup

## Current Remotes
[Вставьте вывод git remote -v]
backup  https://github.com/ImZzzLoL/techstart-api-backup.git (fetch)
backup  https://github.com/ImZzzLoL/techstart-api-backup.git (push)
origin  https://github.com/ImZzzLoL/techstart-api.git (fetch)
origin  https://github.com/ImZzzLoL/techstart-api.git (push)
origin  https://github.com/ImZzzLoL/techstart-api-backup.git (push)

## Tracking Branches
[Вставьте вывод git branch -vv]
  develop 9383bc2 fix 1.1.0-dev
* master  e2011d0 Merge branch 'master' of https://github.com/ImZzzLoL/techstart-api

## Fork Workflow Summary
- Original repository: https://github.com/ImZzzLoL/awesome-calculator
- Fork repository: https://github.com/InndraDev/awesome-calculator
- Upstream configuration: git remote add upstream https://github.com/ImZzzLoL/awesome-calculator

## Backup Strategy
- Primary remote: origin
- Backup remote: backup
- Sync command: git remote set-url --add --push origin https://github.com/ImZzzLoL/techstart-api-backup.git

## Lessons Learned
Много чего непонятно исходя из статей. При выполнении заданий не раз приходилось обращаться к сторонним источникам информации.
