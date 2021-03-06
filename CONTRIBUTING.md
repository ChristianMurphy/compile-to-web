# Contributing

## Requesting a new language

1. [Open an issue on GitHub](https://github.com/ChristianMurphy/compile-to-web/issues/new)
2. Include the name of the language in the issue title
3. Include links to any resources you may have found on how to compile that language to WASM
4. Consider opening a [Pull Request](https://github.com/Roshanjossey/first-contributions#readme) adding the language (See "Adding a new language" below)
5. Thats all! Thanks for contributing! :bow:

## Reporting a bug

1. [Open an issue on GitHub](https://github.com/ChristianMurphy/compile-to-web/issues/new)
2. Include the name of the language in the issue title
3. Include any logs or stacktraces in a [Markdown fenced block](https://help.github.com/articles/creating-and-highlighting-code-blocks/)
4. Consider opening a [Pull Request](https://github.com/Roshanjossey/first-contributions#readme) resolving the issue.
5. Thats all! Thanks for contributing! :bow:

## Adding a new language

1. First time opening a Pull Request? [Checkout this Pull Request guide!](https://github.com/Roshanjossey/first-contributions#readme)
2. Add a new folder for the language with the following files:
  * `hello.{language extension}` for example `hello.go` for Go lang
  * `Vagrantfile`
  * `scripts`
3. Commit changes
4. Add `install` and `build` steps to `scripts`
5. Commit changes
6. Open a Pull Request
7. Review and updates to Pull Request
8. PR merged
9. Thats all! Thanks for Contributing! :bow:
