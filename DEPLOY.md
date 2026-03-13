# Deploy to Vercel

## 1. Create GitHub repo

1. Go to [github.com/new](https://github.com/new)
2. Name it `medisync-outbound` (or any name)
3. Leave it empty (no README)
4. Create the repo

## 2. Push to GitHub

Run these commands (replace `YOUR_USERNAME` with your GitHub username):

```bash
cd outbound-engine
git remote add origin https://github.com/YOUR_USERNAME/medisync-outbound.git
git branch -M main
git push -u origin main
```

## 3. Deploy to Vercel

1. Go to [vercel.com](https://vercel.com) and sign in with GitHub
2. Click **Add New** → **Project**
3. Import your `medisync-outbound` repo
4. Click **Deploy** (no config needed)

Your workspace will be live at `https://your-project.vercel.app`

## 4. Password

The workspace is protected with password: **pillow123**

Only you and Brock need to know it. The password is required each new browser session.
