# gv-sheets

**Generated site — do not edit files here by hand.**

Public player character sheets for Marcel's Golden Vault D&D table, served via
GitHub Pages at https://liquidmasl.github.io/gv-sheets/ (one page per character
so each player bookmarks their own).

Source of truth lives in the private campaign repo:
`golden-vault/sessions/tockworths-clockworks/src/site/`
(template.html + style.css + pages/*.html fragments).

To update:

```bash
cd "~/repos/golden vault/sessions/tockworths-clockworks/src/site"
python3 build.py            # writes into ~/repos/gv-sheets/
cd ~/repos/gv-sheets && git add -A && git commit -m "..." && git push
```

Pages redeploys in about a minute.
