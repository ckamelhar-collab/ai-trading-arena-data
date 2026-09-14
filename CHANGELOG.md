# Changelog

Schema and notable changes only. Daily data refreshes are the `data: YYYY-MM-DD` commits.

## 2026-09-13 — first publish

- `data/trades.csv`: closed positions on the five ledger-published accounts (control + four model lanes) from 2026-07-27 onward, one row per position (duplicate exit fills collapsed on `lane|symbol|opened`, latest close kept).
- `data/standings.json`: since-start standings of every Arena bot, the S&P 500 buy & hold benchmark, and the update stamp.
- README written as the landing page; license CC BY 4.0.
- Daily mirror job registered on the site's build machine (`AITrading_Data_Repo_Push`, 06:25 local, after the 05:40 site build).
