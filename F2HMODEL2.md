# F2H · Funds for Hustlers

A two-sided student marketplace: Work Pool, Prep Work, Tier Work, Tutor Desk, Group Pool, Explore (rent things or offer services) and a My Work tracker, with five-star ratings.

## Run it

Open `index.html` in any browser. It works on its own: data is saved in the visitor's browser (sample tasks and people are included). Call `f2hResetDemo()` in the console to reset.

## Important

The live features (shared tasks, ratings, groups, listings, sign-in details) were built on Claude's artifact database. Outside Claude, for example on GitHub Pages, the page loads and looks the same, but it shows "The live marketplace is not connected" and cannot save anything. To make it work for real users, connect it to a backend such as Firebase or Supabase.

## Publish with GitHub Pages

1. Push this folder to a GitHub repository.
2. In the repository, open Settings, then Pages.
3. Under Build and deployment, choose Deploy from a branch, pick `main` and `/ (root)`, then Save.
4. After a minute the site is live at `https://YOUR-USERNAME.github.io/YOUR-REPO/`.
