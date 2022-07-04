# git-kazap-academy

## git init
Initialize a project 
```bash
git init
```

## git initial config 
```bash
git config --config user.name "username"
git congif --config user.email "user@mail"
```

## check changes
```bash
git status
```

## commiting changes
```bash
git add .
git commit -m "describe changes..."
```

## change master branch to main
```bash
git branch -m main
```

## configure remote
```bash
git remote add origin <http://githubrepo.com>
```

## send changes to the remote repo
```bash 
git push -u origin main
```

## change branch 
```bash
git switch --create <newbranch>
or
git checkout -b <newbranch>
```