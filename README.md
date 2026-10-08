# hirakonline.com

Home page for [hirakonline.com](https://hirakonline.com): a static page that
links to each utility living on its own `*.hirakonline.com` subdomain.

Plain HTML and CSS, no build step. Served as static assets by the Cloudflare
Worker `hirakonline-apex`.

## Deploy

    npx wrangler deploy

`.assetsignore` keeps repo-only files (README, git files, wrangler config) off
the live site.
