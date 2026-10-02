# MarkdownToPDFWebPage

Static multilingual marketing page for MarkdownToPDF PRO, built and deployed with Cloudflare Pages.

The language dropdown matches the app's 30 language and regional options. The eight
additional language dictionaries live in `additional-translations.js`, loaded before
`script.js`. Regional options reuse their language's copy. The page remembers manual
selections, otherwise follows the browser language, and supports Arabic RTL layout.

Production URL: <https://markdowntopdfwebpage.pages.dev/>

## Cloudflare Pages

Connect the repository `fan1056218492/MarkdownToPDFWebPage` to Cloudflare Pages and use:

- Framework preset: None
- Production branch: `main`
- Build command: `npm run build`
- Build output directory: `dist`
- Root directory: `/`

Deploy with:

```sh
npm run deploy
```

Wrangler may print a deployment-specific preview URL such as `https://<hash>.markdowntopdfwebpage.pages.dev`. That URL changes on every deployment. Use the fixed production URL above for sharing and product links.
