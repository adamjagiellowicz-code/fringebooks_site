# Fringe Books — Setup

This is a real, complete site — not a mockup. It's plain HTML/CSS, so it works the moment you open `index.html` in a browser. To get the GUI editor (the "little admin panel" you asked for) actually working online and free, there's a one-time, ~15 minute setup. After that, adding a post is just filling in a form — no code, ever again.

## One-time setup (about 15 minutes)

1. **Create a free GitHub account** (if you don't have one) at github.com, and create a new repository — call it `fringe-books`.
2. **Upload these files** into that repository (drag-and-drop works on GitHub's website — no command line needed).
3. **Create a free Netlify account** at netlify.com, and connect it to that GitHub repository ("Add new site → Import an existing project").
4. In Netlify, go to **Site settings → Identity** and click **Enable Identity**. Then go to **Identity → Services** and enable **Git Gateway**. This is what lets the little editor panel (`/admin`) securely save posts back to your GitHub repo.
5. Under **Identity**, invite yourself as a user (your own email) — this becomes your login for the editor.
6. Your site is now live at a free Netlify address (like `fringe-books.netlify.app`) — you can point your own domain at it later, free, whenever you buy one.

## Using it day-to-day

- Go to `yoursite.netlify.app/admin` and log in.
- Click **New Note & Review**, fill in the title, author, excerpt, and body.
- Click **Publish** — it appears on the site within about a minute.

## Files in this folder

- `index.html` — homepage, lists all posts
- `about.html`, `submit.html` — the two static pages
- `posts/` — where each post lives (the editor creates these for you automatically once set up)
- `admin/` — the editor GUI itself and its configuration
- `css/style.css` — all the design/styling, in one file

## What this gives you vs. every platform we ruled out

- **$0/month, forever**, not a trial.
- **You own every file** — this isn't hosted inside a proprietary system, it's just files, so moving hosts later or adding a storefront is a normal technical step, not a migration nightmare.
- **A real GUI for posting** — you never touch code after today.
