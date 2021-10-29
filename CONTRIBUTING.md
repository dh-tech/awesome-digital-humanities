# Contribution Guidelines

Please note that this project is released with a
[Contributor Code of Conduct](CODE_OF_CONDUCT.md). By participating in this
project you agree to abide by its terms.

---

## We welcome

- **Additions**: restricted to addition of one new entry per pull-request.
- **Removals**: restricted to removal of one obsolete entry per pull-request.
- **Edits**: you may correct the descriptions if it can be improved.

---

  If you are proficient with GitHub, follow the instructions below. Otherwise open an [issue](https://github.com/dh-tech/awesome-dhtools/issues/new/choose).

---

## Criteria for accepting a pull-request

*Contributors, make sure that*:

- a **short pitch** is included in the pull-request description,
- the table of contents has been updated (if a section is added / removed),
- the contents are sorted **alphabetically**,
- The addition you proposed is NOT part of [everything that did not make it into the list](https://github.com/maehr/awesome-digital-history/wiki).

Thank you for your suggestions!

*Maintainers, make sure that*:

- the above criteria are followed,
- the tests pass on the CI,
- in case of addition or removal, make an assessment of
  awesomeness of the entry.

## Updating your PR

A lot of times, making a PR adhere to the standards above can be difficult.
If the maintainers notice anything that we'd like changed, we'll ask you to
edit your PR before we merge it. There's no need to open a new PR, just edit
the existing one. If you're not sure how to do that,
[here is a guide](https://github.com/RichardLitt/knowledge/blob/master/github/amending-a-commit-guide.md)
on the different ways you can update your PR so that we can merge it.

## Appendix: running lint tests

To run tests locally:

    # using ruby
    gem install awesome_bot
    awesome_bot README.md
    # using node.js
    npm install -g awesome-lint
    awesome-lint README.md
