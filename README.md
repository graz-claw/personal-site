# markgraziano.com

Portfolio site for Mark Graziano's development work.

## Deploy

Push to `main` and GitHub Pages will auto-deploy.

### Custom Domain

To use `markgraziano.com`:

1. **In GitHub → Settings → Pages**: Set custom domain to `markgraziano.com`
2. **In your domain registrar**: Add these DNS records:

   | Type    | Name  | Value                    |
   | ------- | ----- | ------------------------ |
   | CNAME   | www   | `graz-claw.github.io`   |
   | A       | @     | `185.199.108.153`        |
   | A       | @     | `185.199.109.153`        |
   | A       | @     | `185.199.110.153`        |
   | A       | @     | `185.199.111.153`        |

3. **Enable HTTPS** in GitHub Pages settings

## Stack

- Plain HTML + CSS (no framework)
- Google Fonts: Inter + JetBrains Mono
- Responsive, minimal, card-based layout
- Subtle animations, accent colors per project

## Projects

| Project | Link | Tagline |
|---------|------|---------|
| Bivvi | bivvi.app | Reading-focused video calls |
| Summa | summahq.com | Sales follow-up automation |
| TXR Studio | txFrstudio.com | Web-first telecom tooling |
| Everyday Chaplet | everydaychaplet.com | Prayer guidance for rosary bracelet finders |
