# GitHub Basics for Beginners

Welcome! This guide will walk you through the steps to fork a repository, clone it locally, and create a pull request to contribute changes to an upstream repository.

---

## 🚀 Steps to Get Started

### 1. Fork a Repository
Forking creates a personal copy of a repository in your GitHub account.  
1. Go to the repository you'd like to fork.  
2. Click the **Fork** button in the top-right corner of the page.  
3. You'll now have a copy of the repository in your own GitHub account.

---

### 2. Clone Your Fork Locally
Cloning downloads the repository to your local machine.  
1. Navigate to your forked repository on GitHub.  
2. Click the **Code** button and copy the URL (HTTPS/SSH/GitHub CLI).  
3. Open a terminal and run:  
   ```bash
   git clone <repository-url>
   ```  
4. Navigate to the repository's folder:  
   ```bash
   cd <repository-name>
   ```  

---

### 3. Set Upstream Remote
The upstream remote links your local repo to the original repository.  
1. Add the upstream remote:  
   ```bash
   git remote add upstream <original-repository-url>
   ```  
2. Verify the remotes:  
   ```bash
   git remote -v
   ```  

---

### 4. Create a New Branch
Always create a new branch for your changes.  
1. Create and switch to a new branch:  
   ```bash
   git checkout -b <branch-name>
   ```  

---

### 5. Make Changes and Commit
1. Make your changes using your favorite editor.  
2. Stage the changes:  
   ```bash
   git add .
   ```  
3. Commit the changes:  
   ```bash
   git commit -m "Brief description of changes"
   ```  

---

### 6. Push Changes to Your Fork
1. Push the branch to your fork:  
   ```bash
   git push origin <branch-name>
   ```  

---

### 7. Create a Pull Request
1. Go to your forked repository on GitHub.  
2. Click the **Compare & pull request** button.  
3. Ensure the base repository is the original repo, and the base branch is the target branch (e.g., `main`).  
4. Add a title and description, then click **Create pull request**.

---

### 8. Sync with Upstream Repository
To avoid merge conflicts, regularly sync your fork with the upstream repository.  
1. Fetch the upstream changes:  
   ```bash
   git fetch upstream
   ```  
2. Merge the changes into your branch:  
   ```bash
   git merge upstream/main
   ```  
3. Resolve any conflicts, if necessary.

---

### 🎉 You're All Set!
Now you know how to fork a repository, clone it, create a new branch, and submit a pull request. Happy coding!  

---

## 💡 Tips
- Use descriptive branch names (e.g., `feature/add-login`).  
- Keep your pull requests concise and well-documented.  
- Always follow the repository's contribution guidelines.  

---

For further assistance, refer to the [GitHub Docs](https://docs.github.com).

