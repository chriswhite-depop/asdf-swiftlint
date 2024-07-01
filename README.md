<div align="center">

# asdf-swiftlint [![Build](https://github.com/chriswhite-depop/asdf-swiftlint/actions/workflows/build.yml/badge.svg)](https://github.com/chriswhite-depop/asdf-swiftlint/actions/workflows/build.yml) [![Lint](https://github.com/chriswhite-depop/asdf-swiftlint/actions/workflows/lint.yml/badge.svg)](https://github.com/chriswhite-depop/asdf-swiftlint/actions/workflows/lint.yml)

[swiftlint](https://github.com/chriswhite-depop/swiftlint) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add swiftlint
# or
asdf plugin add swiftlint https://github.com/chriswhite-depop/asdf-swiftlint.git
```

swiftlint:

```shell
# Show all installable versions
asdf list-all swiftlint

# Install specific version
asdf install swiftlint latest

# Set a version globally (on your ~/.tool-versions file)
asdf global swiftlint latest

# Now swiftlint commands are available
swiftlint --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/chriswhite-depop/asdf-swiftlint/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Chris White](https://github.com/chriswhite-depop/)
