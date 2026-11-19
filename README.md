# NIRHALIs Audio & Wire — Shopify Theme

Storefront: https://audioandwire.nirhalisdevelops.com

**GitHub theme branch:** `shopify-theme` (full Shopify-compatible theme structure at repository root).

**Source:** Shopify theme `NAW — Cart Trust & Payment Confirmation` (ID `192946241848`). The GitHub branch includes the approved **Better Together. Better Value.** homepage highlights, current Audio & Charge, Durability and Everyday Charge bundle images/prices, plus relevant product-page pairing links.

## Connect to Shopify (manual account authorization required)

1. Shopify Admin → **Online Store → Themes**.
2. Theme library → **Add theme → Connect from GitHub**.
3. Authorize Shopify's GitHub app for `NIRHALIsDigital/NIRHALIs-Audio-Wire` when prompted.
4. Select account `NIRHALIsDigital`, repository `NIRHALIs-Audio-Wire`, branch **`shopify-theme`**.
5. Shopify will add an **unpublished** connected theme. Preview the home, product and bundles pages on desktop/mobile and check cart, settings and checkout behaviour.
6. Only after verification, publish the connected theme. Subsequent edits sync bidirectionally between Shopify and GitHub.

**Important:** Updating GitHub alone does not replace the current live Shopify theme until this branch is connected and its theme is published.

## Merchandising safeguards

All bundles are intended to be previewable, but unavailable for purchase until CompuTech validates component stock and fulfilment. Do not enable overselling or fabricate stock when connecting the theme.

## Repository security

This repository is **public**. Theme source and settings are visible to anyone; consider making the repo private before enabling ongoing two-way sync. The settings file was scanned for obvious tokens/password patterns and email addresses, but this is not a comprehensive secret audit. Never store private customer information or API credentials in a Shopify theme.

Shopify's GitHub integration documentation: https://shopify.dev/docs/storefronts/themes/tools/github
