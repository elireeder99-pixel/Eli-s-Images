# Photo gallery

## Add photos
Drop images into `src/photos/`. They appear automatically, sorted by filename.
- Put a photo in a subfolder (`src/photos/landscape/`) to get a filter button for that folder.
- The title comes from the filename: `03-quiet-laneway.jpg` shows as "quiet laneway". A leading number sets the order.
- Delete the sample photos once yours are in.

## Run locally
    npm install
    npm run dev

## Deploy (free)
Cloudflare Pages: push to GitHub, create a Pages project, build command `npm run build`, output `dist`.
Or without Git: `npm run build`, then drag the `dist` folder into Netlify Drop.

Edit the title and subtitle at the top of `src/pages/index.astro`.
