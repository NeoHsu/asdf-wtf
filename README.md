<div align="center">

# asdf-wtfutil ![Build](https://github.com/NeoHsu/asdf-wtfutil/workflows/Build/badge.svg) ![Lint](https://github.com/NeoHsu/asdf-wtfutil/workflows/Lint/badge.svg)

[wtfutil](https://wtfutil.com/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add wtfutil
# or
asdf plugin add wtfutil https://github.com/NeoHsu/asdf-wtfutil.git
```

wtfutil:

```shell
# Show all installable versions
asdf list-all wtfutil

# Install specific version
asdf install wtfutil latest

# Set a version globally (on your ~/.tool-versions file)
asdf global wtfutil latest

# Now wtfutil commands are available
wtfutil --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/NeoHsu/asdf-wtfutil/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Neo Hsu](https://github.com/NeoHsu/)
