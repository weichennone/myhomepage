# Wei Chen - Academic Website

Personal academic website built with Jekyll and hosted on GitHub Pages.

## Structure

- `index.html`: homepage and selected work
- `research/`: research overview
- `publications/`: complete publication list
- `_data/publications.yml`: structured publication records
- `projects/`: demonstrations index
- `_projects/`: standalone project pages and assets
- `writing/`: Blog page; Markdown posts belong in `_posts/`
- `photography/`: Personal interests page
- `_sass/_style.scss`: responsive visual system

## Local preview

Install Ruby, Jekyll, and Bundler, then run:

```powershell
gem install jekyll bundler
jekyll serve --livereload
```

Open `http://localhost:4000/myhomepage/`.

## Add content

Add publications to `_data/publications.yml`. Add blog posts as `_posts/YYYY-MM-DD-title.md` files with `title` and `description` front matter. GitHub Pages rebuilds the site after changes are pushed.
