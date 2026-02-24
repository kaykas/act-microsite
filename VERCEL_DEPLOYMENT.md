# Deploy to Vercel

## Quick Deploy (2 minutes)

1. **Go to Vercel**: https://vercel.com/new

2. **Import Git Repository**:
   - Click "Import Project"
   - Select "Import Git Repository"
   - Paste your repo URL: `https://github.com/kaykas/act-microsite`
   - Click "Import"

3. **Configure Project**:
   - **Project Name**: `act-microsite` (or customize)
   - **Framework Preset**: Other (no framework needed)
   - **Root Directory**: `./` (leave as default)
   - **Build Command**: Leave empty (no build needed)
   - **Output Directory**: Leave empty

4. **Deploy**:
   - Click "Deploy"
   - Wait ~30 seconds
   - Your site will be live at `https://act-microsite.vercel.app`

## Custom Domain (Optional)

After deployment:
1. Go to Project Settings → Domains
2. Add your custom domain (e.g., `season.act-sf.org`)
3. Follow DNS configuration instructions
4. Vercel will auto-provision SSL certificate

## Auto-Deployments

Every push to `main` branch automatically deploys to production.
Every PR creates a preview deployment with unique URL.

---

**GitHub Repo**: https://github.com/kaykas/act-microsite
**Vercel Dashboard**: https://vercel.com/dashboard
