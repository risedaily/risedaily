# Deploy RiseDaily in 3 Minutes

## Step 1: Download Your App (30 seconds)
1. Look for the file `risedaily-app.zip` in your Replit files
2. Click the download button or right-click → Download
3. Extract the zip file on your computer

## Step 2: Upload to GitHub (1 minute)
1. Go to [github.com/new](https://github.com/new)
2. Repository name: `risedaily`
3. Make it Public
4. Click "Create repository"
5. Click "uploading an existing file"
6. Drag all your extracted files into GitHub

## Step 3: Deploy to Vercel (1 minute)
1. Go to [vercel.com/new](https://vercel.com/new)
2. Import your GitHub repository
3. Click "Deploy" (auto-configured for Vite)
4. Add these environment variables in settings:
   - `STRIPE_SECRET_KEY` = your stripe secret key
   - `VITE_STRIPE_PUBLIC_KEY` = your stripe public key

## Result: Live App
- Your app gets a live URL: `https://risedaily-xxx.vercel.app`
- Add custom domain in Vercel dashboard
- Automatic deployments on every GitHub update

## Your Features Live:
- Daily motivational quotes
- Journal with progress tracking
- 6 virtual pet types with evolution
- Premium subscriptions ($5.99/month)
- Mobile-optimized design
- Secure Stripe payments

Ready to inspire users worldwide!