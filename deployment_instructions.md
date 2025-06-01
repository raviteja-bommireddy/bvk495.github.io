# GitHub Pages Deployment Instructions

This guide will walk you through deploying your portfolio website to GitHub Pages at https://bvk495.github.io/ using the simple direct upload method.

## Step 1: Create a GitHub Repository

1. Log in to your GitHub account at [github.com](https://github.com)
2. Click the "+" icon in the top right corner and select "New repository"
3. Name your repository exactly: `bvk495.github.io` (this specific name is required for GitHub Pages)
4. Make sure the repository is set to "Public"
5. Click "Create repository"

## Step 2: Upload Your Portfolio Files

### Option 1: Upload via GitHub Web Interface (Easiest)

1. In your new repository, click the "Add file" button and select "Upload files"
2. Drag and drop all the files and folders from the unzipped portfolio folder
3. Make sure to maintain the folder structure (css/, js/, images/, videos/)
4. Add a commit message like "Initial portfolio website upload"
5. Click "Commit changes"

### Option 2: Upload via Git Command Line

If you prefer using Git commands:

1. Extract the portfolio zip file to a folder on your computer
2. Open a terminal/command prompt in that folder
3. Run the following commands:

```bash
git init
git add .
git commit -m "Initial portfolio website upload"
git branch -M main
git remote add origin https://github.com/bvk495/bvk495.github.io.git
git push -u origin main
```

## Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings" (tab at the top)
3. Scroll down to the "GitHub Pages" section
4. Under "Source", select "main" branch
5. Click "Save"

## Step 4: View Your Live Website

1. Wait a few minutes for GitHub to build your site
2. Visit https://bvk495.github.io/ to see your live portfolio

Your website is now live! Any changes you make to the repository will be automatically reflected on your website.

## Making Future Updates

To update your website in the future:

1. Go to your repository on GitHub
2. Navigate to the file you want to update
3. Click the pencil icon to edit the file
4. Make your changes
5. Add a commit message describing your changes
6. Click "Commit changes"

Alternatively, you can make changes locally and push them using Git commands.

## Troubleshooting

- If your site doesn't appear, check that your repository is named exactly `bvk495.github.io`
- Make sure your repository is public
- Verify that GitHub Pages is enabled in the repository settings
- Check that index.html is in the root directory
- If images or videos don't load, check their file paths in the HTML

## Need More Help?

For more detailed information, visit the [GitHub Pages documentation](https://docs.github.com/en/pages).
