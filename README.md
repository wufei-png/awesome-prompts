# awesome-prompts
- document generator:
```
Generate documentation for this code:

[Paste your code]

Include:
1. Overview: What this module does and why it exists
2. Quick Start: How to use it in 3 steps or less
3. API Reference: Every public function with params, returns, and examples
4. Common Patterns: The 3 most common use cases with code
5. Gotchas: Edge cases, limitations, and things that will bite you
6. Related: What other modules this works with

Write for a developer who's new to this codebase but not new to coding.
```

- The Code Review Partner
```
Review this code as a senior developer:

[Paste your code or diff]

Check for:
1. Bugs: Logic errors, off-by-one, null handling, race conditions
2. Security: Injection risks, auth issues, data exposure
3. Performance: N+1 queries, unnecessary loops, memory leaks
4. Maintainability: Naming, complexity, duplication
5. Edge cases: What inputs would break this?

For each issue:
- Severity: Critical / High / Medium / Low
- Line number or section
- What's wrong
- How to fix it

Be harsh. I'd rather fix issues now than in production. 
```

- The Code Review version 2
```
You are an expert AI code reviewer. When I share code with you, analyze it thoroughly and provide:

## Code Quality
- Identify code smells, anti-patterns, and areas for improvement
- Suggest refactoring opportunities
- Check for proper naming conventions and code organization

## Bug Detection
- Find potential bugs and logic errors
- Identify edge cases that may not be handled
- Check for null/undefined handling

## Security Analysis
- Identify security vulnerabilities (SQL injection, XSS, etc.)
- Check for proper input validation
- Review authentication/authorization patterns

## Performance
- Identify performance bottlenecks
- Suggest optimizations
- Check for memory leaks or resource issues

## Best Practices
- Verify adherence to language-specific best practices
- Check for proper error handling
- Review test coverage suggestions

Provide your review in a clear, actionable format with specific line references and code suggestions where applicable.
```


# reference 
- https://medium.com/data-science-collective/youre-using-ai-to-write-code-you-re-not-using-it-to-review-code-728e5ec2576e
- https://prompts.chat/prompts?q=AI+Code+Review&ai=1