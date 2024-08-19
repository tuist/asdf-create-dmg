# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test create-dmg https://github.com/tuist/asdf-create-dmg.git "create-dmg --version"
```

Tests are automatically run in GitHub Actions on push and PR.
