# SHUCK Market Brief Source

> Canonical sanitized source for scheduled SHUCK grain intelligence.

**Preferred market:** WGM Prentice

**Latest verified report date:** 2026-10-08

**Source status:** Current

**Source state:** `current`

**Source message:** Latest WGM market data was successfully collected and verified.

**Latest checked at:** 2026-10-09T02:06:30.082017+00:00

**Latest verified at:** 2026-10-09T02:06:30.082017+00:00

**Public brief generated at:** 2026-10-09T02:21:46.813593+00:00

## Corn

| Delivery | Cash | Basis | Futures | Futures Price | Cash Strength | Basis Strength | Prentice Competitiveness | Regional Signal | Prior State Date | Cash Change | Basis Change | Futures Change |
|---|---:|---:|---|---:|---|---|---|---|---|---:|---:|---:|
| Oct 26 | $4.59 | -0.41 | CZ26 | $5.00 | Extremely high | Weak | Very weak | MATERIAL_DISAGREEMENT | 2026-10-07 | -0.02 | 0.00 | -0.02 |
| Nov 26 | $4.62 | -0.38 | CZ26 | $5.00 | Extremely high | Weak | Weak | MATERIAL_DISAGREEMENT | 2026-10-07 | -0.04 | -0.02 | -0.02 |
| Dec 26 | $4.79 | -0.21 | CZ26 | $5.00 | Extremely high | Slightly weak | Strong | MATERIAL_DISAGREEMENT | 2026-10-07 | -0.02 | 0.00 | -0.02 |
| Jan 27 | $4.83 | -0.32 | CH27 | $5.15 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Feb 27 | $4.86 | -0.29 | CH27 | $5.15 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Mar 27 | $4.90 | -0.25 | CH27 | $5.15 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Apr 27 | $4.96 | -0.26 | CK27 | $5.22 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| May 27 | $4.99 | -0.23 | CK27 | $5.22 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Jun 27 | $4.98 | -0.28 | CN27 | $5.26 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Jul 27 | $5.01 | -0.25 | CN27 | $5.26 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |

## Soybeans

| Delivery | Cash | Basis | Futures | Futures Price | Cash Strength | Basis Strength | Prentice Competitiveness | Regional Signal | Prior State Date | Cash Change | Basis Change | Futures Change |
|---|---:|---:|---|---:|---|---|---|---|---|---:|---:|---:|
| Oct 26 | $12.43 | -0.45 | SX26 | $12.88 | High | Normal | Weak | CONSISTENT | 2026-10-07 | -0.10 | 0.00 | -0.10 |
| Nov 26 | $12.55 | -0.32 | SX26 | $12.88 | High | Normal | Strong | CONSISTENT | 2026-10-07 | -0.10 | 0.00 | -0.10 |
| Dec 26 | $12.75 | -0.29 | SF27 | $13.04 | High | Normal | Weak | CONSISTENT | 2026-10-07 | -0.11 | 0.00 | -0.10 |
| Jan 27 | $12.77 | -0.27 | SF27 | $13.04 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Feb 27 | $12.82 | -0.32 | SH27 | $13.14 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Mar 27 | $12.86 | -0.28 | SH27 | $13.14 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Apr 27 | $12.81 | -0.42 | SK27 | $13.23 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| May 27 | $12.86 | -0.37 | SK27 | $13.23 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |
| Jul 27 | $12.92 | -0.37 | SN27 | $13.29 | n/a | n/a | n/a | n/a | n/a | n/a | n/a | n/a |

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
