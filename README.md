# Dell Master Worklist – Static Deploy (Vanilla)
Ready to deploy to Netlify or Vercel.
- **No build step** required.
- Single file: `index.html`

## Netlify (fastest)
- Go to https://app.netlify.com/drop
- Drag this whole folder (or the ZIP) onto the page
- You’ll get a live URL instantly

## Netlify (site)
- New site from Git → Select your repo
- Build command: _none_
- Publish directory: `.`

## Vercel (Git import)
- Create a GitHub repo with this folder
- Go to https://vercel.com/new → Import the repo
- Framework preset: **Other** (static)
- Build command: _none_
- Output directory: `.`

## Vercel (CLI)
- `npm i -g vercel`
- `vercel --prod` in this folder
