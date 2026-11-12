# Contributing

Thank you for helping improve this project. Contributions can include bug reports, feature suggestions, documentation, usability improvements, and code changes.

## Report a Bug

Search existing Issues before opening a new one. Include:

- A clear title and description.
- Steps to reproduce the problem.
- Expected behavior and actual behavior.
- Browser, operating system, and application version or commit, if known.
- Whether you used the hosted website or opened the HTML file locally.
- A small example using fictional data, plus screenshots when helpful.

Never include passwords, API keys, customer information, financial records, or private backups in public issues, screenshots, or pull requests.

## Suggest a Feature

Open an Issue describing the problem you want to solve, who would benefit, and an example of the proposed behavior. Discuss major changes before implementing them so the approach can be agreed upon.

## Make a Code or Documentation Change

1. Fork the repository to your GitHub account.
2. Create a branch with a descriptive name, such as `fix/copy-button` or `docs/getting-started`.
3. Make a focused change. The application entry point is `index.html`; usage instructions are in `README.md`.
4. Test the affected behavior using the checklist below.
5. Commit your changes with a descriptive message.
6. Open a pull request targeting this repository's `main` branch.

For small documentation fixes, GitHub's web editor can guide you through creating a fork and pull request.

## Development Guidelines

- Follow the existing code style and application structure.
- Keep changes focused and avoid unrelated rewrites or formatting changes.
- Preserve local browser operation and existing data compatibility.
- Avoid introducing external dependencies or network requests without discussing the need first.
- Do not commit real datasets, backups, credentials, or unrelated generated files.
- Update the README when behavior, setup steps, dependencies, or limitations change.
- For storage changes, explain migration behavior and how existing users can preserve their data.

## Testing Checklist

No build step is currently required. Open `index.html` in a modern browser to test locally. If hosted-site behavior is affected, also test an HTTPS preview when available.

- Reproduce the original issue, then verify the change resolves it.
- Check the affected workflow and nearby functionality.
- Check the browser console for new errors.
- Check the layout at a smaller screen size for interface changes.
- Use synthetic data and a separate browser profile when testing data changes.
- For trackers, check save/reload behavior and affected backup, restore, import, or export functions.
- For text and formula tools, check representative inputs, empty input, and copy/download behavior where applicable.
- Test offline behavior if the change affects functionality intended to work offline.

Record what you actually tested and identify checks you could not complete. Tests should cover meaningful behavior rather than simply repeat the implementation.

## Pull Request Details

Include the following in your pull request:

- **Problem:** What issue or need does this address?
- **Changes:** What behavior changes?
- **Validation:** What browser and scenarios did you test?
- **Screenshots:** Before and after, if the interface changed.
- **Data impact:** Any changes to stored data, imports, exports, or backup compatibility.
- **Related issue:** Link the relevant Issue, if one exists.

The maintainer reviews proposed changes and may request revisions before merging. Opening a pull request does not automatically update the published application.

## Respectful Collaboration

Keep feedback constructive and focused on the work. Explain problems clearly, respect different experience levels, and give others time to respond.

## License

Review the repository's LICENSE file before contributing. If no license is present or the terms are unclear, ask the maintainer to clarify the intended terms before submitting code. This guide does not grant a software license.
