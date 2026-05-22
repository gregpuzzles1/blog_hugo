# Greg's Digital Library

[![Deploy Hugo site to Pages](https://github.com/gregpuzzles1/blog_hugo/actions/workflows/hugo-pages.yml/badge.svg)](https://github.com/gregpuzzles1/blog_hugo/actions/workflows/hugo-pages.yml)

This repository is a **development and testing environment** for the actual Tech Trail Pulse website and blog at **www.techtrailpulse.com**.

It is used to prototype site updates, test theme and layout changes, refine content structure, and validate deployment workflows before changes are applied to the live website.

## Purpose

This repo exists to support safe iteration on the blog and website without directly impacting production. It serves as a sandbox for:

- testing Hugo configuration changes
- experimenting with the **Blowfish** theme
- previewing layout and styling updates
- validating deployment behavior through GitHub Actions and GitHub Pages
- organizing and refining blog content before production release

## Tech stack

- **Hugo** — static site generator
- **Blowfish** — Hugo theme used for layout and presentation
- **GitHub Actions** — automated build and deployment workflow
- **GitHub Pages** — hosting for the test/development deployment
- **CSS** — styling and appearance customization

## Environments

- **Production site:** www.techtrailpulse.com
- **Development/test deployment:** https://gregpuzzles1.github.io/blog_hugo/

## Development notes

This repository may include experimental changes, in-progress content, and configuration updates that are not yet ready for the production site.

If you are using this repo for development, treat it as the staging ground for testing before publishing finalized updates to Tech Trail Pulse.

## Deployment

This repository uses the GitHub Actions workflow shown above to build and publish the Hugo site to GitHub Pages.
