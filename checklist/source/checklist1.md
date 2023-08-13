
### 内容参考
https://www.codereviewchecklist.com/

#### Code Review Checklist
The following checklist for code reviews isn't meant to be an exhaustive list to cover every eventuality.
Merely a prompt to make sure you've thought of some of the common scenarios.

##### Requirements
- [ ] Have the requirements been met?
- [ ] Have stakeholder(s) approved the change?

##### Maintainability
- [ ] Is the code easy to read ?
- [ ] Is the code not repeated(DRY Principle) ?
- [ ] Is the code method/class not too long?

##### Testing
- [ ] Do unit tests pass?
- [ ] Do manual test plans pass?
- [ ] Has been peer review tested?
- [ ] Have edge cases been tested?
- [ ] Are invalid inputs validated?
- [ ] Are inputs sanitised?

##### Code Formatting
- [ ] Is the code formatted correctly?
- [ ] Unnecessary whitespace remove?

##### Performance
- [ ] Is the code performance acceptable?

##### Documentation
- [ ] Is there sufficient documentation?
- [ ] Is the ReadMe.md file up to date?

##### Best Practices
- [ ] Follow Single Responsibility principle ?
- [ ] Are different errors handled correctly ?
- [ ] Are errors and warnings logged?
- [ ] Magic values avoided?
- [ ] No unnecessary comments?
- [ ] Minimal nesting used?

##### Architecture
- [ ] Is it secure/free from risk?
- [ ] Are separations of concerned followed?
- [ ] Relevant Parameters are configurable?
- [ ] Feature switched if necessary?

##### Other
- [ ] Has the release been annotated(GA etc)?

备注说明：
1. A magic number is a direct usage of a number in the code.
- https://stackoverflow.com/questions/47882/what-is-a-magic-number-and-why-is-it-bad

2. Are separations of concerned followed?
- https://www.cnblogs.com/wenhongyu/p/7992028.html
- https://zh.wikipedia.org/zh-hans/%E5%85%B3%E6%B3%A8%E7%82%B9%E5%88%86%E7%A6%BB



