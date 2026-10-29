# SHUCK Market Brief Source

> Canonical sanitized source for scheduled SHUCK grain intelligence.

**Preferred market:** WGM Prentice

**Latest verified report date:** 2026-10-28

**Source status:** Current

**Source state:** `current`

**Source message:** Latest WGM market data was successfully collected and verified.

**Latest checked at:** 2026-10-29T01:47:08.894431+00:00

**Latest verified at:** 2026-10-29T01:47:08.894431+00:00

**Public brief generated at:** 2026-10-29T01:53:18.842554+00:00

## Corn

| Delivery | Cash | Basis | Futures | Futures Price | Cash Strength | Basis Strength | Prentice Competitiveness | Regional Signal | Prior State Date | Cash Change | Basis Change | Futures Change |
|---|---:|---:|---|---:|---|---|---|---|---|---:|---:|---:|
| Oct 26 | $4.21 | -0.31 | CZ26 | $4.52 | Extremely high | Weak | Competitive | MATERIAL_DISAGREEMENT | 2026-10-27 | +0.03 | 0.00 | +0.03 |
| Nov 26 | $4.28 | -0.24 | CZ26 | $4.52 | Extremely high | Weak | Strong | MATERIAL_DISAGREEMENT | 2026-10-27 | +0.03 | 0.00 | +0.03 |
| Dec 26 | $4.36 | -0.16 | CZ26 | $4.52 | Extremely high | Slightly weak | Very strong | MATERIAL_DISAGREEMENT | 2026-10-27 | +0.03 | 0.00 | +0.03 |
| Jan 27 | $4.39 | -0.26 | CH27 | $4.65 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Feb 27 | $4.42 | -0.23 | CH27 | $4.65 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Mar 27 | $4.45 | -0.20 | CH27 | $4.65 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Apr 27 | $4.49 | -0.24 | CK27 | $4.73 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| May 27 | $4.52 | -0.21 | CK27 | $4.73 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Jun 27 | $4.56 | -0.23 | CN27 | $4.79 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Jul 27 | $4.56 | -0.23 | CN27 | $4.79 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |

## Soybeans

| Delivery | Cash | Basis | Futures | Futures Price | Cash Strength | Basis Strength | Prentice Competitiveness | Regional Signal | Prior State Date | Cash Change | Basis Change | Futures Change |
|---|---:|---:|---|---:|---|---|---|---|---|---:|---:|---:|
| Oct 26 | $11.78 | -0.46 | SX26 | $12.24 | High | Normal | Weak | CONSISTENT | 2026-10-27 | -0.05 | 0.00 | -0.05 |
| Nov 26 | $11.92 | -0.32 | SX26 | $12.24 | High | Normal | Strong | CONSISTENT | 2026-10-27 | -0.07 | -0.02 | -0.05 |
| Dec 26 | $12.08 | -0.30 | SF27 | $12.38 | High | Normal | Weak | CONSISTENT | 2026-10-27 | -0.05 | 0.00 | -0.05 |
| Jan 27 | $12.11 | -0.27 | SF27 | $12.38 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Feb 27 | $12.16 | -0.30 | SH27 | $12.46 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Mar 27 | $12.17 | -0.29 | SH27 | $12.46 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Apr 27 | $12.16 | -0.38 | SK27 | $12.54 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| May 27 | $12.21 | -0.34 | SK27 | $12.54 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Jul 27 | $12.25 | -0.36 | SN27 | $12.61 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |

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
