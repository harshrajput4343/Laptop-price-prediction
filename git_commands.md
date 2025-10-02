# Git Commands to Push the Repository to GitHub

## 1. **Initialize a Git Repository**
```bash
git init
```
- **Function**: Initializes a new Git repository in the current directory. This creates a `.git` folder to track changes.

---

## 2. **Add Files to the Staging Area**
```bash
git add .
```
- **Function**: Adds all files in the current directory to the staging area, preparing them for a commit.

---

## 3. **Commit the Changes**
```bash
git commit -m "Initial commit"
```
- **Function**: Saves the changes in the staging area to the repository with a descriptive message (e.g., "Initial commit").

---

## 4. **Add a Remote Repository**
```bash
git remote add origin https://github.com/harshrajput4343/Laptop-price-prediction.git
```
- **Function**: Links the local repository to a remote repository hosted on GitHub.

---

## 4.1 **Set or Update Remote URL**
```bash
git remote set-url origin https://github.com/harshrajput4343/Laptop-price-prediction.git
```
- **Function**: Updates the URL of the remote repository. Useful if the remote repository URL has changed or was not set correctly.

---

## 4.2 **Show Current Branch**
```bash
git branch --show-current
```
- **Function**: Displays the name of the branch you are currently working on.

---

## 4.3 **Rename the Current Branch**
```bash
git branch -M main
```
- **Function**: Renames the current branch to `main`. Useful for standardizing branch names.

---

## 5. **Push the Changes to GitHub**
```bash
git push -u origin main
```
- **Function**: Pushes the committed changes to the `main` branch of the remote repository. The `-u` flag sets the upstream branch for future pushes.

---

## 6. **Check the Status of the Repository**
```bash
git status
```
- **Function**: Displays the current state of the working directory and staging area, showing any untracked, modified, or staged files.

---

## 7. **Check the Remote Repository**
```bash
git remote -v
```
- **Function**: Lists the remote repositories linked to the local repository, along with their URLs.

---

## 8. **Pull Changes from the Remote Repository**
```bash
git pull origin main
```
- **Function**: Fetches and merges changes from the `main` branch of the remote repository into the local repository.

---

## 9. **Push Additional Changes**
```bash
git add .
git commit -m "Updated files"
git push
```
- **Function**: Adds, commits, and pushes any new changes to the remote repository.

---

## 15. **Separate Steps for Git Initialization**

### From Scratch (New Repository):
1. Initialize a new Git repository:
   ```bash
   git init
   ```
2. Add files to the staging area:
   ```bash
   git add .
   ```
3. Commit the changes:
   ```bash
   git commit -m "Initial commit"
   ```
4. Add a remote repository:
   ```bash
   git remote add origin <repository-url>
   ```
5. Push the changes to the remote repository:
   ```bash
   git push -u origin main
   ```

### From an Existing Repository:
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the repository directory:
   ```bash
   cd <repository-folder>
   ```
3. Check the current branch:
   ```bash
   git branch --show-current
   ```
4. Create or switch to a branch:
   ```bash
   git checkout -b <new-branch>
   ```
5. Pull the latest changes:
   ```bash
   git pull origin main
   ```

---

## 16. **Branch Management Commands**

### List All Branches:
```bash
git branch -a
```
- **Function**: Displays all local and remote branches.

### Create a New Branch:
```bash
git branch <new-branch>
```
- **Function**: Creates a new branch with the specified name.

### Switch to a Branch:
```bash
git checkout <branch-name>
```
- **Function**: Switches to the specified branch.

### Delete a Branch:
```bash
git branch -d <branch-name>
```
- **Function**: Deletes the specified branch locally.

### Push a New Branch to Remote:
```bash
git push -u origin <branch-name>
```
- **Function**: Pushes the new branch to the remote repository and sets it as the upstream branch.

---

By following these commands, you can successfully initialize, commit, and push your project to GitHub while maintaining synchronization between the local and remote repositories.