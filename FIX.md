# Fix: rounding in three-decimal FX rates

Switched the conversion math from float64 to Decimal precision 6.
See PR description for full context.