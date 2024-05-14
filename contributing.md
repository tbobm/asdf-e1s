# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test e1s https://github.com/tbobm/asdf-e1s.git "e1s --help"
```

Tests are automatically run in GitHub Actions on push and PR.
