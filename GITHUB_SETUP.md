# GitHub Repository Setup Instructions

Follow these steps to create your GitHub repository and push your portfolio code.

## Step 1: Create Repository on GitHub

1. Go to [GitHub.com](https://github.com) and sign in to your account
2. Click the **"+"** icon in the top right corner
3. Select **"New repository"**
4. Fill in the repository details:
   - **Repository name**: `portfulio`
   - **Description**: `Personal portfolio website - Modern responsive design`
   - **Visibility**: Choose Public or Private
   - **DO NOT** initialize with README, .gitignore, or license (we already have these files)
5. Click **"Create repository"**

## Step 2: Push Your Code to GitHub

After creating the repository, GitHub will show you commands. Use these commands:

```bash
# Make sure you're in the portfulio directory
cd C:\Users\Asif\OneDrive\Desktop\portfulio

# Add the remote repository (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/portfulio.git

# Rename branch to main if needed
git branch -M main

# Push your code
git push -u origin main
```

## Alternative: Using SSH (if you have SSH keys set up)

```bash
git remote add origin git@github.com:YOUR_USERNAME/portfulio.git
git branch -M main
git push -u origin main
```

## Step 3: Verify

1. Go to your repository on GitHub
2. You should see all your files:
   - `index.html`
   - `profile.jpg.jpeg`
   - `README.md`
   - `.gitignore`

## Step 4: Enable GitHub Pages (Optional - to host your portfolio)

1. Go to your repository settings
2. Scroll down to **"Pages"** section
3. Under **"Source"**, select **"Deploy from a branch"**
4. Choose **"main"** branch and **"/ (root)"** folder
5. Click **"Save"**
6. Your portfolio will be live at: `https://YOUR_USERNAME.github.io/portfulio/`

## Updating Your Portfolio

Whenever you make changes:

```bash
# Add all changes
git add .

# Commit with a message
git commit -m "Update: Your change description"

# Push to GitHub
git push
```

## Important Files

- **index.html**: Main portfolio file - Edit this to update your portfolio
- **profile.jpg.jpeg**: Your profile image - Replace this file to change your photo
- **README.md**: Documentation file
- **.gitignore**: Files to ignore in git

---

**Need help?** Check the README.md file for customization guide.

