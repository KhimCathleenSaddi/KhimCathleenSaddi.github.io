# Khim Cathleen Saddi — Research Portfolio

This is the source for the Jekyll-powered portfolio website.

## Edit website content

Edit the Markdown source files in the repository root:

- `index.md` contains the homepage, including the introduction, research themes, projects, publications, education, and contact text.
- `projects.md` contains project descriptions.
- `publications.md` contains the publication list.
- `educationandtraining.md` contains education and training details.
- `memberships.md` contains professional membership details.

The homepage uses HTML tags to preserve its section layout and styling. You can edit the text inside those tags while leaving the tags and their attributes in place. The other pages use regular Markdown; use `#` for headings, `-` for list items, and `**text**` for bold text.

Avoid editing the generated `_site/` files; Jekyll recreates them from these sources when the site is built.

## Build locally

Install Ruby and Bundler, then install the project dependencies:

```sh
bundle install
```

Build the site into `_site/`:

```sh
bundle exec jekyll build
```

To preview the site locally with live reload, run:

```sh
bundle exec jekyll serve
```

Then open the local URL printed by Jekyll (usually `http://127.0.0.1:4000`).
