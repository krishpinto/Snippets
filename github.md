# snippets


**next.js**

init project
```bash
npx create-next-app@latest
```

---

**shadcn**

init
```bash
npx shadcn@latest init
```

add all components
```bash
npx shadcn@latest add .
```

---

**git · new repo**

init
```bash
git init
```

add remote origin
```bash
git remote add origin https://github.com/username/repo.git
```

change remote url
```bash
git remote set-url origin https://github.com/username/repo.git
```

rename branch to main
```bash
git branch -M main
```

stage all
```bash
git add .
```

commit
```bash
git commit -m "message"
```

push
```bash
git push -u origin main
```

---

**git · branches**

new branch + switch
```bash
git checkout -b branch-name
```

switch to branch
```bash
git checkout branch-name
```

---

**git · nuke**

clear commit history
```bash
rm -rf .git && git init && git add . && git commit -m "init" && git push --force
```
