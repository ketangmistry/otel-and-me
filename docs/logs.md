# Logs

## Log entry

Strings of data. If you structure this data in a format such as JSON then computers can understand it. However, unstructured data is more close to what humans can read and understand.

## Event

An occurrence which resulted in the change of behavior of IT. The most important attribute of an event is its timestamp i.e. _something_ happened at this time. Secondary is the descripition of what happened. From an OpenTelemetry perspective, an event **must** also have context e.g. trace ID - otherwise its just a log entry.

## References

- **Learning OpenTelemetry** - _Setting Up and Operating a Modern Observability System_ - Ted Young & Austin Parker (O'Reilly)
- **Observability for Platform Engineers** - Platform Engineering Universify
- **Google Gemini 3 Flash (Fast)**
