<div align="center">

# asdf-fluttergen [![Build](https://github.com/FlutterGen/asdf-fluttergen/actions/workflows/build.yml/badge.svg)](https://github.com/FlutterGen/asdf-fluttergen/actions/workflows/build.yml) [![Lint](https://github.com/FlutterGen/asdf-fluttergen/actions/workflows/lint.yml/badge.svg)](https://github.com/FlutterGen/asdf-fluttergen/actions/workflows/lint.yml)

[FlutterGen](https://github.com/FlutterGen/flutter_gen) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add fluttergen
# or
asdf plugin add fluttergen https://github.com/FlutterGen/asdf-fluttergen.git
```

fluttergen:

```shell
# Show all installable versions
asdf list-all fluttergen

# Install specific version
asdf install fluttergen latest

# Set a version globally (on your ~/.tool-versions file)
asdf global fluttergen latest

# Now fluttergen commands are available
fluttergen -v
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/FlutterGen/asdf-fluttergen/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [FlutterGen](https://github.com/FlutterGen/)
