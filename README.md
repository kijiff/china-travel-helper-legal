# China Travel Helper - Legal Pages

This directory contains the privacy policy and terms of service pages for China Travel Helper app.

## Files

- `index.html` - Homepage with links to legal pages
- `privacy.html` - Privacy Policy page
- `terms.html` - Terms of Service page
- `vercel.json` - Vercel deployment configuration

## Features

- Bilingual support (English/Chinese)
- Responsive design
- Professional gradient backgrounds
- Easy language switching

## Deployment to Vercel

### Option 1: Deploy via GitHub (Recommended)

1. **Create a new GitHub repository**
   - Go to https://github.com
   - Create a new repository named `china-travel-helper-legal`

2. **Upload files**
   - Upload all files from this directory to the repository

3. **Connect to Vercel**
   - Go to https://vercel.com
   - Click "New Project"
   - Import your GitHub repository
   - Click "Deploy"

4. **Get your URLs**
   - After deployment, you'll get:
     - Privacy Policy: `https://your-project.vercel.app/privacy`
     - Terms of Service: `https://your-project.vercel.app/terms`

### Option 2: Deploy via Vercel CLI

1. **Install Vercel CLI**
   ```bash
   npm install -g vercel
   ```

2. **Login to Vercel**
   ```bash
   vercel login
   ```

3. **Deploy**
   ```bash
   vercel
   ```

4. **Production deployment**
   ```bash
   vercel --prod
   ```

## URLs for AGC Submission

After deployment, use these URLs in your AppGallery Connect submission:

- **Privacy Policy URL**: `https://your-project.vercel.app/privacy`
- **Terms of Service URL**: `https://your-project.vercel.app/terms`

## Custom Domain (Optional)

If you want a custom domain:

1. Go to your Vercel project settings
2. Click "Domains"
3. Add your custom domain (e.g., `legal.chinatravelhelper.com`)
4. Update DNS records as instructed

## License

© 2026 China Travel Helper. All rights reserved.
