# Ali Coin (ALIC)

A Bitcoin Core fork with a 100,000 ALIC founder pre-mine at block 101.

## Specifications

| Field | Value |
|-------|-------|
| Name | Ali Coin |
| Ticker | ALIC |
| Fork of | Bitcoin Core v32.99.0 |
| P2P port | 9333 |
| RPC port | 9332 |
| Network magic | 0x41 0x4c 0x49 0x43 (ALIC) |
| Block reward | 50 ALIC |
| Halving interval | 210,000 blocks |
| Block time | 10 minutes |
| Pre-mine | 100,000 ALIC at block 101 |
| Total supply | 21,100,000 ALIC |

## Files

- `feerate.h` - ticker set to ALIC
- `chainparams.cpp` - network magic, ports, genesis
- `chainparamsbase.cpp` - RPC port 9332
- `validation.cpp` - pre-mine rule at block 101
- `REFERENCE.txt` - full project reference

## Status

- Working daemon
- 201 blocks mined
- 100,000 ALIC pre-mine confirmed on-chain
- Transactions working
- **Not audited** - use at your own risk

## License

MIT (inherited from Bitcoin Core)
