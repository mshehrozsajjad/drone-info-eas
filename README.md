# Drone Information Static Page - Setup Instructions

## Files Included
- `index.html` - The main webpage with your drone information
- `EASA_Logo.png` - The EASA logo image

## How to Deploy to GitHub Pages

### Step 1: Create a GitHub Repository
1. Go to https://github.com and sign in
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Name it something like `drone-info` or `drone-registration`
5. Make sure it's set to **Public**
6. Click "Create repository"

### Step 2: Upload Your Files
1. In your new repository, click "uploading an existing file"
2. Drag and drop both files (`index.html` and `EASA_Logo.png`)
3. Scroll down and click "Commit changes"

### Step 3: Enable GitHub Pages
1. In your repository, click "Settings" (top menu)
2. Scroll down to "Pages" in the left sidebar
3. Under "Source", select "Deploy from a branch"
4. Under "Branch", select `main` (or `master`) and `/root`
5. Click "Save"

### Step 4: Access Your Page
Wait 1-2 minutes, then your page will be available at:
```
https://[your-username].github.io/[repository-name]/
```

For example: `https://john-doe.github.io/drone-info/`

### Step 5: Create QR Code
Once your page is live, you can create a QR code:
1. Copy your GitHub Pages URL
2. Use any QR code generator:
   - https://qr-code-generator.com/
   - https://www.qrcode-monkey.com/
   - https://www.qr-code-generator.com/
3. Paste your URL and generate the QR code
4. Download and print it for your drone

## Alternative: Quick Deploy with GitHub CLI
If you have GitHub CLI installed:
```bash
gh repo create drone-info --public
cd drone-info
git init
git add index.html EASA_Logo.png
git commit -m "Initial commit"
git branch -M main
git push -u origin main
```

Then enable Pages in Settings as described above.

## Information Displayed on the Page
- EID: DEU61zieluz0yoi7
- Phone: +49 17625387357
- Email: mshehrozsajjad@gmail.com
- Location: Munich, Germany

## Features
✅ Mobile responsive design
✅ Professional EASA branding
✅ Clickable phone and email links
✅ Clean, modern interface
✅ Perfect for QR code scanning

## Notes
- The page is fully static (no server required)
- Works perfectly with QR codes
- Mobile-friendly for easy scanning
- All contact information is clickable on mobile devices
