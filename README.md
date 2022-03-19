# test-commit-lint
test conventional commits

>[What is commit lint?](https://github.com/conventional-changelog/commitlint)

## Instructions
1. [Install commit-lint](https://commitlint.js.org/#/guides-local-setup?id=guide-local-setup)

### FAQ:  
Test if we can add a second -m as body for breaking changes'  
Todo this, your command needs to look like this:  
`git commit -am 'fix(textArea): can now specify required' -m 'BREAKING CHANGE: textArea now defaults to not required when no prop is specified'`