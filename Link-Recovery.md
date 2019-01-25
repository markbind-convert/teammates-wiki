* **Priority**: High
* **Knowledge required**: Full-stack development/testing, E2E testing
* **Status**: Open

TEAMMATES emails a unique link to each user that they can use to submit responses or view results. In some cases users delete that email by accident or cannot find it again in their inbox. It would be good to provide a way for users to request TEAMMATES to resend the link.

1. Provide a method for students to request submissions links to be resent. The request submission page needs to be protected using something like Captcha to avoid abuse. There should be some mechanism to prevent over-use of this feature by a user too.
1. As TEAMMATES uses email address to identify users, the user can specify which email the links should be sent to. It is fine to send all relevant links to the provided email address.
1. Provide a way for the admin to regenerate new submission links for a student. This is for cases where the student shares the submission link with others by mistake.
