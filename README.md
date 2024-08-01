# Github Best Practices

## Repository Naming Best Practices

- Descriptive and Clear
- Use Hyphens for Separation e.g. my-awesome-project
- Lowercase Letters
- Avoid Special Characters and Spaces
- Keep It Short but Descriptive
- Include Version Control e.g. project-v2 or project-2023.
- Avoid Generic Names: Generic names like test or project are not helpful and can cause confusion. Be specific about what the repository contains.

Some examples of good repository names
- personal-website
- data-analysis-scripts
- mobile-app-backend
- react-todo-app

Some examples of names to avoid
- myrepo
- test
- newproject




## Branch Naming Best Practices

### Use Descriptive Names
- Choose names that convey the purpose of the branch.
- Avoid vague names like `feature-branch` or `new-branch`.
- Example: `feature/user-authentication` instead of `feature-branch`.

### Follow a Consistent Naming Convention
- Establish a consistent naming convention at your team or project.
- This could include prefixes like `feature/`, `bugfix/`, or `hotfix/`.
- Example: `bugfix/issue-123` or `hotfix/security-patch`.

### Include Issue or Ticket Numbers
- Reference related issues or tickets in your branch names for traceability.
- Example: `feature/123-implement-new-feature`.

### Keep It Short and Sweet
- Aim for concise branch names that are easy to remember and type.
- Avoid excessively long names that may become cumbersome.
- Example: `refactor/user-service` instead of `refactor/improve-user-service-performance`.




## Commit Message Best Practices

### Start with a Capitalized Verb
- Example: `Add user authentication feature` or `Fix issue with data validation`.

### Limit the Line Length
- Keep each line of your commit message under 72 characters.
- This improves readability, especially in tools like git log.

### Provide Context
- Offer a brief explanation of why the change is necessary.
- Include any relevant background information.
- Example: `Update user authentication to enhance security`

### Use Imperative Mood
- Write commit messages in the imperative mood for clarity and consistency.
- Example: `Create new API endpoint` instead of `Creating new API endpoint`.

### Reference Related Issues
- Link your commit messages to related issues or tickets for comprehensive tracking.
- Example: `Fixes #123` or `Closes #456`.
