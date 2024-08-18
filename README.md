<div align="center">

# asdf-keepassx-cli [![Build](https://github.com/mrjk/asdf-keepassx-cli/actions/workflows/build.yml/badge.svg)](https://github.com/mrjk/asdf-keepassx-cli/actions/workflows/build.yml) [![Lint](https://github.com/mrjk/asdf-keepassx-cli/actions/workflows/lint.yml/badge.svg)](https://github.com/mrjk/asdf-keepassx-cli/actions/workflows/lint.yml)

[keepassx-cli](https://github.com/mrjk/keepassx-cli) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add keepassx-cli
# or
asdf plugin add keepassx-cli https://github.com/mrjk/asdf-keepassx-cli.git
```

keepassx-cli:

```shell
# Show all installable versions
asdf list-all keepassx-cli

# Install specific version
asdf install keepassx-cli latest

# Set a version globally (on your ~/.tool-versions file)
asdf global keepassx-cli latest

# Now keepassx-cli commands are available
keepassx-cli --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mrjk/asdf-keepassx-cli/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [mrjk](https://github.com/mrjk/)
