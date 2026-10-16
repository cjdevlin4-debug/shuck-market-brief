# SHUCK Market Brief Source

> Canonical sanitized source for scheduled SHUCK grain intelligence.

**Preferred market:** WGM Prentice

**Latest verified report date:** 2026-10-15

**Source status:** Current

**Source state:** `current`

**Source message:** Latest WGM market data was successfully collected and verified.

**Latest checked at:** 2026-10-16T00:21:50.11518+00:00

**Latest verified at:** 2026-10-16T00:21:50.11518+00:00

**Public brief generated at:** 2026-10-16T00:31:43.689986+00:00

## Corn

| Delivery | Cash | Basis | Futures | Futures Price | Cash Strength | Basis Strength | Prentice Competitiveness | Regional Signal | Prior State Date | Cash Change | Basis Change | Futures Change |
|---|---:|---:|---|---:|---|---|---|---|---|---:|---:|---:|
| Oct 26 | $4.42 | -0.36 | CZ26 | $4.78 | Extremely high | Weak | Weak | MATERIAL_DISAGREEMENT | 2026-10-14 | -0.03 | 0.00 | -0.03 |
| Nov 26 | $4.47 | -0.31 | CZ26 | $4.78 | Extremely high | Weak | Competitive | MATERIAL_DISAGREEMENT | 2026-10-14 | -0.03 | 0.00 | -0.03 |
| Dec 26 | $4.62 | -0.16 | CZ26 | $4.78 | Extremely high | Slightly weak | Very strong | MATERIAL_DISAGREEMENT | 2026-10-14 | -0.03 | 0.00 | -0.03 |
| Jan 27 | $4.65 | -0.26 | CH27 | $4.91 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Feb 27 | $4.68 | -0.23 | CH27 | $4.91 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Mar 27 | $4.71 | -0.20 | CH27 | $4.91 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Apr 27 | $4.74 | -0.24 | CK27 | $4.98 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| May 27 | $4.77 | -0.21 | CK27 | $4.98 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Jun 27 | $4.80 | -0.23 | CN27 | $5.04 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Jul 27 | $4.80 | -0.23 | CN27 | $5.04 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |

## Soybeans

| Delivery | Cash | Basis | Futures | Futures Price | Cash Strength | Basis Strength | Prentice Competitiveness | Regional Signal | Prior State Date | Cash Change | Basis Change | Futures Change |
|---|---:|---:|---|---:|---|---|---|---|---|---:|---:|---:|
| Oct 26 | $11.92 | -0.71 | SX26 | $12.63 | High | Normal | Very weak | CONSISTENT | 2026-10-14 | -0.14 | 0.00 | -0.14 |
| Nov 26 | $12.27 | -0.36 | SX26 | $12.63 | High | Normal | Slightly strong | CONSISTENT | 2026-10-14 | -0.14 | 0.00 | -0.14 |
| Dec 26 | $12.45 | -0.33 | SF27 | $12.78 | High | Normal | Very weak | CONSISTENT | 2026-10-14 | -0.14 | 0.00 | -0.14 |
| Jan 27 | $12.47 | -0.31 | SF27 | $12.78 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Feb 27 | $12.50 | -0.36 | SH27 | $12.86 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Mar 27 | $12.54 | -0.32 | SH27 | $12.86 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Apr 27 | $12.51 | -0.44 | SK27 | $12.95 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| May 27 | $12.56 | -0.39 | SK27 | $12.95 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Jul 27 | $12.60 | -0.41 | SN27 | $13.01 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |

## Interpretation rules

- WGM Prentice is the preferred local market.
- Cash price, basis, futures, historical cash strength, historical basis strength,
  preferred-market competitiveness, and regional disagreement are separate signals.
- `Prior State Date = n/a` means SHUCK does not yet have an aligned prior verified
  Local Market State for that delivery month.
- Change fields are calculated only from stored verified Local Market State snapshots.
- `awaiting_report` means SHUCK checked the source but WGM has not yet published
  the expected newer report.
- This file contains sanitized market intelligence only and no credentials or
  private farm-accounting records.
