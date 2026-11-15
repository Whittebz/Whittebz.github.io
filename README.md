# Whittebz Workspace MCP

Public application homepage and privacy policy for Whittebz’s personal Google Drive / Google Slides MCP integration.

- Homepage: https://whittebz.github.io/
- Privacy policy: https://whittebz.github.io/privacy.html
- Hosting: GitHub Pages, `main` branch, repository root. Plain HTML/CSS; no build dependencies.

The app name in Google Auth Platform → Branding should match **Whittebz Workspace MCP**. The site describes the Drive and Slides scopes currently granted to the integration. Keep the scope descriptions and data-handling disclosures aligned with the actual MCP and AI-provider configuration.

## Google Search Console verification

1. Sign in at https://search.google.com/search-console using the Google account that is an Owner or Editor of the OAuth application’s Cloud project.
2. Add a **URL prefix** property: `https://whittebz.github.io/` (not a DNS Domain property).
3. Choose the **HTML file** verification method and download the file Google provides.
4. Add that exact `google….html` file to this repository’s root, commit, and push to `main`. Do not rename it or change its contents.
5. After Pages deploys, verify that `https://whittebz.github.io/google….html` returns the exact Google verification text; then click **Verify** in Search Console.
6. Alternatively, choose **HTML tag** and add the exact `<meta name="google-site-verification" content="…">` tag to the `<head>` of `index.html`.
7. Keep the verification file/tag in place. Search Console can recheck it later.

A verification tag or HTML file is intentionally public. OAuth credentials and tokens are not: never add those to this repository.

## Google Auth Platform links

In Branding, use:

- Application home page: `https://whittebz.github.io/`
- Privacy policy: `https://whittebz.github.io/privacy.html`
- Authorized domain: `whittebz.github.io` (if accepted by the Console)

Search Console ownership verification and OAuth brand / scope review are separate steps. Follow any specific findings shown in Google Auth Platform. This repository does not assert that the app has passed Google verification.
