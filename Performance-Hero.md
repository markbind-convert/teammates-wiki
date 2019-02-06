* **Priority**: Medium
* **Knowledge required**: Back/front-end development, database optimization and tuning, web page performance optimization
* **Status**: Open, Recurring

Improve TEAMMATES performance for operations involving bigger data sets (e.g. bigger courses and/or bigger sessions with many questions).

The performance gains should be significant and worth the additional complexities (which should also be minimized).

1. Optimizing queries to the Datastore so that reads/writes are minimized.
1. Using incremental/paginated page loading to reduce page loading time and reduce server timeouts.
1. Using incremental/paginated data loading to reduce memory usage on server side.
1. Using task queue workers where appropriate, e.g. when the result of an operation does not need to be immediately available.

The project can concentrate on either back-end or front-end, or tackling both concurrently.
