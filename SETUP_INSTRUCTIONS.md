# GitHub Pages Setup Instructions

This repository is now configured to automatically deploy to GitHub Pages!

## Steps to Complete Setup

After this PR is merged, you need to enable GitHub Pages in your repository settings:

1. **Go to your repository settings:**
   - Navigate to `https://github.com/giuliamonopoli/giuliamonopoli/settings/pages`
   - Or: Click on "Settings" tab → "Pages" in the left sidebar

2. **Configure GitHub Pages:**
   - Under "Build and deployment"
   - Set **Source** to: `GitHub Actions`
   - Save the changes

3. **That's it!** 
   - The workflow will automatically run when you push to the `copilot/add-public-page` branch
   - Your site will be available at: `https://giuliamonopoli.github.io/giuliamonopoli/`

## How it Works

- The `.github/workflows/deploy.yml` file contains the GitHub Actions workflow
- It automatically builds and deploys your site whenever you push to this branch
- You can also manually trigger deployment from the Actions tab

## Customizing Your Site

Edit the `index.html` file and content in the `assets` folder to customize your portfolio with your own:
- Name and contact information
- Profile picture (replace `assets/images/my-avatar.png`)
- Projects and work experience
- Skills and resume details

## Manual Deployment

You can also manually trigger a deployment:
1. Go to the "Actions" tab in your repository
2. Select "Deploy to GitHub Pages" workflow
3. Click "Run workflow"
