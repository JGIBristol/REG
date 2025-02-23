# Redirect to new REG website

The REG website has moved to: <https://bristol-reg.github.io>

This repo generates redirects to the new website.

## Editing the redirects

1. Edit `redirects.csv`, adding each redirect as a new row in the format: `/old_url,https://new_site/new_url`
2. Push the `main` brnach to GitHub
3. A GitHub Action will regenerate the redirect pages for you

You can also preview the redirect pages locally, by running `python generate_redirects.py` which will generate a directory `docs/`.
