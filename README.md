<div align="center">

# asdf-bashbot [![Build](https://github.com/mathew-fleisch/asdf-bashbot/actions/workflows/build.yml/badge.svg)](https://github.com/mathew-fleisch/asdf-bashbot/actions/workflows/build.yml) [![Lint](https://github.com/mathew-fleisch/asdf-bashbot/actions/workflows/lint.yml/badge.svg)](https://github.com/mathew-fleisch/asdf-bashbot/actions/workflows/lint.yml)


[bashbot](https://github.com/mathew-fleisch/bashbot-example) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add bashbot
# or
asdf plugin add bashbot https://github.com/mathew-fleisch/asdf-bashbot.git
```

bashbot:

```shell
# Show all installable versions
asdf list-all bashbot

# Install specific version
asdf install bashbot latest

# Set a version globally (on your ~/.tool-versions file)
asdf global bashbot latest

# Now bashbot commands are available
bashbot --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mathew-fleisch/asdf-bashbot/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Mathew Fleisch](https://github.com/mathew-fleisch/)
