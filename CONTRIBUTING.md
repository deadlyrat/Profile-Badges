# Contributing to Profile-Badges

Thank you for your interest in improving this repository!

## How to Contribute

### Reporting Issues
- Open an issue describing what information is missing or incorrect.
- Include the badge name and what should be updated.

### Submitting a Pull Request

1. **Fork** this repository.
2. **Create a branch** from `main`:
   ```bash
   git checkout -b fix/badge-name-correction
   ```
3. **Make your changes** following the style guide below.
   4. **Open a pull request** against the `main` branch of this repo.

## Style Guide

Each row in the badge tables should follow this format:

```markdown
Badge Name | <img src="IMAGE_URL" width="175px"> | ``Yes`` or ``No`` | Description | Difficulty
```

- Badge image width: `175px` for main tables, `60px` for tier tables.
- Difficulty values: `Very Easy`, `Easy`, `Medium`, `Hard`.
- Use `✅ Yes` for earnable badges, `❌ No` for unobtainable, `👜 In testing` for beta.

## Verifying Badge Information

Before submitting, please verify:
- The badge image URL still works.
- The earning requirements are still accurate.
- The difficulty rating is appropriate.

## Code of Conduct

Be respectful and constructive in all interactions.
