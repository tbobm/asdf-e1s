<div align="center">

# asdf-e1s [![Build](https://github.com/tbobm/asdf-e1s/actions/workflows/build.yml/badge.svg)](https://github.com/tbobm/asdf-e1s/actions/workflows/build.yml) [![Lint](https://github.com/tbobm/asdf-e1s/actions/workflows/lint.yml/badge.svg)](https://github.com/tbobm/asdf-e1s/actions/workflows/lint.yml)

[e1s](https://github.com/keidarcy/e1s) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add e1s
# or
asdf plugin add e1s https://github.com/tbobm/asdf-e1s.git
```

e1s:

```shell
# Show all installable versions
asdf list-all e1s

# Install specific version
asdf install e1s latest

# Set a version globally (on your ~/.tool-versions file)
asdf global e1s latest

# Now e1s commands are available
e1s --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/tbobm/asdf-e1s/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Theo Bob Massard](https://github.com/tbobm/)
