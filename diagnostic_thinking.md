# Diagnostic Thinking

## Chapter 1

### Presenting a Problem

- Define the problem
- A concise description of an issue to be addressed
- Concise: lot of information clearly, in a few words. Brief, but comprehensive.
- Ask questions, think from a different perspective.
- Verify vague words use
- Determine timing of the issue

### QUIZ

What is the correct definition of a "problem statement"?

```sh
"A(n) concise description of an issue to be addressed or a condition to be
improved upon."
```

### Problem Statements

- Statement: Mongodb is slow.
- Define 'slow': Quantify, relate. Slow=1s? Slow=slower than yesterday?
- Identify scale. A specific query? a specific collecction. Focus on the distinction.
- When did it occured? Look at timestamps.
- If it has always been there, might be related to architecture rather than code changes.
- Verify Vague words

### Quiz: Problem Statements Continued

Problem:

Around noon, your co-worker comes to you for help with a MongoDB issue. There have been reports of slow queries against the cities collection only and your co-worker doesn't know what next steps to take. Which of the following would be the most concise problem statement for this issue?
Attempts Remaining:3 Attempts left

Choose the best answer:

- [ ] "This morning MongoDB was fine but at 11am I noticed in our metrics that query times were rising in our cities collection. When I looked at the metrics for the other collections I didn't notice any increased query times in them but I could be wrong."
- [ ] "After 11am, MongoDB suddenly became very slow."
- [X] "After 11am, query time against the cities collection increased but query time against any other collection remained the same."
- [ ] "Query time against the cities collection increased."

### Lecture: Identifying Info and Forming Hypotheses

- Define problem
- Identify information. System configuration, logs, metrics.
- Form an hypotehsis.
- Test the hypothesis. Prove your theory.
- Form new hypothesis if necessary. Each hypothesis must use the information from the previous hypothesis.

### QUIZ Identifying Info and Forming Hypotheses

Problem:

Following our diagnostic workflow, arrange in order the steps you would perform to solve the problem "MongoDB is slow".
Drag and drop the steps into the correct order and click submit.
Attempts Remaining:3 Attempts left

- [1] Determine the actual problem by asking clarifying questions
- [3] Propose a possible cause
- [2] Identify the possibly relevant logs and metrics
- [5] Use the results of a test to inform a new theory
- [4] Change something in the system and see if the problem reoccurs