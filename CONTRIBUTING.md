# Contributing to Issue & PR Automation Suite

Thank you for your interest in contributing! We welcome contributions from the community.

## How to Contribute

### Reporting Bugs

If you find a bug, please open an issue with:
- A clear, descriptive title
- Steps to reproduce the issue
- Expected behavior
- Actual behavior
- Your workflow configuration (redact sensitive information)
- Relevant logs from the workflow run

### Suggesting Enhancements

We welcome feature requests! Please open an issue with:
- A clear description of the feature
- Use cases that would benefit from this feature
- Any implementation ideas you might have

### Pull Requests

1. Fork the repository
2. Create a new branch for your feature (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Update documentation if needed
5. Test your changes thoroughly
6. Commit your changes (`git commit -m 'Add amazing feature'`)
7. Push to your branch (`git push origin feature/amazing-feature`)
8. Open a Pull Request

#### PR Guidelines

- Follow the existing code style
- Update the README.md if you're adding new features or changing behavior
- Add your changes to CHANGELOG.md under [Unreleased]
- Ensure the action.yml syntax is valid
- Test your changes in a real repository before submitting
- Keep PRs focused on a single feature or fix

### Development Setup

1. Clone the repository
2. Make changes to `action.yml`
3. Test locally by:
   - Creating a test repository
   - Adding a workflow that uses your local action:
     ```yaml
     uses: your-username/AutomationSuite@your-branch
     ```
   - Trigger the workflow and verify behavior

### Testing

Before submitting a PR, please test:
- All three features (project automation, label sync, ZAP labeling) independently
- Feature combinations (e.g., project + label sync)
- Edge cases (empty labels, missing projects, invalid issue references)
- Different event types (issue opened, PR created, labels changed, etc.)

### Documentation

- Update README.md for user-facing changes
- Add examples for new features
- Update input parameter documentation
- Keep the troubleshooting section up to date

## Code of Conduct

- Be respectful and inclusive
- Provide constructive feedback
- Focus on what's best for the community
- Show empathy towards other community members

## Questions?

Feel free to open an issue for any questions about contributing!

## License

By contributing, you agree that your contributions will be licensed under the MIT License.
