# Span

Is a single unit of work. The size of this unit _should_ be different depending on what is being done and is probably a good guide in writing decoupled modular application code. For an example, if you have a function that make a database query in _addition_ to analysing the results. What are the units of work? The entire function or the individual query and analysing tasks?

## Span constructs

A **Span** will have a name, a timestamp, a duration, atributes and parent span ID.
