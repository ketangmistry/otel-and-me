# Instrumentation

## Types

### Manual

Pull in OpenTelemetry dependencies into your class path or add modules, and then create instances of meters, tracers, loggers. Finally call methods to invoke the API - there would also be a need to setup exporters e.g. OTLP.

### Auto

Explicitly add/reference agents in your program command line.

### Zero-touch

The adding/referring of agents is handled by an operator which could be an opt-out but most likely an opt-in through an annotation.

## References

- **Observability for Platform Engineers** - Platform Engineering Universify
