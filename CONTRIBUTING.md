# Contributing Guidelines

*Pull requests, bug reports, and all other forms of contribution
are welcomed and highly encouraged!*

This guide serves to set clear expectations for everyone involved
with the project so that we can improve it together
while also creating a welcoming space for everyone to participate.
Following these guidelines will help ensure a positive experience
for contributors and maintainers.

## Table of Contents

- [Code of Conduct](#book-code-of-conduct)
- [Asking Questions](#bulb-asking-questions)
- [Opening an Issue](#inbox_tray-opening-an-issue)
- [Feature Requests](#jigsaw-feature-requests)
- [Triage of Issues](#label-triage-of-issues)
- [Submitting Pull Requests](#gift-submitting-pull-requests)
- [Writing Commit Messages](#memo-writing-commit-messages)
- [Code Review](#white_check_mark-code-review)
- [Coding Style](#recycle-coding-style)
- [Certificate of Origin](#medal_sports-certificate-of-origin)
- [Credits](#pray-credits)

## :book: Code of Conduct

Please review our [Code of Conduct](https://github.com/whisperpine/.github/blob/main/CODE_OF_CONDUCT.md).
It is in effect at all times.
We expect it to be honored by everyone who contributes to this project.

## :bulb: Asking Questions

See our [Support Guide](https://github.com/whisperpine/.github/blob/main/SUPPORT.md).
In short, GitHub issues are not the appropriate place
to debug your specific project,
but should be reserved for filing bugs and feature requests.

## :inbox_tray: Opening an Issue

Before [creating an issue](https://help.github.com/en/github/managing-your-work-on-github/creating-an-issue),
check if you are using the latest version of the project.
If you are not up-to-date, see if updating fixes your issue first.

### :shield: Reporting Security Issues

Review our [Security Policy](https://github.com/whisperpine/.github/blob/main/SECURITY.md).
**Do not** file a public issue for security vulnerabilities.

### :bug: Bug Reports and Other Issues

A great way to contribute to the project is to send a detailed issue
when you encounter a problem.
We always appreciate a well-written, thorough bug report. :v:

In short, since you are most likely a developer,
**provide a ticket that you would like to receive**.

- **Review the documentation and [Support Guide](https://github.com/whisperpine/.github/blob/main/SUPPORT.md)**
before opening a new issue.
- **Do not open a duplicate issue!** Search through existing issues
to see if your issue has previously been reported.
If your issue exists, comment with any additional information you have.
You may simply note "I have this problem too",
which helps prioritize the most common problems and requests.
- **Prefer using [reactions](https://github.blog/2016-03-10-add-reactions-to-pull-requests-issues-and-comments/)**,
not comments, if you simply want to "+1" an existing issue.
- **Fully complete the provided issue template.**
The bug report template requests all the information we need to quickly
and efficiently address your issue.
Be clear, concise, and descriptive.
Provide as much information as you can, including steps to reproduce,
stack traces, compiler errors, library versions, OS versions,
and screenshots (if applicable).
- **Use [GitHub-flavored Markdown](https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax).**
Especially put code blocks and console outputs in backticks (```).
This improves readability.

## :jigsaw: Feature Requests

Feature requests are welcome!
While we will consider all requests, we cannot guarantee your request will be accepted.
We want to avoid [feature creep](https://en.wikipedia.org/wiki/Feature_creep).
Your idea may be great, but also out-of-scope for the project.
If accepted, we cannot make any commitments regarding the timeline
for implementation and release. However, you are welcome
to submit a pull request to help!

- **Do not open a duplicate feature request.**
Search for existing feature requests first.
If you find your feature (or one very similar) previously requested,
comment on that issue.
- **Fully complete the provided issue template.**
The feature request template asks for all necessary information
for us to begin a productive conversation.
- Be precise about the proposed outcome of the feature
and how it relates to existing features.
Include implementation details if possible.

## :label: Triage of Issues

You can triage issues which may include reproducing bug reports or asking for
additional information, such as version numbers or reproduction instructions.
Any help you can provide to quickly resolve an issue is very much appreciated!

## :gift: Submitting Pull Requests

We **love** pull requests!
Before [forking the repo](https://help.github.com/en/github/getting-started-with-github/fork-a-repo)
and [creating a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/proposing-changes-to-your-work-with-pull-requests)
for non-trivial changes,
it is usually best to first open an issue to discuss the changes,
or discuss your intended approach for solving the problem
in the comments for an existing issue.

*Note: All contributions will be licensed under the project's license.*

- **Smaller is better.**
Submit **one** pull request per bug fix or feature.
A pull request should contain isolated changes
pertaining to a single bug fix or feature implementation.
**Do not** refactor or reformat code that is unrelated to your change.
It is better to **submit many small pull requests**
rather than a single large one.
Enormous pull requests will take enormous amounts of time to review,
or may be rejected altogether.
- **Coordinate bigger changes.**
For large and non-trivial changes,
open an issue to discuss a strategy with the maintainers.
Otherwise, you risk doing a lot of work for nothing!
- **Prioritize understanding over cleverness.**
Write code clearly and concisely.
Remember that source code usually gets written once and read often.
Ensure the code is clear to the reader.
The purpose and logic should be obvious to a reasonably skilled developer,
otherwise you should add a comment that explains it.
- **Follow existing coding style and conventions.**
Keep your code consistent with the style, formatting,
and conventions in the rest of the code base.
When possible, these will be enforced with a linter.
Consistency makes it easier to review and modify in the future.
- **Include test coverage.**
Add unit tests or UI tests when possible.
Follow existing patterns for implementing tests.
- **Update the example project** if one exists to exercise
any new functionality you have added.
- **Add documentation.**
Document your changes with code doc comments or in existing guides.
- **Use the repo's default branch.**
Branch from and [submit your pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request-from-a-fork)
to the repo's default branch. Usually this is `main`,
but it could be `dev`, `develop`, or `master`.
- **[Resolve any merge conflicts](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/resolving-a-merge-conflict-on-github)**
that occur.
- **Promptly address any CI failures.**
If your pull request fails to build or pass tests,
please push another commit to fix it.
- When writing comments, use properly constructed sentences, including punctuation.
- Use spaces, not tabs.

## :memo: Writing Commit Messages

Please adhere to
[Conventional Commits 1.0.0](https://www.conventionalcommits.org/)
initiative when the current repository adheres to.
This should be the case by default,
and exceptions are only for historical reasons.

## :white_check_mark: Code Review

- **Review the code, not the author.**
Look for and suggest improvements without disparaging or insulting the author.
Provide actionable feedback and explain your reasoning.
- **You are not your code.**
When your code is critiqued, questioned, or constructively criticized,
remember that you are not your code. Do not take code review personally.
- **Always do your best.**
No one writes bugs on purpose. Do your best, and learn from your mistakes.
- Kindly note any violations to the guidelines specified in this document.

## :recycle: Coding Style

Consistency is the most important.
Following the existing style, formatting, and naming conventions
of the file you are modifying and of the overall project.
Failure to do so will result in a prolonged review process
that has to focus on updating the superficial aspects of your code,
rather than improving its functionality and performance.

For example, if all private properties are prefixed with an underscore `_`,
then new ones you add should be prefixed in the same way.
Or, if methods are named using camelcase, like `thisIsMyNewMethod`,
then do not diverge from that by writing `this_is_my_new_method`.
You get the idea.
If in doubt, please ask or search the codebase for something similar.

When possible, style and format will be enforced with a linter.

## :medal_sports: Certificate of Origin

[Developer's Certificate of Origin 1.1](https://developercertificate.org/)

By making a contribution to this project, I certify that:

> (a) The contribution was created in whole or in part by me and I
> have the right to submit it under the open source license
> indicated in the file; or
>
> (b) The contribution is based upon previous work that, to the best
> of my knowledge, is covered under an appropriate open source
> license and I have the right under that license to submit that
> work with modifications, whether created in whole or in part
> by me, under the same open source license (unless I am
> permitted to submit under a different license), as indicated
> in the file; or
>
> (c) The contribution was provided directly to me by some other
> person who certified (a), (b) or (c) and I have not modified
> it.
>
> (d) I understand and agree that this project and the contribution
> are public and that a record of the contribution (including all
> personal information I submit with it, including my sign-off) is
> maintained indefinitely and may be redistributed consistent with
> this project or the open source license(s) involved.

If you are reading this, bravo dear user and (hopefully) contributor
for making it this far! You are awesome. :100:

## :pray: Credits

Written by [@whisperpine](https://github.com/whisperpine).

**Please feel free to adopt this guide in your own projects.
Fork it wholesale or remix it for your needs.**

*Many of the ideas and prose for the statements in this document were
based on or inspired by work from the following communities:*

- [jessesquires](https://github.com/jessesquires/.github/blob/main/CONTRIBUTING.md)
- [Alamofire](https://github.com/Alamofire/Alamofire/blob/master/CONTRIBUTING.md)
- [CocoaPods](https://github.com/CocoaPods/CocoaPods/blob/master/CONTRIBUTING.md)
- [Docker](https://github.com/moby/moby/blob/master/CONTRIBUTING.md)
- [Linux](https://elinux.org/Developer_Certificate_Of_Origin)

*We commend them for their efforts to facilitate collaboration in their projects.*
