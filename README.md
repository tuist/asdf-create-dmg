<div align="center">

# asdf-create-dmg [![Build](https://github.com/tuist/asdf-create-dmg/actions/workflows/build.yml/badge.svg)](https://github.com/tuist/asdf-create-dmg/actions/workflows/build.yml) [![Lint](https://github.com/tuist/asdf-create-dmg/actions/workflows/lint.yml/badge.svg)](https://github.com/tuist/asdf-create-dmg/actions/workflows/lint.yml)

[create-dmg](https://github.com/create-dmg/create-dmg/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Install

Plugin:

```shell
asdf plugin add create-dmg
# or
asdf plugin add create-dmg https://github.com/tuist/asdf-create-dmg.git
```

create-dmg:

```shell
# Show all installable versions
asdf list-all create-dmg

# Install specific version
asdf install create-dmg latest

# Set a version globally (on your ~/.tool-versions file)
asdf global create-dmg latest

# Now create-dmg commands are available
create-dmg --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/tuist/asdf-create-dmg/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Tuist](https://github.com/tuist/)
