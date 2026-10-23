# SHUCK Market Brief Source

> Canonical sanitized source for scheduled SHUCK grain intelligence.

**Preferred market:** WGM Prentice

**Latest verified report date:** 2026-10-22

**Source status:** Current

**Source state:** `current`

**Source message:** Latest WGM market data was successfully collected and verified.

**Latest checked at:** 2026-10-23T00:37:58.440512+00:00

**Latest verified at:** 2026-10-23T00:37:58.440512+00:00

**Public brief generated at:** 2026-10-23T00:46:28.706942+00:00

## Corn

| Delivery | Cash | Basis | Futures | Futures Price | Cash Strength | Basis Strength | Prentice Competitiveness | Regional Signal | Prior State Date | Cash Change | Basis Change | Futures Change |
|---|---:|---:|---|---:|---|---|---|---|---|---:|---:|---:|
| Oct 26 | $4.25 | -0.36 | CZ26 | $4.61 | Extremely high | Weak | Weak | MATERIAL_DISAGREEMENT | 2026-10-20 | -0.01 | 0.00 | -0.01 |
| Nov 26 | $4.30 | -0.31 | CZ26 | $4.61 | Extremely high | Weak | Competitive | MATERIAL_DISAGREEMENT | 2026-10-20 | -0.01 | 0.00 | -0.01 |
| Dec 26 | $4.45 | -0.16 | CZ26 | $4.61 | Extremely high | Slightly weak | Very strong | MATERIAL_DISAGREEMENT | 2026-10-20 | -0.01 | 0.00 | -0.01 |
| Jan 27 | $4.48 | -0.26 | CH27 | $4.74 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Feb 27 | $4.51 | -0.23 | CH27 | $4.74 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Mar 27 | $4.54 | -0.20 | CH27 | $4.74 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Apr 27 | $4.58 | -0.24 | CK27 | $4.83 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| May 27 | $4.62 | -0.21 | CK27 | $4.83 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Jun 27 | $4.66 | -0.23 | CN27 | $4.89 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Jul 27 | $4.66 | -0.23 | CN27 | $4.89 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |

## Soybeans

| Delivery | Cash | Basis | Futures | Futures Price | Cash Strength | Basis Strength | Prentice Competitiveness | Regional Signal | Prior State Date | Cash Change | Basis Change | Futures Change |
|---|---:|---:|---|---:|---|---|---|---|---|---:|---:|---:|
| Oct 26 | $12.02 | -0.51 | SX26 | $12.53 | High | Normal | Very weak | CONSISTENT | 2026-10-20 | +0.10 | +0.05 | +0.05 |
| Nov 26 | $12.21 | -0.32 | SX26 | $12.53 | High | Normal | Strong | CONSISTENT | 2026-10-20 | +0.07 | +0.02 | +0.05 |
| Dec 26 | $12.33 | -0.32 | SF27 | $12.65 | High | Normal | Very weak | CONSISTENT | 2026-10-20 | +0.03 | +0.01 | +0.01 |
| Jan 27 | $12.38 | -0.27 | SF27 | $12.65 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Feb 27 | $12.38 | -0.33 | SH27 | $12.71 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Mar 27 | $12.41 | -0.30 | SH27 | $12.71 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Apr 27 | $12.41 | -0.38 | SK27 | $12.79 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| May 27 | $12.45 | -0.34 | SK27 | $12.79 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Jul 27 | $12.48 | -0.36 | SN27 | $12.84 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |

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
