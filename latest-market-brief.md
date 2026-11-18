# SHUCK Market Brief Source

> Canonical sanitized source for scheduled SHUCK grain intelligence.

**Preferred market:** WGM Prentice

**Latest verified report date:** 2026-11-17

**Source status:** Current

**Source state:** `current`

**Source message:** Latest WGM market data was successfully collected and verified.

**Latest checked at:** 2026-11-18T03:41:02.230732+00:00

**Latest verified at:** 2026-11-18T03:41:02.230732+00:00

**Public brief generated at:** 2026-11-18T03:46:03.341612+00:00

## Corn

| Delivery | Cash | Basis | Futures | Futures Price | Cash Strength | Basis Strength | Prentice Competitiveness | Regional Signal | Prior State Date | Cash Change | Basis Change | Futures Change |
|---|---:|---:|---|---:|---|---|---|---|---|---:|---:|---:|
| Nov 26 | $4.37 | -0.10 | CZ26 | $4.47 | Extremely high | Weak | Very strong | MATERIAL_DISAGREEMENT | 2026-11-16 | -0.02 | 0.00 | -0.02 |
| Dec 26 | $4.34 | -0.13 | CZ26 | $4.47 | Extremely high | Weak | Very strong | MATERIAL_DISAGREEMENT | 2026-11-16 | -0.02 | 0.00 | -0.02 |
| Jan 27 | $4.36 | -0.23 | CH27 | $4.59 | Extremely high | Slightly weak | Slightly strong | MATERIAL_DISAGREEMENT | 2026-11-16 | 0.00 | 0.00 | +0.00 |
| Feb 27 | $4.38 | -0.21 | CH27 | $4.59 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Mar 27 | $4.41 | -0.18 | CH27 | $4.59 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Apr 27 | $4.42 | -0.26 | CK27 | $4.67 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| May 27 | $4.44 | -0.23 | CK27 | $4.67 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Jun 27 | $4.50 | -0.25 | CN27 | $4.75 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Jul 27 | $4.50 | -0.25 | CN27 | $4.75 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Oct 27 | $4.48 | -0.35 | CZ27 | $4.83 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |

## Soybeans

| Delivery | Cash | Basis | Futures | Futures Price | Cash Strength | Basis Strength | Prentice Competitiveness | Regional Signal | Prior State Date | Cash Change | Basis Change | Futures Change |
|---|---:|---:|---|---:|---|---|---|---|---|---:|---:|---:|
| Nov 26 | $11.93 | -0.33 | SF27 | $12.26 | High | Normal | Slightly strong | CONSISTENT | 2026-11-16 | -0.02 | +0.01 | -0.04 |
| Dec 26 | $11.99 | -0.27 | SF27 | $12.26 | High | Normal | Very strong | CONSISTENT | 2026-11-16 | -0.03 | 0.00 | -0.04 |
| Jan 27 | $12.03 | -0.23 | SF27 | $12.26 | High | Normal | Competitive | CONSISTENT | 2026-11-16 | -0.03 | 0.00 | -0.04 |
| Feb 27 | $12.01 | -0.30 | SH27 | $12.31 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Mar 27 | $12.02 | -0.29 | SH27 | $12.31 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Apr 27 | $12.01 | -0.38 | SK27 | $12.39 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| May 27 | $12.05 | -0.34 | SK27 | $12.39 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Jul 27 | $12.08 | -0.36 | SN27 | $12.44 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |

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
