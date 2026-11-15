# Yasmin Ahmed Omar: portfolio

A static site: plain HTML, CSS and a little JavaScript. There is no build step, so Vercel serves it as it is.

## Files

- `index.html`: all the content (edit text here)
- `styles.css`: colours, fonts and layout (the colours are variables at the top)
- `script.js`: theme switch and copy-email button
- `Yasmin_Ahmed_Omar_Resume.pdf`: the file behind the "Download CV" buttons (replace it when you update your CV, keeping the same name)
- `favicon.svg`: browser tab icon

## Deploy on Vercel

**Option A: from GitHub (recommended, updates on every push)**

1. Create a new GitHub repository (for example `portfolio`) and upload all the files in this folder.
2. Go to vercel.com, choose **Add New > Project**, and import that repository.
3. Leave **Framework Preset** as "Other". Leave the build command and output directory empty.
4. Click **Deploy**. Your site gets a `.vercel.app` address.

**Option B: from your computer with the CLI**

```bash
npm i -g vercel
cd portfolio-site
vercel          # first deploy, answer the prompts
vercel --prod   # publish to your main address
```

## Before you share it

- Open each live demo and GitHub link once to confirm it works.
- Put your portfolio address on your CV and LinkedIn.
