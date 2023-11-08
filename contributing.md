# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test asdf-next-ls https://github.com/John-Goff/asdf-next-ls.git "nextls --help"
```

Tests are automatically run in GitHub Actions on push and PR.
