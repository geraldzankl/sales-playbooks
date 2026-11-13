# Sales Meeting Playbook landing page

Static English-language landing page for `sales-meeting-playbook.geraldzankl.com`.

## Deployment (Hostinger)

1. In Hostinger, open the website **sales-meeting-playbook.geraldzankl.com**.
2. Under **Advanced -> Git**, select GitHub repository `geraldzankl/sales-playbooks`.
3. Select branch `main`. It now exists (the initial `index.html` commit was created).
4. Confirm this is the **subdomain's own** `public_html` directory and deploy.
5. Enable automatic deployment for future changes if wanted.
6. Open the live subdomain and check the displayed hero and mobile design.

Do not deploy this repository to the main `geraldzankl.com` website.

## Commerce launch checklist (NOT LIVE)

The purchase CTA is intentionally disabled until these items are done:

- Establish a connected Stripe account and create a $49 USD **one-time** checkout / Payment Link.
- Confirm which legal entity sells the digital product and add verified refund policy, terms, privacy notice and contact.
- Configure fulfillment: buyer receives authorized playbook access **only after verified Stripe payment**. A success-page redirect alone is not proof of payment.
- Important: The supplied playbooks.kickscale.com/public link is public. Merely sending this link after purchase does NOT restrict access or prevent sharing; use authenticated access or unique entitlements for a genuine paywall.
- Verify that Kickscale's promised 2-month complimentary access is supported by a real activation workflow and clearly state eligibility and terms.
- Test checkout, fulfillment, mobile UX, and Google Ads tracking/consent before enabling advertisements.

## Editing

Single static file: `index.html`. No build step required.
