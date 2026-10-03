# Alya Aulia

A warm, playful personal website, made with love for our first child.

Static HTML and CSS, with an illustrated garden. No build step needed. The name and copy are an initial draft; edit `index.html` to personalize them.

## Preview

Run `python3 -m http.server 8000` and open http://localhost:8000.

## Hosting

GitHub Pages publishes the root of the `main` branch. Changes pushed to `main` automatically publish.

## Custom domain

First add your domain under repository Settings → Pages → Custom domain. Then configure these DNS records at your DNS provider:

| Type | Name | Value |
| --- | --- | --- |
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | rendybjunior.github.io |

For another subdomain such as `alya.example.com`, use a CNAME named `alya` pointing to `rendybjunior.github.io` instead of the apex A records. Do not include the repository name in the DNS target. Keep unrelated mail records intact. After DNS resolves and GitHub provisions a certificate, enable Enforce HTTPS in Pages settings.

Official guide: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site
