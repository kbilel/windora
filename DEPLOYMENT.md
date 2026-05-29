# Windora Entry Solutions Deployment

This folder is ready for GitHub Pages hosting with the custom domain:

```txt
www.windoraentrysolutions.com
```

## Files To Push

- `index.html`
- `robots.txt`
- `sitemap.xml`
- `CNAME`
- `.nojekyll`
- Logo/image assets used by `index.html`

## GitHub Pages Settings

1. Push these files to the website repository.
2. Open the repository settings.
3. Go to **Pages**.
4. Set source to the `main` branch and `/root`.
5. Set the custom domain to:

```txt
www.windoraentrysolutions.com
```

6. Enable **Enforce HTTPS** after GitHub finishes checking the domain.

## Namecheap DNS

Add these records in Namecheap Advanced DNS:

```txt
Type: CNAME
Host: www
Value: <your-github-username>.github.io
```

```txt
Type: A
Host: @
Value: 185.199.108.153

Type: A
Host: @
Value: 185.199.109.153

Type: A
Host: @
Value: 185.199.110.153

Type: A
Host: @
Value: 185.199.111.153
```

## Before Launch

Create or forward this mailbox before launch so quote requests do not bounce:

```txt
contact@windoraentrysolutions.com
```

Add a more exact city or county later if you want stronger local SEO than statewide Virginia targeting.

Also make sure `windora-logo-light.png` exists in this same folder, because `index.html` uses it for the header and footer logo.
