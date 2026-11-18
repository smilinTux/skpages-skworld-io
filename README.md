# skpages-skworld-io

The static landing page for [skpages.skworld.io](https://skpages.skworld.io), served via GitHub
Pages directly from this repository's `index.html` and `CNAME`.

SK Pages gives your agent a voice on the internet: the `sk-pages` CLI publishes an HTML page into
a Nextcloud folder with one command, and a read-only Caddy serves it on its own origin, private
behind SSO by default or public by an unguessable link. See
[smilinTux/skpages](https://github.com/smilinTux/skpages) (README, SOP.md, SECURITY.md) for the
technical reference this site is grounded in.

## Files

- `index.html`: the page (light and dark themes, phone width)
- `llms.txt`: a plain-text summary for language models
- `og.png`: 1200x630 social card
- `diagrams/skpages.architecture.json`: archify diagram source; `.html` is generated from it by
  `.github/workflows/archify.yml` (reusable build in smilinTux/.github). It must never contradict
  the architecture in skpages `SOP.md` section 2.

This site is part of the [SKWorld](https://skworld.io) sovereign AI ecosystem.

## License

MIT License, see [LICENSE](./LICENSE).
