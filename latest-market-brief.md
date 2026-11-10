# SHUCK Market Brief Source

> Canonical sanitized source for scheduled SHUCK grain intelligence.

**Preferred market:** WGM Prentice

**Latest verified report date:** 2026-11-09

**Source status:** Current

**Source state:** `current`

**Source message:** Latest WGM market data was successfully collected and verified.

**Latest checked at:** 2026-11-10T04:05:14.593734+00:00

**Latest verified at:** 2026-11-10T04:05:14.593734+00:00

**Public brief generated at:** 2026-11-10T04:13:50.641845+00:00

## Corn

| Delivery | Cash | Basis | Futures | Futures Price | Cash Strength | Basis Strength | Prentice Competitiveness | Regional Signal | Prior State Date | Cash Change | Basis Change | Futures Change |
|---|---:|---:|---|---:|---|---|---|---|---|---:|---:|---:|
| Nov 26 | $4.21 | -0.18 | CZ26 | $4.39 | Extremely high | Weak | Very strong | MATERIAL_DISAGREEMENT | 2026-11-06 | -0.03 | 0.00 | -0.02 |
| Dec 26 | $4.23 | -0.16 | CZ26 | $4.39 | Extremely high | Weak | Very strong | MATERIAL_DISAGREEMENT | 2026-11-06 | -0.02 | 0.00 | -0.02 |
| Jan 27 | $4.29 | -0.23 | CH27 | $4.52 | Extremely high | Slightly weak | Slightly strong | MATERIAL_DISAGREEMENT | 2026-11-06 | -0.03 | 0.00 | -0.03 |
| Feb 27 | $4.31 | -0.21 | CH27 | $4.52 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Mar 27 | $4.34 | -0.18 | CH27 | $4.52 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Apr 27 | $4.35 | -0.26 | CK27 | $4.61 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| May 27 | $4.38 | -0.23 | CK27 | $4.61 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Jun 27 | $4.44 | -0.25 | CN27 | $4.69 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Jul 27 | $4.44 | -0.25 | CN27 | $4.69 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Oct 27 | $4.48 | -0.35 | CZ27 | $4.83 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |

## Soybeans

| Delivery | Cash | Basis | Futures | Futures Price | Cash Strength | Basis Strength | Prentice Competitiveness | Regional Signal | Prior State Date | Cash Change | Basis Change | Futures Change |
|---|---:|---:|---|---:|---|---|---|---|---|---:|---:|---:|
| Nov 26 | $11.52 | -0.36 | SF27 | $11.88 | High | Normal | Competitive | CONSISTENT | 2026-11-06 | -0.06 | 0.00 | -0.06 |
| Dec 26 | $11.60 | -0.28 | SF27 | $11.88 | High | Normal | Very strong | CONSISTENT | 2026-11-06 | -0.06 | 0.00 | -0.06 |
| Jan 27 | $11.64 | -0.24 | SF27 | $11.88 | High | Normal | Slightly weak | CONSISTENT | 2026-11-06 | -0.06 | 0.00 | -0.06 |
| Feb 27 | $11.65 | -0.30 | SH27 | $11.95 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Mar 27 | $11.66 | -0.29 | SH27 | $11.95 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Apr 27 | $11.71 | -0.34 | SK27 | $12.04 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| May 27 | $11.71 | -0.34 | SK27 | $12.04 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Jul 27 | $11.76 | -0.36 | SN27 | $12.12 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |

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
