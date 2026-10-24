# Cargo Finance documentation

Source for the Cargo Finance docs (Mintlify): how Cargo brings real-world assets on-chain (soft commodities such as cocoa, coffee and sugar, precious metals such as gold), the vault mechanism, batch auctions, safety and FAQs, plus the Genesis Vault (cvCOCOA, West African Grade 1 cocoa priced off ICE London Cocoa) and its Genesis Auction.

Docs: [https://cargo-finance.mintlify.app](https://cargo-finance.mintlify.app)

## Editing

- Pages are `.mdx` files; navigation lives in `docs.json`.
- Preview locally with `npx mint dev`, and check links with `npx mint broken-links`.
- Work on a branch and open a pull request. Merging into the deployment branch (set in the Mintlify dashboard, usually `main`) publishes the site.
- Write platform pages for real-world assets in general; cocoa details belong only where a page describes the Genesis Vault.
- Describe the Genesis Vault as West African Grade 1 cocoa priced off ICE London Cocoa. Do not name countries, ports or warehouses outside the legal and eligibility notes.
