# How to deploy your portfolio to barbaraameliux.com

This is a static HTML site — no framework, no build step, no dependencies. 
Pure HTML + CSS + JS. You can host it anywhere.

---

## Option A: Netlify (recommended, free)

1. Go to https://netlify.com and sign up (free)
2. Drag and drop the entire `barbara-portfolio` folder onto their deploy zone
3. It'll give you a URL like `random-name.netlify.app`
4. Go to **Domain settings → Add custom domain**
5. Type `barbaraameliux.com` and follow the steps
6. Netlify will tell you to update your DNS — just point it to Netlify's nameservers

**To update later:** just drag-drop the new folder again. Done in 30 seconds.

---

## Option B: Vercel (also free, also great)

1. Go to https://vercel.com and sign up
2. Click **Add New → Project → Browse** and upload the folder
3. Go to **Settings → Domains → Add**
4. Type `barbaraameliux.com`
5. Update DNS as instructed

---

## Option C: GitHub Pages (free, takes 5 mins to set up)

1. Create a free GitHub account at github.com
2. Create a new repository called `portfolio`
3. Upload all the files
4. Go to **Settings → Pages → Source: main branch**
5. Add your custom domain `barbaraameliux.com` in the Pages settings
6. Update DNS: add a CNAME record pointing to `yourusername.github.io`

---

## Wherever you bought your domain (e.g. GoDaddy, Namecheap):

You'll need to update the DNS settings. The hosting platform will give you 
exact instructions once you add the domain — it's usually just copying 
a few numbers into your domain registrar.

---

## File structure

```
barbara-portfolio/
  index.html          ← main homepage (this is everything)
  HOW-TO-DEPLOY.md    ← this file
```

To add a new project later: just copy the project card block in index.html 
and update the text. No tools needed — just a text editor.

---

## Adding case study pages

Each project card links to e.g. `projects/multibuy.html`
Create a `projects/` folder and add HTML files for each case study.
I can build those pages for you too — just ask!
