# TowFinderMethod

Deployment trigger: GitHub connected to the existing Vercel production project.

## Vercel Web Analytics

Web Analytics is enabled for this static HTML deployment using Vercel's built-in analytics script already included in `index.html`:

```html
<script>
window.va=window.va||function(){(window.vaq=window.vaq||[]).push(arguments)};
</script>
<script defer src="/_vercel/insights/script.js"></script>
```

Because this repository is a static HTML site rather than a Next.js app, no `npm i @vercel/analytics` package install is required for the current deployment.
