# Vercel landing page

This is the public landing page only. It does not capture or control the PC. After your Cloudflare remote hostname is configured, edit `index.html` and replace `https://remote.YOUR_DOMAIN.com` with its exact HTTPS address.

In Vercel, import the repository/project and set **Root Directory** to `vercel-site`. Select **Other** for Framework Preset. Leave Build Command and Output Directory blank, then deploy.

Never upload `config.json`, `host/`, `.nickworks/`, or a Cloudflare tunnel token to Vercel or a Git repository.
