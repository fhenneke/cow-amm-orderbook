# CoW AMM orderbook

The purpose of the software is to continuously add executable orders for CoW AMMs the the CoW Protocol orderbook. Those orders can then be picked up by other solvers who do not natively support CoW AMMs yet.

This is done by
- indexing the state of CoW AMMs,
- computing reasonable trades for CoW AMMs,
- creating order with suitable pre- and post-interactions, and
- submitting those orders to the orderbook.

These four parts of the code can also be used independently.
