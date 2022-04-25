[From Darragh](https://dev.to/darraghor/20-questions-for-valuable-code-reviews-3g9i)
[Darragh ORiordan](https://www.darraghoriordan.com/)

# 20 code readability and functional correctness code review questions
---

Is the intent clear?
Is there needless duplication?
Could existing code have solved this?
Is this an atomic commit?
Could this be simpler?
Are there obvious logic issues?
Does it need tests?
Are the tests comprehensive and clear?
Are there any security issues or considerations?
Are there any accessibility considerations?
Are there any PII considerations?
Is it instrumented? Are there relevant analytics? Are there relevant production logs?
Are there revert scripts for database changes?
Is the database work ACID? Is it transactioned sensibly?
Does this feature need to be turned off in the future?
Is it easy to turn it off?
How easy is it to delete the feature code as a whole entity?
Does the code respect Command-Query separation?
If DDD - Are there well defined aggregate roots, value objects, enumerations?
Will there be any issues recovering from a transient failure? Is the solution distributed in an unexpected way?
