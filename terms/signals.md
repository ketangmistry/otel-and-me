# Signals

A Signal is a particular **form** of Telemetry, in that it is a piece of data that takes a well-known format (e.g., a piece of data that takes the form of a Trace).

There are different **kinds** of Signals which have well-known use cases. For example:

- System event logs
- Infrastructure metrics
- Client and server spans (where "Kind" defines the role of the span)

With these general kinds of Signals, you have **types** which define the data specification or implementation. An example of this is a metric type of Counter or Gauge.
