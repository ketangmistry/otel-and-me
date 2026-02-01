# Fundamentals

## Telemetry

Describes what your systems is doing. A systems will emit Telemetry.

## Signals

A Signal is a particular **form** of Telemetry, in that it is a piece of data that takes a well-known format (e.g., a piece of data that takes the form of a Trace).

There are different **kinds** of Signals which have well-known use cases. For example:

- System event logs
- Infrastructure metrics
- Client and server spans (where "Kind" defines the role of the span)

With these general kinds of Signals, you have **types** which define the data specification or implementation. An example of this is a metric type of Counter or Gauge.

## Context

Telemetry without **context** is just data. Theses pieces of data that form Signals **_should_** carry context.

## Observability

The **analysis** of Telemetry to find the Signals to understand system events.

## References

- **Learning OpenTelemetry** - _Setting Up and Operating a Modern Observability System_ - Ted Young & Austin Parker (O'Reilly)
- **Observability for Platform Engineers** - Platform Engineering Universify
- **Google Gemini 3 Flash (Fast)**
