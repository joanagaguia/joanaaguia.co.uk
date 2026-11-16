# joanaaguia.co.uk

My portfolio site: one `index.html`, with no build step and no CMS. To update it, edit `index.html` on GitHub and commit. GitHub Pages republishes within a minute or two.

## Go live on GitHub Pages

1. Create a public repository and upload `index.html`, `CNAME` and this README.
2. In the repository, open Settings > Pages. Set Source to "Deploy from a branch", branch `main`, folder `/ (root)`, and save.
3. Under Custom domain, enter `joanaaguia.co.uk` and save.
4. At whoever manages your domain's DNS, delete the old WordPress A records (and any AAAA records) for the root domain, then add these four A records:
   - 185.199.108.153
   - 185.199.109.153
   - 185.199.110.153
   - 185.199.111.153
5. Set the `www` record to a CNAME pointing to `YOUR-GITHUB-USERNAME.github.io`.
6. DNS can take up to 24 hours. When GitHub's DNS check passes, tick "Enforce HTTPS".

Before switching, check whether WordPress also handles your domain registration or any email on the domain, so you don't lose either.
