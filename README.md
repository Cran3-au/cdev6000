# OSHC prototype: GitHub Pages upload

This folder contains the built static site. The payment flow is simulated; it does not take payments or issue insurance policies.

## Publish using GitHub's website

1. Create a new GitHub repository with a `main` branch.
2. Choose **Add file → Upload files** and drag **everything inside this folder** into the upload area. Keep the `assets/` and `option-icons/` folders intact. Commit the upload to `main`.
3. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select **main** and **/(root)**, then save.
4. Wait for GitHub Pages to publish the site. The URL appears in **Settings → Pages**.

The site uses relative asset paths, so it can be hosted under any GitHub repository name. To update it later, rebuild from the separate source project and replace these generated files.

Before making the repository public, confirm you have permission to publish the supplied images and brand marks.
