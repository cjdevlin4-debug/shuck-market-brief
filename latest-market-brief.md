# SHUCK Market Brief Source

> Canonical sanitized source for scheduled SHUCK grain intelligence.

**Preferred market:** WGM Prentice

**Latest verified report date:** 2026-10-14

**Source status:** Current

**Source state:** `current`

**Source message:** Latest WGM market data was successfully collected and verified.

**Latest checked at:** 2026-10-15T00:30:27.278416+00:00

**Latest verified at:** 2026-10-15T00:30:27.278416+00:00

**Public brief generated at:** 2026-10-15T00:40:05.407681+00:00

## Corn

| Delivery | Cash | Basis | Futures | Futures Price | Cash Strength | Basis Strength | Prentice Competitiveness | Regional Signal | Prior State Date | Cash Change | Basis Change | Futures Change |
|---|---:|---:|---|---:|---|---|---|---|---|---:|---:|---:|
| Oct 26 | $4.45 | -0.36 | CZ26 | $4.81 | Extremely high | Weak | Weak | MATERIAL_DISAGREEMENT | 2026-10-13 | -0.02 | 0.00 | -0.02 |
| Nov 26 | $4.50 | -0.31 | CZ26 | $4.81 | Extremely high | Weak | Competitive | MATERIAL_DISAGREEMENT | 2026-10-13 | -0.02 | 0.00 | -0.02 |
| Dec 26 | $4.65 | -0.16 | CZ26 | $4.81 | Extremely high | Slightly weak | Very strong | MATERIAL_DISAGREEMENT | 2026-10-13 | -0.02 | 0.00 | -0.02 |
| Jan 27 | $4.68 | -0.26 | CH27 | $4.94 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Feb 27 | $4.71 | -0.23 | CH27 | $4.94 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Mar 27 | $4.74 | -0.20 | CH27 | $4.94 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Apr 27 | $4.78 | -0.24 | CK27 | $5.02 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| May 27 | $4.81 | -0.21 | CK27 | $5.02 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Jun 27 | $4.84 | -0.23 | CN27 | $5.08 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Jul 27 | $4.84 | -0.23 | CN27 | $5.08 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |

## Soybeans

| Delivery | Cash | Basis | Futures | Futures Price | Cash Strength | Basis Strength | Prentice Competitiveness | Regional Signal | Prior State Date | Cash Change | Basis Change | Futures Change |
|---|---:|---:|---|---:|---|---|---|---|---|---:|---:|---:|
| Oct 26 | $12.06 | -0.71 | SX26 | $12.77 | High | Normal | Very weak | CONSISTENT | 2026-10-13 | -0.11 | -0.04 | -0.07 |
| Nov 26 | $12.41 | -0.36 | SX26 | $12.77 | High | Normal | Slightly strong | CONSISTENT | 2026-10-13 | -0.11 | -0.04 | -0.07 |
| Dec 26 | $12.59 | -0.33 | SF27 | $12.92 | High | Normal | Very weak | CONSISTENT | 2026-10-13 | -0.12 | -0.04 | -0.08 |
| Jan 27 | $12.61 | -0.31 | SF27 | $12.92 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Feb 27 | $12.64 | -0.36 | SH27 | $13.00 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Mar 27 | $12.68 | -0.32 | SH27 | $13.00 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Apr 27 | $12.62 | -0.46 | SK27 | $13.09 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| May 27 | $12.68 | -0.41 | SK27 | $13.09 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Jul 27 | $12.73 | -0.41 | SN27 | $13.14 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |

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
