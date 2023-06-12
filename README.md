<div align="center">

# asdf-tuist [![Build](https://github.com/cprecioso/asdf-tuist/actions/workflows/build.yml/badge.svg)](https://github.com/cprecioso/asdf-tuist/actions/workflows/build.yml) [![Lint](https://github.com/cprecioso/asdf-tuist/actions/workflows/lint.yml/badge.svg)](https://github.com/cprecioso/asdf-tuist/actions/workflows/lint.yml)

[tuist](https://tuist.io/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add tuist
# or
asdf plugin add tuist https://github.com/cprecioso/asdf-tuist.git
```

tuist:

```shell
# Show all installable versions
asdf list-all tuist

# Install specific version
asdf install tuist latest

# Set a version globally (on your ~/.tool-versions file)
asdf global tuist latest

# Now tuist commands are available
tuist version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/cprecioso/asdf-tuist/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Carlos Precioso](https://github.com/cprecioso/)
