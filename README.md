# Bear Blog Theme

This repo contains my custom Bear Blog theme files:

- `styles.css` for the full visual style
- `header.html` for `<head>` additions (fonts, preconnects)
- `footer.html` for footer markup + behavior scripts

## Quick setup (Bear Blog)

1. Open **Theme -> Edit theme CSS** and paste the contents of `styles.css`.
2. Open **Settings -> Header and footer directives -> Head directive** and paste `header.html`.
3. Open **Settings -> Header and footer directives -> Footer directive** and paste `footer.html`.

That is it. Save, refresh your site, and the theme should be live.

## Notes

- `footer.html` includes extra footer links (`/privacy-policy/` and `/terms-use/`) at the top. Change or remove them if your routes are different.
- The header loads Google Fonts (`Literata`), and the CSS also references `Source Code Pro` and `Work Sans`.

## License

MIT. See `LICENSE`.
