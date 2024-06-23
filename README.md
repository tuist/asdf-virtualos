<div align="center">

# asdf-virtualos [![Build](https://github.com/tuist/asdf-virtualos/actions/workflows/build.yml/badge.svg)](https://github.com/tuist/asdf-virtualos/actions/workflows/build.yml) [![Lint](https://github.com/tuist/asdf-virtualos/actions/workflows/lint.yml/badge.svg)](https://github.com/tuist/asdf-virtualos/actions/workflows/lint.yml)

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add virtualos
# or
asdf plugin add virtualos https://github.com/tuist/asdf-virtualos.git
```

virtualos:

```shell
# Show all installable versions
asdf list-all virtualos

# Install specific version
asdf install virtualos latest

# Set a version globally (on your ~/.tool-versions file)
asdf global virtualos latest

# Now virtualos commands are available
virtualos --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/tuist/asdf-virtualos/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Tuist](https://github.com/tuist/)
