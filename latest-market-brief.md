# SHUCK Market Brief Source

> Canonical sanitized source for scheduled SHUCK grain intelligence.

**Preferred market:** WGM Prentice

**Latest verified report date:** 2026-10-09

**Source status:** Current

**Source state:** `current`

**Source message:** Latest WGM market data was successfully collected and verified.

**Latest checked at:** 2026-10-10T01:44:39.183189+00:00

**Latest verified at:** 2026-10-10T01:44:39.183189+00:00

**Public brief generated at:** 2026-10-10T01:50:24.674641+00:00

## Corn

| Delivery | Cash | Basis | Futures | Futures Price | Cash Strength | Basis Strength | Prentice Competitiveness | Regional Signal | Prior State Date | Cash Change | Basis Change | Futures Change |
|---|---:|---:|---|---:|---|---|---|---|---|---:|---:|---:|
| Oct 26 | $4.39 | -0.41 | CZ26 | $4.80 | Extremely high | Weak | Very weak | MATERIAL_DISAGREEMENT | 2026-10-08 | -0.20 | 0.00 | -0.20 |
| Nov 26 | $4.49 | -0.31 | CZ26 | $4.80 | Extremely high | Weak | Competitive | MATERIAL_DISAGREEMENT | 2026-10-08 | -0.13 | +0.07 | -0.20 |
| Dec 26 | $4.64 | -0.16 | CZ26 | $4.80 | Extremely high | Slightly weak | Very strong | MATERIAL_DISAGREEMENT | 2026-10-08 | -0.15 | +0.05 | -0.20 |
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
| Oct 26 | $12.44 | -0.48 | SX26 | $12.92 | High | Normal | Very weak | CONSISTENT | 2026-10-08 | +0.01 | -0.03 | +0.04 |
| Nov 26 | $12.60 | -0.32 | SX26 | $12.92 | High | Normal | Strong | CONSISTENT | 2026-10-08 | +0.05 | 0.00 | +0.04 |
| Dec 26 | $12.80 | -0.29 | SF27 | $13.09 | High | Normal | Weak | CONSISTENT | 2026-10-08 | +0.05 | 0.00 | +0.04 |
| Jan 27 | $12.82 | -0.27 | SF27 | $13.09 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Feb 27 | $12.87 | -0.32 | SH27 | $13.19 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Mar 27 | $12.91 | -0.28 | SH27 | $13.19 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Apr 27 | $12.85 | -0.42 | SK27 | $13.27 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| May 27 | $12.90 | -0.37 | SK27 | $13.27 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Jul 27 | $12.96 | -0.37 | SN27 | $13.32 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |

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
