# stylesense-legal

GitHub Pages site serving StyleSense legal pages.

## Current state

- **Privacy Policy** — moved to <https://stylesense.sabarishraja.com/privacy>, served by the
  `landing/app/privacy/` route in the main StyleSense repo. `privacy-policy.md` here is now a
  redirect stub only, kept so links already in the wild keep working. GitHub Pages cannot issue
  a real 301 without a custom domain, so it uses a canonical link plus a meta refresh.
- **Account & Data Deletion** — still served from here at `/account-deletion`. This is the URL
  submitted to Google Play as the required account-deletion page, so **do not remove it** until
  an equivalent route exists on the main site.

Contact address for both pages: `privacy@sabarishraja.com`.
