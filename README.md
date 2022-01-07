<div align="center">

# asdf-kube-dump [![Build](https://github.com/MxNxPx/asdf-kube-dump/actions/workflows/build.yml/badge.svg)](https://github.com/MxNxPx/asdf-kube-dump/actions/workflows/build.yml) [![Lint](https://github.com/MxNxPx/asdf-kube-dump/actions/workflows/lint.yml/badge.svg)](https://github.com/MxNxPx/asdf-kube-dump/actions/workflows/lint.yml)


[kube-dump](https://github.com/WoozyMasta/kube-dump) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add kube-dump
# or
asdf plugin add kube-dump https://github.com/MxNxPx/asdf-kube-dump.git
```

kube-dump:

```shell
# Show all installable versions
asdf list-all kube-dump

# Install specific version
asdf install kube-dump latest

# Set a version globally (on your ~/.tool-versions file)
asdf global kube-dump latest

# Now kube-dump commands are available
kube-dump --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/MxNxPx/asdf-kube-dump/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Palassis](https://github.com/MxNxPx/)
