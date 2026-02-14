# Getting Worst Over Time

## Root Cause Examples

- Database indexing becomes less effcient
  - Increase in latency of data operations e.g. inserts and reads
    - Load balancer healthcheck fails because the check is expecting a database query result to return within a timeout interval
      - Software applications becomes saturated
        - User experience gets worst
          - Users stop using products
