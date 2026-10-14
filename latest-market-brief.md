# SHUCK Market Brief Source

> Canonical sanitized source for scheduled SHUCK grain intelligence.

**Preferred market:** WGM Prentice

**Latest verified report date:** 2026-10-13

**Source status:** Current

**Source state:** `current`

**Source message:** Latest WGM market data was successfully collected and verified.

**Latest checked at:** 2026-10-14T01:11:37.752963+00:00

**Latest verified at:** 2026-10-14T01:11:37.752963+00:00

**Public brief generated at:** 2026-10-14T01:18:35.661186+00:00

## Corn

| Delivery | Cash | Basis | Futures | Futures Price | Cash Strength | Basis Strength | Prentice Competitiveness | Regional Signal | Prior State Date | Cash Change | Basis Change | Futures Change |
|---|---:|---:|---|---:|---|---|---|---|---|---:|---:|---:|
| Oct 26 | $4.47 | -0.36 | CZ26 | $4.83 | Extremely high | Weak | Weak | MATERIAL_DISAGREEMENT | 2026-10-12 | +0.05 | +0.05 | -0.00 |
| Nov 26 | $4.52 | -0.31 | CZ26 | $4.83 | Extremely high | Weak | Competitive | MATERIAL_DISAGREEMENT | 2026-10-12 | 0.00 | 0.00 | -0.00 |
| Dec 26 | $4.67 | -0.16 | CZ26 | $4.83 | Extremely high | Slightly weak | Very strong | MATERIAL_DISAGREEMENT | 2026-10-12 | 0.00 | 0.00 | -0.00 |
| Jan 27 | $4.71 | -0.26 | CH27 | $4.96 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Feb 27 | $4.73 | -0.23 | CH27 | $4.96 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Mar 27 | $4.76 | -0.20 | CH27 | $4.96 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Apr 27 | $4.80 | -0.24 | CK27 | $5.04 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| May 27 | $4.83 | -0.21 | CK27 | $5.04 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Jun 27 | $4.87 | -0.23 | CN27 | $5.10 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Jul 27 | $4.87 | -0.23 | CN27 | $5.10 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |

## Soybeans

| Delivery | Cash | Basis | Futures | Futures Price | Cash Strength | Basis Strength | Prentice Competitiveness | Regional Signal | Prior State Date | Cash Change | Basis Change | Futures Change |
|---|---:|---:|---|---:|---|---|---|---|---|---:|---:|---:|
| Oct 26 | $12.17 | -0.67 | SX26 | $12.84 | High | Normal | Very weak | CONSISTENT | 2026-10-12 | -0.20 | -0.16 | -0.04 |
| Nov 26 | $12.52 | -0.32 | SX26 | $12.84 | High | Normal | Strong | CONSISTENT | 2026-10-12 | -0.04 | 0.00 | -0.04 |
| Dec 26 | $12.71 | -0.29 | SF27 | $13.00 | High | Normal | Weak | CONSISTENT | 2026-10-12 | -0.05 | 0.00 | -0.05 |
| Jan 27 | $12.73 | -0.27 | SF27 | $13.00 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Feb 27 | $12.77 | -0.32 | SH27 | $13.09 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Mar 27 | $12.81 | -0.28 | SH27 | $13.09 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Apr 27 | $12.75 | -0.42 | SK27 | $13.17 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| May 27 | $12.80 | -0.37 | SK27 | $13.17 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Jul 27 | $12.86 | -0.37 | SN27 | $13.23 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |

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
