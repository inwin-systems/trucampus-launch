# TruCampus launch page

Static launch page for GitHub Pages with a Buttondown email signup form. The form collects a required name and email address.

## Before publishing

1. Create a Buttondown account at <https://buttondown.com>.
2. Copy your Buttondown username.
3. In Buttondown, create a custom subscribe-form input with key `name`, label `Name`, type free text, and required enabled. This matches the `metadata__name` field in `index.html`.
4. In `index.html`, replace `YOUR_BUTTONDOWN_USERNAME` in the form `action` URL.
5. Create a GitHub repository (for example, `trucampus.com`) and push the contents of this folder to its `main` branch.

## GitHub Pages

In the repository, open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.

Add `trucampus.com` under **Custom domain**, enable **Enforce HTTPS** when it becomes available, and follow the Namecheap DNS instructions provided with this project.

## Form behavior

Buttondown uses double opt-in by default, so subscribers must confirm their email address. Do not place subscriber data or API keys in this repository.
