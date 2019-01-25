* **Priority**: Low
* **Knowledge required**: Full-stack development/testing, E2E testing
* **Status**: Archived

Add the ability for instructors to tag students (e.g. `#good-coder`, `#potential-tutor`) and searching all students by keywords/tags.

While it sounds easy, the following factors add to the complexity.
1. We prefer progressive search, i.e. displaying results as the user types keywords.
1. Results should show some information about the user e.g., photo thumbnail, the courses taken.
1. The feature should be scalable to situations where an instructor has several thousands of students in his/her courses.
1. The instructor may not have the full name of the student or might make a minor typo in the name. We might have to make use of GAE's search API or create more indexes to support search. However, creating extra indexes is costly.
1. The feature should allow using multiple tags on a single student.
