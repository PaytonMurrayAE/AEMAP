# AE Marketing Territory Map

GitHub Pages-ready version of the AE Marketing territory map with Add Company and Remove Company controls.

## Publish

1. Create a new GitHub repository.
2. Upload the contents of this folder so `index.html` is at the repository root.
3. Open **Settings > Pages**.
4. Choose **Deploy from a branch**.
5. Select **main** and **/(root)**, then Save.
6. Use the Pages URL shown by GitHub.

## GoHighLevel iframe

Replace both placeholders in `GOHIGHLEVEL-IFRAME.html` with your GitHub username and repository name, then paste it into a GoHighLevel Custom HTML widget.

## Data behavior

The original company data is embedded in `index.html`. Companies added or removed through the map are saved in the current browser's localStorage. Those edits do not modify the GitHub repository and are not shared across browsers or users.
