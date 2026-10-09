# AUREN — Modern Lifestyle Storefront

A premium responsive ecommerce concept built to demonstrate storefront design and Shopify Storefront API integration.

## Preview locally
Open `index.html` in a browser, or run `python -m http.server 8000` from this folder and visit `http://localhost:8000`.

## Included
- Responsive editorial-style storefront
- Product category filters, search and sorting
- Cart drawer, quantity controls and subtotal
- Demo catalog when Shopify is not configured
- Shopify Storefront API product loading and Shopify-hosted checkout flow
- Newsletter signup UI placeholder

## Connect Shopify
1. Configure a public Storefront API access token for your Shopify custom storefront.
2. Edit `shopify-config.js` and set `domain` to your shop domain (such as `your-store.myshopify.com`) and `storefrontAccessToken` to your public Storefront API token.
3. Confirm Storefront API permissions allow product reads and cart creation.
4. Deploy over HTTPS and test product loading, cart creation, checkout, variants, prices, tax and shipping with the real catalog.

**Never put a Shopify Admin API token, private app secret or password in this frontend.**

## Demo limitations
- Demo product titles, prices and imagery are illustrative and not purchasable.
- Live checkout requires valid Shopify configuration and products with purchasable variants.
- Newsletter form is UI-only until connected to a consent-aware email provider.
- AUREN is a fictional demo identity. Replace the name, content, policies and contact details before using this for a client.
- Verify all product images and licenses, accessibility, responsive behavior, and Shopify API version before production.

## Deploy
Static site: deploy the repository root to Vercel, Netlify, or another static host. No build step is required.