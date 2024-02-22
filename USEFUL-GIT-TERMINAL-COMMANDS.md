# USEFUL GIT TERMINAL COMMANDS

In no particular order, just notes for now.

## Get Latest Commit
```
git log -1
```

## Buscar una Palabra Específica en un Commit dado
```
git log --all --grep="test"
```

Donde la palabra sería "test". Si queremos buscar la palabra "house" en un commit, usaremos:

```
git log --all --grep="test"
```

------

🚨 🚨 🚨 
## WARNING: Will discard YOUR LOCAL CHANGES on current branch and override with REMOTE (save your work before trying!!!)
```
git reset --hard origin/master
```

### If you want to simply cleanup local files (same warning as before):
```
git clean -f
```
