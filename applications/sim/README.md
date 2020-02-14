# Parity Market Simulator

Parity Market Simulator is a simple market event simulation.

## Usage

Run Parity Market Simulator with Java:

```
java -jar <executable> <configuration-file>
```

When started, the market simulator enters an opening bid and ask. Then it
begins to generate orders based on its model.

A sample configuration file is in etc/devel.conf

## In Progress
- Issue 1 - running without the full networking backend. 
- Issue 2 - tracing to address Connection refused error.

## References

Parity Market Simulator is based on the following paper:

- T.X. Guo. _An agent-based simulation of double-auction markets_. 2005.

## License

Released under the Apache License, Version 2.0.
