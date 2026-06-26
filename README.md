# POS PM Hub

PM Command Center for Q2 2026 POS Modernization. Tracks Order Flow, Paytronix OO, CFD Loyalty, and Brand Coupon POS.

## First-time setup (10 minutes)

### 1. Make repo public (required for GitHub Pages on free plan)
1. Go to **Settings** → scroll to bottom → **"Change visibility"** → Make public

### 2. Enable GitHub Pages
1. **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: **main** / **/ (root)**
4. Click **Save**
5. Your site will be live at: `https://ruthandrade86.github.io/pos-pm-hub`

### 3. Get your Jira API token
1. Go to: https://id.atlassian.com/manage-profile/security/api-tokens
2. Click **Create API token**
3. Label it "POS PM Hub"
4. Copy the token

### 4. Add token to the app (never committed to GitHub)
1. Open your live site
2. Click the **Settings** tab
3. Paste your Jira API token
4. Confirm your email address
5. Click **Save settings** → **Test Jira connection**

Token is stored in your browser's localStorage only — never in code, never in GitHub.

### 5. Load Jira data
- Click **⟳ Jira** in the top bar, or
- Go to **Projects** tab → click any workstream → **Load from Jira**

## Updating the app

Edit `index.html` directly on GitHub (click the file → pencil icon) or push from your machine. GitHub Pages auto-deploys on every push to main, usually within 60 seconds.

## Workstream → Epic mapping

| Workstream | Lead | Jira Epics |
|---|---|---|
| Order Flow | Marc McCoy | POS-5646, POS-5780 |
| Paytronix OO | Saffan Momin | POS-5869, POS-5841 |
| CFD Loyalty | Carlos Vaquedano | POS-5572, POS-5573, POS-5574, POS-5575, POS-5571 |
| Brand Coupon POS | Matthew Do | POS-5600, POS-6076 |

## Teams status updates

**Weekly status** and **Q3 carry-forward** buttons in the top bar copy a formatted update to your clipboard. Paste directly into Teams.
