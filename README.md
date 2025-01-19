# **GitHub Basics for Beginners**

Welcome! This guide will walk you through the steps to fork a repository, clone it locally, and create a pull request to contribute changes to an upstream repository.

---

## 🚀 Steps to Get Started  

### Step 1: **Set Up GitHub**

1. **Create a GitHub Account**  
   - Go to [GitHub](https://github.com) and sign up for a free account.  
   - Verify your email and complete the setup process.

---
### Step 2: **Install Git**

1. **Download Git**  
   - Visit the [official Git website](https://git-scm.com).  
   - Download the latest version for your operating system (Windows, macOS, or Linux).  

2. **Install Git**  
   - Run the downloaded installer and follow the setup instructions.  
   - Beginners should use the default settings during installation.  

3. **Verify Installation**  
   - Open your terminal (Command Prompt, Git Bash, or any shell).  
   - Run this command to check if Git is installed:  
     ```bash
     git --version
     ```  
   - You should see something like `git version x.y.z`.

---

### Step 3: **Configure Git**

1. **Set Your Username**  
   Assign your username for commits:  
   ```bash
   git config --global user.name "Your Name"
   ```  

2. **Set Your Email**  
   Use the email linked to your GitHub account:  
   ```bash
   git config --global user.email "youremail@example.com"
   ```  

3. **Verify Your Configuration**  
   Confirm your settings by running:  
   ```bash
   git config --list
   ```  
   You should see your username and email.

---

### Step 4: **Fork a Repository**

Forking creates a personal copy of a repository in your GitHub account.  

1. Go to the repository you'd like to fork.  
2. Click the **Fork** button in the top-right corner of the page.  
3. You'll now have a copy of the repository in your own GitHub account.

---

### Step 5: **Clone Your Fork Locally**

Cloning downloads the repository to your local machine.  

1. Navigate to your forked repository on GitHub.  
2. Click the **Code** button and copy the URL (HTTPS recommended for beginners).  
3. Open a terminal and run:  
   ```bash
   git clone <repository-url>
   ```  
4. Navigate to the repository's folder:  
   ```bash
   cd <repository-name>
   ```

---

### Step 6: **Set Upstream Remote**

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

### Step 7: **Create a New Branch**

Always create a new branch for your changes.  

1. Create and switch to a new branch:  
   ```bash
   git checkout -b <branch-name>
   ```

---

### Step 8: **Make Changes and Commit**

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

### Step 9: **Push Changes to Your Fork**

1. Push the branch to your fork:  
   ```bash
   git push origin <branch-name>
   ```

---

### Step 10: **Create a Pull Request**

1. Go to your forked repository on GitHub.  
2. Click the **Compare & pull request** button.  
3. Ensure the base repository is the original repo, and the base branch is the target branch (e.g., `main`).  
4. Add a title and description, then click **Create pull request**.

---

### Step 11: **Sync with Upstream Repository**

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

### 🎉 **You're All Set!**

Now you know how to fork a repository, clone it, create a new branch, and submit a pull request. Happy coding!  

---

## 💡 **Tips**

- Use descriptive branch names (e.g., `feature/add-login`).  
- Keep your pull requests concise and well-documented.  
- Always follow the repository's contribution guidelines.

---

For further assistance, refer to the [GitHub Docs](https://docs.github.com).