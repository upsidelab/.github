# Contributing guide

We're glad for your interest in our projects and taking the time to contribute 🧡

We created a set of rules and hints to make this process as easy and transparent as possible.

## Creating Issue and Pull Request

Submitting changes requires an issue to describe what you want to change and why. Secondly you will need to start a new pull request where your progress is tracked and all discussions related to your implementation is kept.

1. Create an issue
2. Fork the repository
3. Open a pull request and use the appropriate label if possible

### Naming convention

Make sure your commits as well as a title of the pull request match the repository convention described in "contributing guide" (CONTRIBUTING.md/docs/README.md/...) for each repository.

### Tips
Feel free to make yourself familiar with [conventional commits](https://www.conventionalcommits.org) convention. It's widely used in some of our repositories.

The seven rules of a great Git commit message

1. Separate subject from body with a blank line
2. Limit the subject line to 50 characters
3. Capitalize the subject line
4. Do not end the subject line with a period
5. Use the imperative mood in the subject line (**if applied, this commit will <...>**)
6. Wrap the body at 72 characters
7. Use the body to explain what and why vs. how

## Creating a new repository

Consistency is a key. Following rules make sure, we keep our style the same across all repositories.

Generally, the rule of thumb is to use **kebab-case** when creating new repository. However, there are some exceptions from this rule:

#### Platform-specific
Generally, the ones that already use some particular name convention. Repository name should then be formatted accordingly.

>Examples:
> - spree-related repositories (Spree's convention implies using snake_case)
> - ruby gems (current convention implies using snake_case)
> - forked repositories (there's no functionality of creating an alias for forked repositories)
> - ...
