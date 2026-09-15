# M-T425-V3 — Prior-state reconciliation notes (intentionally stale)

Prepared 2026-09-14 before the current source audit.

- A prior concept grouped visual feed posts and carousels together under “Projects”; this is no longer approved.
- The old navigation named only “Work” and “Motion”; it lacks a Carousel destination.
- The prior card model had optional `sourceUrl` and did not require a direct original link on every featured card. The approved brief now requires it.
- Asset availability was assumed from a thumbnail alone. Treat thumbnail-only, expired, or inaccessible media as an exception; do not mask it with a broken image.
- No reliable reach/video-view totals were stored in this artifact. Re-query valid insights and disclose omissions.
- Do not treat any format label in this note as authoritative. Use Instagram `media_type` and `media_product_type`, and inspect carousel children.
- This is not implementation guidance and not a completed analysis; it exists to create reconciliation work for the portfolio build.