# How to Upload to GitHub

Follow these simple steps to upload your HTML to PDF Converter to GitHub:

## Method 1: Using GitHub Website (Easiest)

1. **Create a New Repository**
   - Go to [GitHub.com](https://github.com) and sign in
   - Click the "+" icon in the top right corner
   - Select "New repository"
   - Name it: `html-to-pdf-converter` (or any name you prefer)
   - Choose Public or Private
   - **DO NOT** initialize with README, .gitignore, or license (we already have these)
   - Click "Create repository"

2. **Upload Files**
   - On the new repository page, click "uploading an existing file"
   - Drag and drop all files from your `web to pdf` folder:
     - `index.html` (or `web_to_pdf.html`)
     - `README.md`
     - `.gitignore`
     - `LICENSE`
   - Scroll down and click "Commit changes"

3. **Done!** Your repository is now live on GitHub.

## Method 2: Using Git Command Line

1. **Open Terminal/Command Prompt**
   - Navigate to your project folder:
     ```bash
     cd "C:\Users\Admin\Downloads\web to pdf"
     ```

2. **Initialize Git Repository**
   ```bash
   git init
   ```

3. **Add All Files**
   ```bash
   git add .
   ```

4. **Commit Files**
   ```bash
   git commit -m "Initial commit: HTML to PDF Converter"
   ```

5. **Create Repository on GitHub**
   - Go to GitHub.com and create a new repository (don't initialize it)
   - Copy the repository URL

6. **Connect and Push**
   ```bash
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```
   (Replace YOUR_USERNAME and YOUR_REPO_NAME with your actual GitHub username and repository name)

## Method 3: Using GitHub Desktop

1. **Download GitHub Desktop** from [desktop.github.com](https://desktop.github.com)

2. **Install and Sign In** with your GitHub account

3. **Add Repository**
   - Click "File" → "Add Local Repository"
   - Browse to your `web to pdf` folder
   - Click "Add repository"

4. **Publish to GitHub**
   - Click "Publish repository"
   - Choose a name and description
   - Click "Publish repository"

## Enable GitHub Pages (Optional)

To host your HTML file online for free:

1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll down to "Pages" section
4. Under "Source", select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click "Save"
7. Your site will be available at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

## Files Included

- ✅ `index.html` - Main application (you can rename `web_to_pdf.html` to `index.html` if needed)
- ✅ `README.md` - Project documentation
- ✅ `.gitignore` - Git ignore rules
- ✅ `LICENSE` - MIT License

## Tips

- Make sure `index.html` is in the root of your repository for GitHub Pages to work
- You can rename `web_to_pdf.html` to `index.html` if you want it as the main file
- Update the README.md with your own information if needed
- Add screenshots to make your README more attractive!

---

**Need Help?** Check out [GitHub Docs](https://docs.github.com) for more information.

