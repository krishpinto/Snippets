# **Git Commands Cheatsheet**

## **1. Initialize a Git Repository**

Create a new Git repository in your project directory:

```bash
git init
```
<button onclick="copyToClipboard('git init')">Copy</button>

_Initializes an existing directory as a Git repository._

---

## **2. Configure Git**

Set your Git username and email:

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```
<button onclick="copyToClipboard('git config --global user.name \"Your Name\" && git config --global user.email \"your.email@example.com\"')">Copy</button>

_Sets your identity for all Git repositories._

---

## **3. Clone a Repository**

Copy a remote repository to your local machine:

```bash
git clone https://github.com/username/repository.git
```
<button onclick="copyToClipboard('git clone https://github.com/username/repository.git')">Copy</button>

_Creates a local copy of a remote repository._

---

## **4. Stage Changes**

Add a specific file to the staging area:

```bash
git add filename
```
<button onclick="copyToClipboard('git add filename')">Copy</button>

Add all changes (new, modified, and deleted files):

```bash
git add .
```
<button onclick="copyToClipboard('git add .')">Copy</button>

_Stages changes for commit._

---

## **5. Commit Changes**

Save your staged changes with a descriptive message:

```bash
git commit -m "Your commit message"
```
<button onclick="copyToClipboard('git commit -m \"Your commit message\"')">Copy</button>

_Commits the staged changes to the repository._

---

## **6. Add a Remote Repository**

Link your local repository to a remote GitHub repository:

```bash
git remote add origin https://github.com/username/repository.git
```
<button onclick="copyToClipboard('git remote add origin https://github.com/username/repository.git')">Copy</button>

Change the remote repository URL:

```bash
git remote set-url origin https://github.com/username/new-repository.git
```
<button onclick="copyToClipboard('git remote set-url origin https://github.com/username/new-repository.git')">Copy</button>

---

## **7. Push Changes to Remote**

Upload your local commits to the remote repository:

```bash
git push -u origin main
```
<button onclick="copyToClipboard('git push -u origin main')">Copy</button>

_Pushes changes to the `main` branch on GitHub._

---

## **8. Pull Changes from Remote**

Fetch and merge the latest changes from the remote repository:

```bash
git pull origin main
```
<button onclick="copyToClipboard('git pull origin main')">Copy</button>

_Downloads and integrates updates from the remote `main` branch._

---

## **9. Check Repository Status**

View the current state of your working directory and staging area:

```bash
git status
```
<button onclick="copyToClipboard('git status')">Copy</button>

_Displays the status of tracked and untracked files._

---

## **10. View Commit History**

See a list of past commits:

```bash
git log --oneline --graph --all
```
<button onclick="copyToClipboard('git log --oneline --graph --all')">Copy</button>

_Shows a condensed commit history with a graphical representation._

---

## **11. Create a New Branch**

Create a new branch:

```bash
git branch branch-name
```
<button onclick="copyToClipboard('git branch branch-name')">Copy</button>

Switch to the new branch:

```bash
git checkout branch-name
```
<button onclick="copyToClipboard('git checkout branch-name')">Copy</button>

_Create and move to a separate branch for feature development._

---

## **12. Merge Branches**

Merge a branch into the current branch:

```bash
git merge branch-name
```
<button onclick="copyToClipboard('git merge branch-name')">Copy</button>

_Integrates changes from another branch._

---

## **13. Delete a Branch**

Delete a local branch:

```bash
git branch -d branch-name
```
<button onclick="copyToClipboard('git branch -d branch-name')">Copy</button>

Delete a remote branch:

```bash
git push origin --delete branch-name
```
<button onclick="copyToClipboard('git push origin --delete branch-name')">Copy</button>

_Removes a branch after merging or when no longer needed._

---

## **14. Reset Changes**

Unstage all changes:

```bash
git reset .
```
<button onclick="copyToClipboard('git reset .')">Copy</button>

Hard reset to a previous commit:

```bash
git reset --hard commit-hash
```
<button onclick="copyToClipboard('git reset --hard commit-hash')">Copy</button>

_Reverts the repository to a previous state._

---

## **15. Revert a Commit**

Undo the last commit without losing changes:

```bash
git revert HEAD
```
<button onclick="copyToClipboard('git revert HEAD')">Copy</button>

_Creates a new commit that undoes the last commit._

---

## **16. Stash Changes**

Temporarily save changes without committing:

```bash
git stash
```
<button onclick="copyToClipboard('git stash')">Copy</button>

Apply the stashed changes:

```bash
git stash pop
```
<button onclick="copyToClipboard('git stash pop')">Copy</button>

_Saves work for later without committing._

---

## **17. Deploying a GitHub Repository**

Before deploying, build the application:

```bash
npm run build
```
<button onclick="copyToClipboard('npm run build')">Copy</button>

Run the application locally to test it:

```bash
npm start
```
<button onclick="copyToClipboard('npm start')">Copy</button>

_Runs the application in a local environment._

---

This cheatsheet covers all essential Git commands, including deployment steps.

<script>
function copyToClipboard(text) {
  navigator.clipboard.writeText(text);
  alert("Copied: " + text);
}
</script>

