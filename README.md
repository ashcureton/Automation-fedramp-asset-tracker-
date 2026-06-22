# FedRAMP Asset Tracker

Interactive web-based tracker for IBM Automation FedRAMP assets.

## Features
- Track 4 asset types per product (Client One Pager, Internal One Pager, Enablement Deck, Feature Parity)
- Contact touchpoint tracking (3 dates per product)
- Quick links to Seismic, Email Templates, and Box Note
- Filter by status (Complete, Incomplete, Unassigned)
- Export data to JSON
- Auto-save changes to browser localStorage

## Deploy to GitHub Pages

### Step 1: Create Repository
1. Go to https://github.com/new
2. **Repository name**: `fedramp-asset-tracker` (or any name you prefer)
3. **Description**: "FedRAMP Asset Tracker for IBM Automation"
4. **Visibility**: Choose "Public" (required for free GitHub Pages) or "Private" (requires paid plan)
5. **DO NOT** check "Add a README file"
6. Click **"Create repository"**

### Step 2: Upload Files
After creating the repository, you'll see a page with setup instructions. Follow these steps:

1. Click on **"uploading an existing file"** link
2. Drag and drop these files:
   - `FedRAMP_Asset_Tracker.html`
   - `README.md`
3. Scroll down and click **"Commit changes"**

### Step 3: Rename HTML File (Important!)
1. In your repository, click on `FedRAMP_Asset_Tracker.html`
2. Click the pencil icon (Edit this file)
3. Change the filename at the top from `FedRAMP_Asset_Tracker.html` to `index.html`
4. Scroll down and click **"Commit changes"**

### Step 4: Enable GitHub Pages
1. Go to your repository **Settings** (top menu)
2. Click **"Pages"** in the left sidebar
3. Under "Source", select **"Deploy from a branch"**
4. Under "Branch", select **"main"** and **"/ (root)"**
5. Click **"Save"**

### Step 5: Access Your Site
1. Wait 1-2 minutes for deployment
2. Your site will be available at: `https://YOUR-USERNAME.github.io/fedramp-asset-tracker/`
3. GitHub will show you the exact URL in the Pages settings

## Sharing the Tracker
Once deployed, share the URL with your team. All changes are saved locally in each user's browser.

## Local Usage
You can also open `FedRAMP_Asset_Tracker.html` directly in any browser without hosting.