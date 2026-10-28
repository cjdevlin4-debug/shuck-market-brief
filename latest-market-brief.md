# SHUCK Market Brief Source

> Canonical sanitized source for scheduled SHUCK grain intelligence.

**Preferred market:** WGM Prentice

**Latest verified report date:** 2026-10-27

**Source status:** Current

**Source state:** `current`

**Source message:** Latest WGM market data was successfully collected and verified.

**Latest checked at:** 2026-10-28T01:17:31.110247+00:00

**Latest verified at:** 2026-10-28T01:17:31.110247+00:00

**Public brief generated at:** 2026-10-28T01:30:37.451945+00:00

## Corn

| Delivery | Cash | Basis | Futures | Futures Price | Cash Strength | Basis Strength | Prentice Competitiveness | Regional Signal | Prior State Date | Cash Change | Basis Change | Futures Change |
|---|---:|---:|---|---:|---|---|---|---|---|---:|---:|---:|
| Oct 26 | $4.18 | -0.31 | CZ26 | $4.49 | Extremely high | Weak | Competitive | MATERIAL_DISAGREEMENT | 2026-10-23 | -0.02 | +0.05 | -0.07 |
| Nov 26 | $4.25 | -0.24 | CZ26 | $4.49 | Extremely high | Weak | Strong | MATERIAL_DISAGREEMENT | 2026-10-23 | -0.07 | 0.00 | -0.07 |
| Dec 26 | $4.33 | -0.16 | CZ26 | $4.49 | Extremely high | Slightly weak | Very strong | MATERIAL_DISAGREEMENT | 2026-10-23 | -0.07 | 0.00 | -0.07 |
| Jan 27 | $4.37 | -0.26 | CH27 | $4.63 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Feb 27 | $4.40 | -0.23 | CH27 | $4.63 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Mar 27 | $4.43 | -0.20 | CH27 | $4.63 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Apr 27 | $4.47 | -0.24 | CK27 | $4.71 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| May 27 | $4.50 | -0.21 | CK27 | $4.71 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Jun 27 | $4.55 | -0.23 | CN27 | $4.78 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Jul 27 | $4.55 | -0.23 | CN27 | $4.78 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |

## Soybeans

| Delivery | Cash | Basis | Futures | Futures Price | Cash Strength | Basis Strength | Prentice Competitiveness | Regional Signal | Prior State Date | Cash Change | Basis Change | Futures Change |
|---|---:|---:|---|---:|---|---|---|---|---|---:|---:|---:|
| Oct 26 | $11.83 | -0.46 | SX26 | $12.29 | High | Normal | Weak | CONSISTENT | 2026-10-23 | -0.22 | +0.05 | -0.27 |
| Nov 26 | $11.99 | -0.30 | SX26 | $12.29 | High | Normal | Strong | CONSISTENT | 2026-10-23 | -0.25 | +0.02 | -0.27 |
| Dec 26 | $12.13 | -0.30 | SF27 | $12.43 | High | Normal | Weak | CONSISTENT | 2026-10-23 | -0.24 | +0.02 | -0.26 |
| Jan 27 | $12.16 | -0.27 | SF27 | $12.43 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Feb 27 | $12.22 | -0.30 | SH27 | $12.52 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Mar 27 | $12.23 | -0.29 | SH27 | $12.52 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Apr 27 | $12.22 | -0.38 | SK27 | $12.61 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| May 27 | $12.27 | -0.34 | SK27 | $12.61 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Jul 27 | $12.31 | -0.36 | SN27 | $12.67 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |

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
