* **Priority**: High
* **Knowledge required**: Full-stack development/testing, E2E testing
* **Status**: Completed

Add the ability to recover deleted sessions/courses via a recycle bin.

Occasionally, users delete sessions/courses by mistake and ask us to recover data. In the current implementation, there is no way to recover deleted data. The challenge is to implement such a feature without a significant increase in database writes or storage usage as we are billed for both based on usage.

1. Restoring/deleting from recycle bin.
1. UI presentation of the deleted items.
1. Auto-purging of the recycle bin after a set waiting period.
