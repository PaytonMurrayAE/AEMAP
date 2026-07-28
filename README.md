# AE Marketing Territory Map

This folder is a complete GitHub Pages website for the AE Marketing territory map.

## Required files

- `index.html` — the complete map application and company data
- `.nojekyll` — tells GitHub Pages to serve the files directly
- `GOHIGHLEVEL-IFRAME.html` — iframe template for embedding the live site in GoHighLevel
- `UPLOAD-CHECKLIST.txt` — condensed deployment checklist

## GitHub Pages setup

1. Create a new GitHub repository.
2. Set the repository to **Public** when using GitHub Free.
3. Upload the contents of this folder to the repository root.
4. Confirm `index.html` is visible directly in the main repository file list.
5. Open **Settings > Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select branch **main** and folder **/(root)**.
8. Click **Save**.
9. GitHub will display the public Pages URL after deployment.

Expected project-site URL format:

`https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY-NAME/`

## GoHighLevel

Open `GOHIGHLEVEL-IFRAME.html`, replace the placeholder URL with the GitHub Pages URL, and paste the code into a GoHighLevel Custom HTML/JavaScript widget.

## Important data behavior

Add, Edit, and Remove actions use browser local storage. Changes remain on the same browser/device but are not written back to GitHub and are not automatically shared with other users.

## Updating the map later

Replace `index.html` in the repository and commit the change. The GitHub Pages URL and the GoHighLevel iframe do not need to change.
