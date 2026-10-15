# Trading Journal Analytics | Power BI

A personal analytics project built to organize trading records and review trading performance through an interactive Power BI report.

> **Portfolio-safe release:** Real account history and personal trading records are intentionally not included. Before publishing a `.pbix` file or screenshots, replace private records with synthetic/demo data and check every page for account balances, broker details, trade timestamps, and personal notes.

## Project goals

- Organize trade records in a consistent journal structure.
- Review profit and loss (P/L) across trade type, weekday, and recorded emotions.
- Compare analysis, execution, and management quality scores.
- Turn journal entries into an interactive report for performance review.

## Report pages

The current report is organized into three pages:

- **Overview** – high-level view of trading activity.
- **Performance Analysis** – performance-focused analysis.
- **Trade Analysis** – trade-level comparisons, including visuals for P/L by emotion, P/L by day of week, P/L by trade type, and quality performance.

The visuals and labels may evolve as the project is refined.

## Tools

- Microsoft Power BI
- Power Query for data preparation and transformation
- Microsoft Excel as the journal data source

## Data model / workbook areas

The workbook/report currently uses trade records alongside supporting calendar, quality, and session mapping data. The public repository should use a synthetic dataset with the same relevant column structure; actual personal trading records should remain private.

## Current analysis themes

- Profit and loss by recorded emotion
- Profit and loss by weekday
- Profit and loss by trade type
- Quality scores for analysis, execution, and management
- Standardized emotion and mistake categories (being refined)

## How to explore

1. Open the report in Power BI Desktop (once a sanitized demo `.pbix` is published).
2. Review each report page and interact with the visuals and filters.
3. Use the demo dataset only; do not connect the published report to a private trading account or personal journal file.

> The `.pbix` and sample dataset are intentionally omitted from this starter package. Add them only after replacing private records with synthetic data and verifying that no credentials, account identifiers, or personal notes are embedded.

## Planned improvements

- Complete and validate standardized mistake categories.
- Improve emotion categorization for consistent analysis.
- Add a public demo dataset and report screenshots using synthetic data.
- Document data refresh and source configuration.

## Disclaimer

This project is for personal performance analysis and portfolio demonstration. It is not financial advice and does not guarantee trading results.
