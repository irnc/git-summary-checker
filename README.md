# git-summary-checker

Check commit summary and pull request title for basic rules that summary is
explanatory and conveys action which is done by proposed changes.

Good examples:

- Explain project goals and reason for existence
- Initialize npm package using `npm init`

Summaries for which we should raise flag:

- Changed package.json
- Fixed navigation issues

## Why sumamry should be explanatory?

Because it eases code review, allows to share knowledge and it does not confuse
commit log readers.

## Roadmap

1. Implement web page for cheking statuses from form and query param.
2. Implement GitHub status checker.
