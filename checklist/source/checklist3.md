### 参考
https://linearb.io/blog/code-review-checklist


#### What to Add to Your Code Review Checklist

##### 1. Identify Obvious Bugs 

##### 2. Look for Possible Security Issues

##### 3. Look for "Clever" Code
Code readability is another vital area you should look into when reviewing code. 
First, remember that readability is, to a certain extent, subjective.
MayBe "Clever" Code is unreadable.

##### 4. Check for Code Duplication

##### 5. 
Naming is one of the hardest things in software engineering, but that does not mean we should give up.
When performing a review, look for opportunities to improve the names of variables, constants, class fields and properties, methods, classes, and so on.
With the help of a patient, creative, and empathetic reviewer, engineers can certainly find names that are creative yet simple and adhere to the language used by the rest of business.

##### 6. Look for Possible Performance Improvements
Again, you should have automatic checks and production monitoring to detect performance issues.

- an expensive operation inside a loop
- excessive allocations of objects
- inefficient string concatenations
- inefficient logging

##### 7. Check the Presence and Quality of Tests 
- The presence of tests: Did the author create tests for their change?
- The quality of tests: Do the tests created seem to effectively exercise the system under test? Do they follow agreed-upon best practices?
- Readability: Remember tests are also documentation. They should be simple and easy to understand.
- Naming: Are the tests named according to the team’s convention? Is it easy to understand what they’re about?

##### 8. Explain Your Changes

##### 9. Optional: Code Documentation
