# LEGO Joblot Pricing Tool

A pricing helper for UK eBay LEGO joblot resellers. Estimates fair
value of mixed-content auction lots so the user can place informed
bids targeting a defined ROI.

## Inputs

- Active auction listings from eBay Browse API
- Reference catalogue prices from BrickLink
- Recent sold-listing comps (eBay Marketplace Insights)

## Output

A recommended max-bid per listing, sized to hit the user's ROI target
after subtracting eBay final-value fees and postage.

## Status

Active development, single-user (the developer). UK marketplace only.
Internal tool — not a public service.
