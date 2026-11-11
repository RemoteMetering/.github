## Summary

<!-- What does this PR change, and why? Keep it to a few sentences. -->

## Linked work item

<!-- Link the issue, ticket or story. Use "Closes #123" to auto-close a GitHub issue. -->

## Type of change

- [ ] Bug fix (non-breaking change that fixes an issue)
- [ ] New feature (non-breaking change that adds functionality)
- [ ] Breaking change (existing behaviour or contracts change)
- [ ] Refactor (no functional change)
- [ ] Dependency or tooling update
- [ ] Infrastructure, CI/CD or configuration change
- [ ] Documentation only

## How to test

<!-- Steps a reviewer can follow to verify the change. Include test data, URLs or commands. -->

## Screenshots or output

<!-- For UI, API or report changes. Delete this section if not relevant. -->

---

## Full branch code review (required)

<!--
Run a code review over the complete diff between this branch and the target branch,
not only the latest commit. Commit and push all work first, because the review
covers committed changes only. Implement the findings before requesting review.

Prompt for Claude Code:

  Do a /code-review on xhigh over the entire branch diff, exclude uncommitted changes and merge commits
-->

- [ ] All my work was committed and pushed before I ran the review
- [ ] I ran a code review over the full branch diff against the target branch, not only recent commits
- [ ] I implemented all findings
- [ ] I re-ran the review after implementing changes, and it raised no new issues
- [ ] I ran a /simplify pass over the entire branch diff

---

## Author checklist

### Branch hygiene

- [ ] The branch is up to date with the target branch and has no merge conflicts
- [ ] The PR has a single, clear purpose and is a reasonable size to review
- [ ] Commit messages are meaningful
- [ ] I removed debug code, commented-out code and stray TODOs

### Code quality

- [ ] The code follows our team conventions and style guides
- [ ] Linting and formatting pass locally
- [ ] Error handling covers expected failure paths
- [ ] Comments explain non-obvious logic and are contextual to the project, not prompts
- [ ] No deprecated libraries or patterns were introduced

### Testing

- [ ] I added or updated unit tests for the change
- [ ] I added or updated integration tests where relevant
- [ ] All tests pass locally
- [ ] I tested edge cases and failure scenarios
- [ ] CI checks pass

### Security and data

- [ ] No secrets, credentials, API keys or connection strings are in the code, config or commit history
- [ ] No personal or customer data (PII) is exposed in code, logs, tests or fixtures
- [ ] Authentication and authorisation changes have been reviewed with extra care
- [ ] New dependencies come from trusted sources and have no known vulnerabilities

### Data and deployment

- [ ] Configuration or environment changes are documented, or not applicable
- [ ] A rollback plan exists for this change
- [ ] The package version is updated, or not applicable

### Observability

- [ ] Logging is meaningful and contains no sensitive data

### Documentation

- [ ] README, API docs or scripts are updated where relevant
- [ ] The changelog is updated, or not applicable

---

## Breaking changes and migration notes

<!-- Describe what breaks, who is affected and the steps to migrate. Write "None" if not applicable. -->

## Deployment notes

<!-- Ordering, feature flags, manual steps or downtime. Write "None" if not applicable. -->

## Notes for reviewers

<!-- Areas you want extra attention on, known limitations or open questions. -->