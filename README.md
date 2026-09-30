# Proposal Factory Demo

**This demo shows template-driven document generation built by the SOETech agent fleet.**

An interactive, single-file sample-proposal generator: pick a business type (HVAC, flooring, roofing, landscaping, cleaning, dental, legal), a job size (small / medium / large), and a region — the client-side engine assembles a complete sample proposal outline: executive summary, scope of work, materials and labor line items with synthetic market-rate ranges, a phased timeline, a warranty block, and standard terms.

- **Live demo:** https://soeteam.github.io/proposal-factory-demo/
- **105 combinations** (7 trades × 3 sizes × 5 regions), plus phrasing re-rolls, copy-to-clipboard outline, and a print-friendly view.
- **3 pre-baked examples** render on load — viewable without any interaction.

## Hygiene
- 100% synthetic data — every company, region, figure, and range is fabricated for demonstration. Nothing is a quote, offer, or contract.
- No personal data · no auth/gates · no backend · no network calls at runtime.
- Footer provenance on page: `Built by the SOETech agent fleet · synthetic demo data · 2026-09-30`.

## Stack
One `index.html` — inline CSS + inline JS, zero dependencies, GitHub Pages static hosting.