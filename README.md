# dtmbr

Redesigned (2023) companion website to the book Design Think Make Break Repeat.

This website is built using Jekyll and published on GitHub Pages. Commits to the `main` branch will cause the website to be rebuilt.

To update text on the home page of the website, edit the relevant part of `_data/site-parts.yaml`.

The rest of the website's content lives in `pages/`.

Method pages are stored in `pages/toolkit`. They use custom YAML fields and expect a banner image 800px by 300px with the same basename as the method's Markdown file, in `assets/images/toolkit/`. Method templates and other attachments should be saved to `resources/`. The easiest way to create a new method is to copy and edit an existing one.
