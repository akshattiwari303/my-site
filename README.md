# My Personal Site

Bold, modern portfolio + blog. Ready to deploy on Vercel in under 5 minutes.

## Files
- `index.html` — Homepage (hero, about, blog list, contact)
- `post.html` — Sample blog post (duplicate this for each new post)
- `vercel.json` — Vercel config (clean URLs)

## How to Deploy on Vercel

### Option A: Drag & Drop (Easiest — no account needed initially)
1. Go to vercel.com
2. Sign up with GitHub (free)
3. Click "Add New Project"
4. Drag this entire folder into the deploy area
5. Done — you'll get a live URL like `yoursite.vercel.app`

### Option B: Via GitHub (Recommended for ongoing use)
1. Create a free GitHub account at github.com
2. Create a new repository (e.g. "my-site")
3. Upload these files to the repo
4. Go to vercel.com → "Add New Project" → Import from GitHub
5. Select your repo → Deploy
6. Every time you push changes to GitHub, Vercel auto-deploys ✓

## Customizing Your Site

### Change your name/info
In `index.html`, find and replace:
- `YOUR.NAME` → your actual name
- `[Your Name]` → your name in the About section
- `[what you do]` → your current role/project
- `you@email.com` → your email
- Social media links in the Contact section

### Add a new blog post
1. Duplicate `post.html`
2. Rename it (e.g. `my-second-post.html`)
3. Edit the title, tag, content inside
4. In `index.html`, add a new `.blog-card` block pointing to your new file

### Change accent color
In `index.html` and `post.html`, find `:root` and change:
- `--accent: #ff4d00;` → any color you want (e.g. `#0066ff` for blue)

## Custom Domain (Optional, ~$10/year)
1. Buy a domain on Namecheap or Cloudflare
2. In Vercel dashboard → your project → Settings → Domains
3. Add your domain and follow DNS instructions
4. Takes ~10 minutes to go live
