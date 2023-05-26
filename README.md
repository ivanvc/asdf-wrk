<div align="center">

# asdf-wrk [![Build](https://github.com/ivanvc/asdf-wrk/actions/workflows/build.yml/badge.svg)](https://github.com/ivanvc/asdf-wrk/actions/workflows/build.yml) [![Lint](https://github.com/ivanvc/asdf-wrk/actions/workflows/lint.yml/badge.svg)](https://github.com/ivanvc/asdf-wrk/actions/workflows/lint.yml)


[wrk](https://github.com/wg/wrk) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, `make`: generic POSIX utilities.
- `gcc`

# Install

Plugin:

```shell
asdf plugin add wrk
# or
asdf plugin add wrk https://github.com/ivanvc/asdf-wrk.git
```

wrk:

```shell
# Show all installable versions
asdf list-all wrk

# Install specific version
asdf install wrk latest

# Set a version globally (on your ~/.tool-versions file)
asdf global wrk latest

# Now wrk commands are available
wrk --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/ivanvc/asdf-wrk/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ivan Valdes](https://github.com/ivanvc/)
