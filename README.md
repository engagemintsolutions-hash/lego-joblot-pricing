# LEGO Joblot Pricing Tool

A pricing helper for UK eBay LEGO joblot resellers. Estimates fair
value of mixed-content auction lots to inform purchasing decisions
against a defined ROI target.

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

## Data use

Sold-listing data is used strictly for internal pricing decisions —
not redistributed, not resold, not exposed in any public-facing UI,
and never shared with third parties.
