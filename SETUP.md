# Mona’s Website

Based on the Academic Pages template. The original MIT license is retained in LICENSE.

## Preview locally

Run `bundle install`, then `bundle exec jekyll serve --host 127.0.0.1 --port 4001`. Open http://127.0.0.1:4001.

## Add a portrait

Place the photo in `images/mona-chopra.jpg` and set `author.avatar` in `_config.yml` to `mona-chopra.jpg`. The initials appear until a photo is configured.

## Before publishing

Confirm the exact qualification wording: the supplied text uses both “MD” and “MD / Master’s in Geriatrics”. These are not necessarily equivalent awards.

Add confirmed consultation/contact details and service availability when supplied.

Set `url` to the GitHub Pages hostname and `repository` to `OWNER/REPOSITORY`. For a project repository, set `baseurl` to `/REPOSITORY`; for `OWNER.github.io`, leave it empty.

Create a repository in your own account, add its URL as the origin remote (the template is saved as upstream), and push the site. Configure GitHub Pages to build from the repository branch and root directory.

## Content

Edit `_pages/home.md`, `_pages/services.md`, `_pages/family-support.md` and `_pages/about.md`. Navigation is in `_data/navigation.yml`; colours and spacing are in `assets/css/mona.css`.
