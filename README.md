# Bear Trap Planner

Kingshot city layout around our two bear traps. Anyone with the link can find their city, see its coordinates and export the plan as a PDF. No account needed.

## Put it online with GitHub Pages (about 5 minutes)

1. Sign in at [github.com](https://github.com) and click **New repository**.
2. Name it, for example `bear-planner`, set it to **Public**, and click **Create repository**.
3. Click **uploading an existing file**, drag in `index.html` and `plan.json`, and click **Commit changes**.
4. Open **Settings → Pages**. Under **Branch**, pick `main` and `/ (root)`, then click **Save**.
5. Wait a minute and refresh. Your link appears at the top, for example
   `https://your-name.github.io/bear-planner/`.

Share that link in alliance chat or Discord.

## Updating the official plan

1. Open your planner link and make the changes (move cities, add new members, set coordinates).
2. Go to the **Map** tab and click **Save plan file**. This downloads a new `plan.json`.
3. In your GitHub repository, click **Add file → Upload files**, drag in the new `plan.json` and click **Commit changes**.

Everyone sees the new plan within a few minutes. You never need to touch `index.html` again.

## Good to know

- Changes other people make stay on their own device. They never change the official plan.
  The top bar shows **Your changes, on this device only**, with a **Back to official plan** button.
- When you upload a new `plan.json`, people who were looking at the old official plan get the new one automatically.
- `index.html` also holds a built-in copy of the plan, so the page still works if you open the file directly from your computer.
