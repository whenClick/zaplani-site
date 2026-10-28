# ZaPlani site

The landing page (`index.html`) and the owner's admin page (`admin/`), plain static files.
They are published as they are to the public repo whenClick/zaplani-site (GitHub Pages):
https://zaplani.com/ and https://zaplani.com/admin/ (`CNAME` names the domain). The web app is
at https://app.zaplani.com/, from the public repo whenClick/zaplani-app.

The admin page reads `GET /stats` from the free-mode server (`server/index.mjs`) with an access
code from `UNLIMITED_CODES`, sent as a bearer token; the code stays in the browser.

The «Скачать для Android» button links to the latest release of zaplani-site
(`releases/latest/download/zaplani.apk`), published by the Android APK workflow in
whenClick/ZaPlani when its signing and site secrets are set; the button stays hidden until then.
