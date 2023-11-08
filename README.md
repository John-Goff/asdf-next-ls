<div align="center">

# asdf-next-ls [![Build](https://github.com/John-Goff/asdf-next-ls/actions/workflows/build.yml/badge.svg)](https://github.com/John-Goff/asdf-next-ls/actions/workflows/build.yml) [![Lint](https://github.com/John-Goff/asdf-next-ls/actions/workflows/lint.yml/badge.svg)](https://github.com/John-Goff/asdf-next-ls/actions/workflows/lint.yml)

[next-ls](https://www.elixir-tools.dev/docs/next-ls/quickstart/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add next-ls
# or
asdf plugin add next-ls https://github.com/John-Goff/asdf-next-ls.git
```

next-ls:

```shell
# Show all installable versions
asdf list-all next-ls

# Install specific version
asdf install next-ls latest

# Set a version globally (on your ~/.tool-versions file)
asdf global next-ls latest

# Now next-ls commands are available
nextls --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/John-Goff/asdf-next-ls/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [John Goff](https://github.com/John-Goff/)
