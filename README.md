# firas-bchir.github.io

Personal website of Firas Bchir, served by GitHub Pages from the `main` branch (a push goes live in about 30 seconds).

## When the page changes

1. Update `dateModified` in the JSON-LD of `index.html` (a full date-time with time zone, e.g. `2026-11-26T20:45:00+01:00`).
2. Update `<lastmod>` in `sitemap.xml` to the same value.
3. If a fact changed (role, project, link), change it in `llms.txt` too.
4. After pushing, tell IndexNow (Bing, Yandex, Naver, Seznam):
   `curl -s -o /dev/null -w "%{http_code}\n" "https://api.indexnow.org/indexnow?url=https://firas-bchir.github.io/&key=96e80e128a5875512f5672c6b6a8f194"` (200 or 202 = received).

## Never delete

- `google9eaa05b3c8c27899.html`: proves ownership in Google Search Console.
- `96e80e128a5875512f5672c6b6a8f194.txt`: the IndexNow key.
- A changed link-preview picture gets a new file name (WhatsApp and Facebook cache pictures by address).
