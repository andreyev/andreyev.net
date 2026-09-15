# andreyev.net

Source for [andreyev.net](https://andreyev.net) — a one-page personal site
styled as a fake Apache `mod_autoindex` directory listing, linking out to
various profiles (GitHub, Instagram, Strava, LinkedIn, Letterboxd, Goodreads,
Instapaper) and a contact email.

## How it works

- `index.md` is the entire page: a Markdown table dressed up to look like a
  raw `Index of /public_html/` listing.
- Served via [GitHub Pages](https://pages.github.com/) with Jekyll.
  `_config.yml` disables the default theme so the page renders unstyled,
  preserving the raw-directory-listing look instead of being wrapped in
  Jekyll's Minima theme.
- `CNAME` points the custom domain at GitHub Pages.

## License

Content is licensed under [CC BY 4.0](LICENSE).
