# Forcola website

Static publisher, privacy, and support pages for apps published by Forcola.

## URLs

- `https://forcola.github.io/`
- `https://forcola.github.io/app-ads.txt`
- `https://forcola.github.io/panes/`
- `https://forcola.github.io/panes/privacy/`
- `https://forcola.github.io/panes/support/`
- `https://forcola.github.io/critter-captains/`
- `https://forcola.github.io/critter-captains/privacy/`
- `https://forcola.github.io/critter-captains/privacy/#choices` (optional App Store privacy choices URL)
- `https://forcola.github.io/critter-captains/support/`

## Local preview

Serve the repository root with any static HTTP server. The site deliberately has no build step, JavaScript, analytics, cookies, forms, or third-party embeds.

Display headings use the self-hosted Familjen Grotesk variable font under the SIL Open Font License 1.1. The licence text is included with the font asset.

## Publishing

GitHub Pages should deploy from the `main` branch and repository root. The repository must remain public on the GitHub Free plan. The root `app-ads.txt` file authorises Forcola's AdMob inventory and must remain publicly reachable at the URL above.

Critter Captains pages were prepared locally on 16 September 2026. Publish the site and verify the public URLs before submitting the app. Its policy reflects the current build: Firebase is not configured, Crashlytics collection is disabled, statistics are opt-in, local notifications are optional, and no ATT prompt is implemented. Reconcile this policy and store disclosures with the final service configuration before release.

Critter Captains was selected as the public-facing name on 16 September 2026. The `/submarines/`, `/submarines/privacy/` and `/submarines/support/` routes remain as static redirect pages with visible fallback links. Publish the new `/critter-captains/` pages and redirects together before installing an app release that uses the new URLs. No publication was performed by this rename.
