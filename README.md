# ILPv3

**This is a prototype. Nothing is finished and everything could change.**

An implementation of the Interledger Protocol V3.

See [./example.js](./example.js) for how to use it.

## TODOs

- [x] Connector exchange rates
- [x] Connector streams data from incoming to outgoing request
- [x] Send authorization in HTTP header
- [x] Sender automatically caveats macaroon token
- [x] Unified middleware API for senders, receivers, and connectors
- [x] Connector keeps balances for multiple senders (and adjusts balance on incoming and outgoing transfers)
- [x] Connector uses ILP addresses to determine where transfers are going to / coming from
- [ ] Quoting
- [ ] Fragmented payments
- [ ] Error handler that produces machine-readable error objects
- [ ] Compatibility API (that mimicks the `ilp` module for ILPv1)
- [ ] Payment channel support
- [ ] Middleware that wraps a V1 Ledger Plugin
- [ ] Bundle recommended set of middleware for senders, receivers, connectors
