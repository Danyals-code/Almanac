# Putting the website online

Do this once. It takes about ten minutes. At the end you have the privacy and support links App Store Connect asks for.

## What goes in the new repo

Upload these five files from `release/website/`. Nothing else is needed:

| File | What it is | Edit before uploading? |
|---|---|---|
| `README.md` | Describes the repo. It isn't shown on the website. | No |
| `_config.yml` | The site's title and theme | No |
| `index.md` | Home page: what the app does, with links | No |
| `privacy.md` | Privacy policy | **Yes:** your email, on the last line |
| `support.md` | Support page and common questions | **Yes:** your email, near the top |

Don't upload this file (`website-setup.md`) or anything else from `release/`.

## Step 1: add your email

In `privacy.md` and `support.md`, replace `YOUR-EMAIL-HERE` with the address people should write to. A separate address is a good idea, for example a new Gmail such as `almanac.app.support@gmail.com`. It will be public, so expect some spam.

## Step 2: create the repo

1. On github.com, click **+** (top right), then **New repository**.
2. **Repository name:** `almanac`
3. Choose **Public**. GitHub Pages is free only for public repos, and Apple's reviewers must be able to open the pages.
4. Leave "Add a README" unticked, then click **Create repository**.

## Step 3: upload the files

1. On the new repo's page, click **uploading an existing file**.
2. Drag in the five files from `release/website/`.
3. Click **Commit changes**.

## Step 4: turn on GitHub Pages

1. In the repo, open **Settings**, then **Pages** in the left column.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Set **Branch** to **main** and the folder to **/ (root)**, then click **Save**.
4. Wait a minute or two, then reload the page. A box appears: "Your site is live at https://danyals-code.github.io/almanac/".

## Step 5: check the pages

Open each one and check that your email shows:

- https://danyals-code.github.io/almanac/
- https://danyals-code.github.io/almanac/privacy/
- https://danyals-code.github.io/almanac/support/

If a page shows "404", wait a few more minutes. The first build can be slow. You can follow it under the repo's **Actions** tab.

## Step 6: paste the links into App Store Connect

| Where in App Store Connect | Paste |
|---|---|
| **App Privacy** → Privacy Policy URL | `https://danyals-code.github.io/almanac/privacy/` |
| **iOS App 1.0** → Support URL | `https://danyals-code.github.io/almanac/support/` |
| **iOS App 1.0** → Marketing URL (optional) | `https://danyals-code.github.io/almanac/` |

If your GitHub username isn't `Danyals-code`, use yours instead. The address is always `https://<username>.github.io/almanac/`, in lower case.

## Later

- **When the stars app comes:** make a second repo the same way (for example `ancient-skies`) with its own privacy and support pages.
- **A custom domain** (for example `almanac.app`) can be added later under Settings → Pages → Custom domain. If you do, update the links in App Store Connect too.
