# Remote Repositories Assignment

## Repository Links

### Open Source Contribution
- Original repository: https://github.com/ImZzzLoL/awesome-calculator
- Fork repository: https://github.com/InndraDev/awesome-calculator (форк)
- Feature branch: feature/multiply

### Corporate Project  
- Main repository: https://github.com/ImZzzLoL/techstart-api
- Backup repository: https://github.com/ImZzzLoL/techstart-api-backup

## Verification Commands

Run these commands in techstart-api-local:
```
git remote -v | grep -c "push"
git branch -r | wc -l
```

Expected output: 
- First command: 4 or more (multiple push URLs)
- Second command: number of remote branches
