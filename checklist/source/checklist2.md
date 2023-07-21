
### 参考内容
https://engineerchirag.medium.com/effective-code-review-checklist-c735abbcd613

### 10 detailed code review checklist

#### 1. Functionality
- Does the PR work as expected?
- Does the new feature add value or is it a sign of feature-creep?
- Will it impact existing functionality?
- Is it going to create inconsistency at other place?

#### 2. Readability, Code syntax & formatting
- Is the code clear and concise?
- Does it comply with PEP-8/best practice?
- Are all language and project conventions followed?
- Are identifiers given meaningful and style guide-compliant names?
- Ensure that proper naming conventions(Pascal, CamelCase etc.) have been followed.
- Ensure code is properly indented and team follows same rule(two space/tab) in the project.
- Does the PR add test-cases for the modified code?

#### 3. Design principle
- Is the code properly planned and designed?
- Separation of Concerns followed?
- Is code in sync with existing code patterns/technologies?
- Did we think about reusability?
- Is the code well organised in terms of placement of components?
- Did we explore existing design principle that suits the need?

#### 4. Patterns, idioms & best practices
- No hard coding, use constants/configuration values
- Does the code keep with idioms and code patterns of the language?
- Does the code make use of the language features and standard libraries?

#### 5. Documentation and maintainability
- Is the code self-documenting or well-documented?
- Did you add comments mentioning reason of change, todo, workaround, hacks did in the code?
- Is the code free of obfuscation and unnecessary complexity?
- Is the control flow and component relationship clear to understand?

#### 6. Debuggability, Testability and Configurability 
- Are you logging exceptions, flow or control, user behavior for better debugging and consumer behavior understanding?
- Is code testable?
- Is code configurable enough, to avoid changes in business or view layers or even code changes?

#### 7. Performance, reliability and scalability
- Is the code optimised for in terms of time and space complexity?
- Does it scale as per the need?
- Does it cover failure scenarios?
- Does it have instrumentation like reporting for metrics and alerting for failures?

#### 8. Security
- Is the code free of implementation bugs that could be exploited?
- Have all the new dependencies been audited for vulnerabilities?
- Does it have Authentication, authorization, input data validation against security threats?


#### 9. Etiquette
- Is the PR atomic?
- Does the PR follow the single concern principle?
- Are the commit messages well-written?

#### 10. Notice What's Missing
- Did you try using app/functionality as end user?
- Does it cover loading ,error handling, edge cases and unexpected input handling?
- Will it work in all support environment OS, browsers, platform etc?
- Does it need feature flag control?
- Does it have proper instrumentation?

