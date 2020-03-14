# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]
asdf plugin test gcloud https://github.com/jthegedus/asdf-firebase.git firebase --version
```

Tests are automatically run in GitHub Actions on push and PR.
