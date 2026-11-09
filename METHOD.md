# Method

Edition 2026-11. All data read on 9 November 2026.

| Store | How the data was read |
|---|---|
| Figma Community | Figma search API with the paid filter, about 80 queries; price and purchase_count per plugin. |
| JetBrains Marketplace | Plugin search API (paid and freemium, by downloads), the price endpoint and the version list. |
| Apify Store | Store API: top 100 by popularity and 18 keyword searches. |
| WordPress.org | Plugin info API, 23 searches. |
| Gumroad | Discover search, then sales_count from each product page. |
| Chrome Web Store, Google Workspace | Search pages, then each detail page. |
| Atlassian Marketplace | REST API v2, paid apps by installs. |
| GitHub Marketplace | Listing pages for 300 apps. |
| Smithery | Registry API, 5 pages of 100. |

Gross proxy = purchase or sales count x current list price, before fees, tax and refunds. For subscriptions the count may include renewals. Gumroad sellers can hide their counts; those rows stay with an empty count.

No descriptions, screenshots or reviews were copied. Emails were removed. People's names appear only where a person is the listed publisher.
