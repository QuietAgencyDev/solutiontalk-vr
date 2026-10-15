# Solution Talk VR

Public site for the seated practice space from [Solution Therapy & Coaching](https://solutiontalktherapy.com/).

The page is static: `index.html`, `css/site.css`, and `assets/`. GitHub Pages serves it from the `main` branch.

## Domain

Register **solutiontalk-vr.com**, then point DNS at GitHub Pages:

| Host | Type | Value |
|------|------|--------|
| `@` | A | `185.199.108.153` |
| `@` | A | `185.199.109.153` |
| `@` | A | `185.199.110.153` |
| `@` | A | `185.199.111.153` |
| `www` | CNAME | `quietagencydev.github.io` |

After those records answer, add a `CNAME` file containing `solutiontalk-vr.com` and push it. GitHub Pages will then serve the site on that host. Turn on HTTPS in the repository Pages settings once the certificate is ready.

Until the domain is connected, the site stays at `https://quietagencydev.github.io/solutiontalk-vr/`. A `CNAME` file is not in the repo yet, so that address keeps working before the domain is registered.
