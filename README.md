# DiscoveryGC Markets

Standalone GitHub Pages build containing only:

- Commodity Market
- Goods Market

## Publish

Upload the contents of this folder to the root of your GitHub repository.

Then:

**Settings → Pages → Deploy from a branch → main → /(root) → Save**

The GitHub version calls Darkstat directly from client-side JavaScript.

Market calculation order:

`dedupe → median filters → consumer funds filter → producer/consumer netting → totals`
