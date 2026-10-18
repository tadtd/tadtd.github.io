# tadtd.github.io
## tadtd blog

This is a bilingual Hugo blog. Write pages and posts in Markdown under:

- `content/en/` for English, the default language
- `content/vi/` for Vietnamese

The HTML templates live in `layouts/`, and custom CSS lives in `static/css/`.
The `public/` directory is generated output and should not be edited manually.

There is no theme dependency: the site uses the templates in `layouts/`.

### Preview locally

```powershell
hugo server
```

Open `http://localhost:1313/`.

### Build the site

```powershell
hugo
```

To create a new English post:

```powershell
hugo new content/en/posts/my-post.md
```

To add its Vietnamese translation, create
`content/vi/posts/my-post.md` with the same `translationKey`.
