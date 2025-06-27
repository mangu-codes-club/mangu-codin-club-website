# 🚀 Deployment Instructions for Mangu Coding Club Website

## Step 1: Create GitHub Repository

1. Go to [GitHub.com](https://github.com) and sign in to the `mangu-codes-club` organization account
2. Click the "+" icon in the top right corner and select "New repository"
3. Set the repository name to: `mangu-codin-club-website`
4. Make sure it's set to **Public** (required for free GitHub Pages)
5. **Do NOT** initialize with README, .gitignore, or license (we already have these files)
6. Click "Create repository"

## Step 2: Push Code to GitHub

After creating the repository, run these commands in the project directory:

```bash
# Add the remote repository (update if URL is different)
git remote set-url origin https://github.com/mangu-codes-club/mangu-codin-club-website.git

# Push the code
git push -u origin main
```

## Step 3: Enable GitHub Pages

1. Go to the repository on GitHub
2. Click on **Settings** tab
3. Scroll down to **Pages** section in the left sidebar
4. Under **Source**, select "GitHub Actions" (NOT "Deploy from a branch")
5. Save the settings

## Step 4: Verify Deployment

1. After pushing to main branch, go to the **Actions** tab in your repository
2. You should see a workflow called "Deploy to GitHub Pages" running
3. Wait for it to complete (usually takes 2-3 minutes)
4. Once completed, your website will be available at:
   `https://mangu-codes-club.github.io/mangu-codin-club-website/`

## Step 5: Custom Domain (Optional)

If you want to use a custom domain (like `mangucodingclub.com`):

1. In the **Pages** settings, add your custom domain
2. Create a CNAME record in your DNS settings pointing to `mangu-codes-club.github.io`
3. Enable "Enforce HTTPS" once the domain is verified

## Troubleshooting

### If deployment fails:
- Check the Actions tab for error logs
- Ensure the repository is public
- Verify that GitHub Pages is enabled with "GitHub Actions" as source

### If the website shows a 404:
- Make sure the base path in `vite.config.ts` matches your repository name
- Check that the workflow completed successfully

### Making changes:
- Any push to the `main` branch will automatically trigger a new deployment
- Changes typically take 2-3 minutes to appear on the live site

## Current Configuration

- ✅ Vite configured with correct base path
- ✅ GitHub Actions workflow set up
- ✅ Build optimization for production
- ✅ All components properly configured
- ✅ Responsive design implemented

Your website is ready to go live! 🎉
