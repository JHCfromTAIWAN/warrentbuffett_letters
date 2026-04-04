# Warren Buffett Letters (1956–2025)

A curated collection of **91 documents** by Warren E. Buffett, focusing on value investing philosophy and methodology.

## Scope

- **Buffett Associates Partnership Agreement (1956)**: The founding document
- **Buffett Partnership Letters (1957–1969)**: 32 letters to limited partners of Buffett Partnership, Ltd.
- **Berkshire Hathaway Shareholder Letters (1970–2025)**: 58 letters to shareholders of Berkshire Hathaway Inc.

## Curation Principle

This collection focuses on letters with **substantive investment discussion** — investment philosophy, valuation methodology, portfolio management, business analysis, and market commentary. Purely administrative letters (e.g., tax filing instructions) are excluded.

### Excluded Letters

The following 2 letters from [rbcpa.com](https://www.rbcpa.com/warren-e-buffett/buffett-letters-1959-present/) are **not included** because they contain only tax filing instructions with no investment content:

- **1962-12-24** — Tax information letter to limited partners
- **1963-12-26** — Tax information letter to limited partners

Interested readers can find them at: https://www.rbcpa.com/warren-e-buffett/buffett-letters-1959-present/

## Directory Structure

```
Warren Buffett Letters(1956-2025)/
├── letters-en-source/   # Original source files (HTML, PDF, EPUB extracts)
├── letters-en-pdf/      # All letters in PDF format (text-searchable)
├── letters-en-md/       # All letters in Markdown format
├── referance/           # Reference materials and source indexes
├── INDEX.md             # Full index table of all letters
└── README.md
```

## File Naming Convention

```
{FiscalYear}_Letter({N})_{SigningDate}.{ext}
```

- **FiscalYear**: The fiscal year the letter covers (e.g., `1957`, `2024`)
- **Letter(N)**: Sequence number when multiple letters exist for the same fiscal year (omitted if only one)
- **SigningDate**: Date the letter was signed in `YYYYMMDD` format

Examples:
- `1957_Letter_19580201.pdf` — FY1957 annual letter, signed Feb 1, 1958
- `1962_Letter(2)_19621101.pdf` — FY1962 second letter, signed Nov 1, 1962
- `2024_Letter(1)_20241125.pdf` — FY2024 special letter, signed Nov 25, 2024

## Sources

| Source | Count | Period |
|--------|-------|--------|
| [gurufocus.com](https://www.gurufocus.com/news/126451/original-warren-buffett-partnership-agreement-found-here) | 1 | 1956 |
| [1957-1969 Complete Buffett Partnership Letters (PDF)](https://www.ivey.uwo.ca/media/2975913/buffett-partnership-letters.pdf) | 29 | 1957–1969 |
| [rbcpa.com](https://www.rbcpa.com/warren-e-buffett/buffett-letters-1959-present/) | 3 | 1966–1968 |
| [1965-2012 BH Letters to Shareholders (EPUB)](referance/1965-2012_Berkshire_Hathaway_Letters_to_Shareholders.epub) | 8 | 1970–1977 |
| [berkshirehathaway.com](https://www.berkshirehathaway.com/letters/letters.html) | 55 | 1978–2025 |

## Copyright Notice

The letters in this collection are copyrighted by Warren E. Buffett and/or Berkshire Hathaway Inc. This collection is compiled for **educational and research purposes only** under fair use principles.

Original letters are publicly available from the sources listed above. If you are the copyright holder and have concerns about this collection, please open an issue.

## Non-Buffett Letters

Letters not written by Buffett are stored separately in `letters-en-*/non-buffett/`:

- **Kenneth V. Chace** (President, Berkshire Hathaway): 5 early BH annual letters (1965–1969)
- **Charles T. Munger** (Vice Chairman, Berkshire Hathaway): 1 special letter (2014)
