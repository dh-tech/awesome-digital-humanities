# Contribution Guidelines

This project follows a [Contributor Code of Conduct](CODE_OF_CONDUCT.md).
By participation, you agree to its terms.

This file is the only source for the contribution process.

## Summary

| You want to | What to do |
| --- | --- |
| Add a new resource | Open an [Addition issue](https://github.com/dh-tech/awesome-digital-humanities/issues/new?template=addition.yml). Wait for maintainer approval. Then open a pull request. |
| Fix a description, fix a broken link, or remove an entry | Open a pull request directly. You do not need an issue. |

## Add a new resource

All contributors must follow these steps. This includes returning contributors.

1. Open an [Addition issue](https://github.com/dh-tech/awesome-digital-humanities/issues/new?template=addition.yml).
2. Wait for a maintainer to approve the proposal in a comment on the issue.
3. Open one pull request for the approved resource.
4. Add the URL of the approved issue to the pull request description.

An Addition issue does not guarantee inclusion.

### What the issue must contain

The Addition form asks for these items:

1. The name and URL of the resource.
2. A concrete digital-humanities research use case.
3. The scholarly value that distinguishes the resource from existing tools.
4. Evidence that the resource is useful. Documentation, methods, research applications, publications, or reproducible examples are all valid evidence.
5. The license, the price, and any access limits.
6. Your affiliation with the project, or your commercial relationship to it. Write "none" if you have none.
7. Whether AI helped you prepare the proposal.

### How maintainers assess a proposal

Maintainers assess each proposal on its evidence:

- The resource supports a real digital-humanities research task.
- The resource offers value that existing entries do not offer.
- Documentation or examples show that the resource works.
- The resource is available to researchers, and its access terms are clear.

We prefer free and open-source resources.
We can also consider commercial and proprietary services when they offer clear, demonstrable research value.

We do not require academic publications, institutional affiliation, or a minimum number of GitHub stars.
Such rules would exclude useful niche tools.

## Correct or remove an entry

You can open a pull request directly for these changes:

- Improve a description.
- Fix a broken link.
- Remove an obsolete entry.

Explain the reason in the pull request description.

## AI and automation

- We welcome contributions that a human wrote.
- We welcome AI-assisted contributions when an accountable human has reviewed and understood them.
- Autonomous AI agents must not submit issues or pull requests without human review.
- We do not accept mass-produced promotional submissions, repeated unsolicited advertisements, or duplicate submissions.
- You must disclose material AI assistance.
- You must disclose a relevant commercial interest.

Maintainers assess submissions on their evidence and conduct.
They do not judge whether the writing sounds AI-generated.

## Pull request requirements

Each pull request must meet these requirements:

- It adds, edits, or removes one entry.
- The entries stay in alphabetical order.
- The table of contents is up to date when a section is added or removed.
- The `awesome-lint` check passes.
- The addition is not part of [everything that did not make it into the list](https://github.com/maehr/awesome-digital-history/wiki).
- An addition links to its approved Addition issue.

Pull requests opened before this policy took effect stay under the previous rules.

## How maintainers enforce this process

- A maintainer can ask for more information on an incomplete proposal.
- A maintainer can close an addition pull request that has no approved issue. The maintainer links to this file.
- A maintainer can close repeated promotional or automated submissions without a full review.
- Maintainers keep editorial discretion.
- Maintainers give a short reason when they decline a submission.
- Maintainers use neutral language. They do not accuse a person of being a bot without evidence.

## Updating your pull request

Maintainers can ask you to change your pull request before they merge it.
Edit the existing pull request. Do not open a new one.
If you are not sure how, read
[this guide](https://github.com/RichardLitt/knowledge/blob/master/github/amending-a-commit-guide.md).

## Appendix: run the lint test

To run the test on your computer:

    # using ruby
    gem install awesome_bot
    awesome_bot README.md
    # using node.js
    npm install -g awesome-lint
    awesome-lint README.md
