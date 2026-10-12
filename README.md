# SIG CX Test Suite

Central place to report **bugs** and request **features** for the **Catena-X Test Suite** during its beta testing phase and go-live operations.

This repository contains no source code. It is the public feedback channel between Test Suite users and the team that builds and operates it.

## Table of contents

- [How to report an issue](#how-to-report-an-issue)
  - [🐞 Report a bug](#-report-a-bug)
  - [✨ Request a feature](#-request-a-feature)
  - [Adding screenshots](#adding-screenshots)
- [What happens after you open an issue](#what-happens-after-you-open-an-issue)
- [Guidelines](#guidelines)
- [Maintainers](#maintainers)
- [License](#license)

## How to report an issue

1. Go to [**Issues → New issue**](https://github.com/catenax-eV/sig-cx-test-suite/issues/new/choose).
2. Choose one of the templates below and fill in the form.
3. Before opening a new issue, please [search the existing issues](https://github.com/catenax-eV/sig-cx-test-suite/issues?q=is%3Aissue) to avoid duplicates. If you find one that matches, add a 👍 or a comment instead.

Blank issues are disabled, so every report uses one of the templates.

### 🐞 Report a bug

Use the [**Bug Report**](https://github.com/catenax-eV/sig-cx-test-suite/issues/new?template=bug_report.yml) template when something in the Test Suite does not work as expected.

You will be asked for:

| Field | Required | Description |
|---|:---:|---|
| Bug description | ✅ | What went wrong |
| Steps to reproduce | ✅ | How we can trigger the problem ourselves |
| Expected / actual behavior | ✅ | What should have happened and what happened instead |
| Phase | ✅ | `Beta testing`, `Go-live operations` or `Other` |
| Severity | ✅ | `Critical`, `High`, `Medium` or `Low` |
| Environment | ✅ | `PROD` or `DEV` |
| Test Suite version | | Version or release, if known (e.g. `v1.2.0`) |
| Logs or payloads | | Pasted as text, shown as a code block |
| Screenshots | | Images showing the problem |

Bug reports get the issue type **Bug** and the `bug` label.

### ✨ Request a feature

Use the [**Feature Request**](https://github.com/catenax-eV/sig-cx-test-suite/issues/new?template=feature_request.yml) template to suggest a new test case, an improvement or anything else that would make the Test Suite more useful.

You will be asked for:

| Field | Required | Description |
|---|:---:|---|
| Problem statement | ✅ | The problem or need behind the request |
| Proposed solution | ✅ | What you would like to happen |
| Area | ✅ | New test case, existing test case, reporting, usability, documentation or other |
| Priority | ✅ | `High`, `Medium` or `Low` |
| Alternatives considered | | Workarounds or other options you thought about |
| Screenshots or mockups | | Images that illustrate the idea |

Feature requests get the issue type **Feature** and the `enhancement` label.

### Adding screenshots

The **Screenshots** fields accept images. You can:

- drag and drop image files into the field,
- paste an image from the clipboard (e.g. a screenshot you just took), or
- click the attach area at the bottom of the field to choose a file.

You can write text between images to explain what each one shows.

## What happens after you open an issue

1. A bot thanks you for the report.
2. The code owners are assigned to the issue, and they and the test suite maintainers team are notified.
3. The team triages the issue (it is labeled `triage` until then), may ask follow-up questions in the comments, and keeps you updated on progress.

Please keep an eye on your GitHub notifications so you don't miss questions about your report.

## Guidelines

- **No sensitive data.** This repository is **public**. Never include passwords, tokens, client secrets, API keys, personal data or confidential business information in issues, logs or screenshots. Redact them before posting.
- **One topic per issue.** Open separate issues for separate problems or ideas so each can be tracked on its own.
- **Be specific.** Exact steps, timestamps, test case names and the environment make it much faster to reproduce and fix a bug.
- **Be respectful.** Keep the discussion constructive and friendly.

## Maintainers

Issues and pull requests in this repository are reviewed by the people listed in [`.github/CODEOWNERS`](.github/CODEOWNERS), supported by the CX Test Suite maintainers team.

## License

This repository is licensed under the [Apache License 2.0](LICENSE).
