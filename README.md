# FangloSpirit storefront

Responsive storefront recreation based on the supplied Anglo Spirit Figma homepage and product page frames. Product photography in the gallery has been recreated with FangloSpirit branding.

## Run locally

```bash
npm install
npm run dev
```

`npm run build` creates the static Vite build for Vercel.

## Routes

- `/` — homepage
- `/products/kendal-mint-4mg` — product page
- `/collections/all` — catalogue
- `/pages/contact` — contact
- `/pages/affiliates` — affiliates
- `/blogs/news` — news index
- `/policies/refund-policy`, `/policies/privacy-policy`, `/policies/terms-of-service`, `/pages/shipping-delivery` — information pages

## Integration needed before taking orders

The cart stores selections locally in the browser. Checkout, contact form submission, newsletter subscriptions, order fulfilment, and customer accounts need a commerce and messaging backend. The published policy pages are layout content and require business and legal review before using the site for real transactions. Contact email addresses and social handles currently match the source website and need replacement if FangloSpirit uses different accounts.
