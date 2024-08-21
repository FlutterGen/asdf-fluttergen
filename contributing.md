# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test fluttergen git@github.com:FlutterGen/asdf-fluttergen.git "fluttergen -v"
```

Tests are automatically run in GitHub Actions on push and PR.
