# slipsend_page

Marketing site for SlipSend at https://slipsend.app. Static HTML and CSS, no build step, no JavaScript, no third-party requests.

Pages required by the stores: `/privacy`, `/support`.

Deploys to GitHub Pages from `main` (`.github/workflows/pages.yml`). `CNAME` binds `slipsend.app`.

Palette and typography follow the app: graphite, warm neutrals, indigo accent. Every text pair is AAA (7:1) in light, dark, and `prefers-contrast: more`. The header band is always navy so the white ribbon S in the logo stays visible.

Store listing rule: "Concur" and "Workday" appear only in descriptive copy ("works with SAP Concur and Workday Expenses email receipts"), never in names or titles.
