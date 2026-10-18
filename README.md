# ZaPlani site

The landing page (`index.html`) and the owner's admin page (`admin/`), plain static files.
They are published as they are to the public repo whenClick/zaplani-site (GitHub Pages):
https://whenclick.github.io/zaplani-site/ and https://whenclick.github.io/zaplani-site/admin/.

The admin page reads `GET /stats` from the free-mode server (`server/index.mjs`) with an access
code from `UNLIMITED_CODES`, sent as a bearer token; the code stays in the browser.
