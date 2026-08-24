# My Blog

A minimal, static blog. No build step, no frameworks — just HTML and CSS.

## Structure

```
index.html        homepage / post list
about.html         about page
style.css          shared stylesheet
posts/
  post-1.html      example post
  post-2.html      example post
```

## Adding a new post

1. Copy `posts/post-1.html` to `posts/post-3.html` (or any name you like).
2. Edit the title, date, and body content.
3. Add a matching `<li>` entry at the top of the list in `index.html`.

## Hosting on GitHub Pages

1. Push this folder to a GitHub repository.
2. Go to the repo's **Settings → Pages**.
3. Under "Build and deployment", set **Source** to "Deploy from a branch".
4. Choose the branch (usually `main`) and the `/ (root)` folder, then save.
5. Your site will be live at `https://<username>.github.io/<repo-name>/`
   within a minute or two.

No further configuration is needed — it's plain HTML/CSS with no dependencies.
