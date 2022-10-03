# Setup Rsync

[![Action test on Ubuntu](https://github.com/GuillaumeFalourd/setup-rsync/actions/workflows/ubuntu_action_test.yml/badge.svg)](https://github.com/GuillaumeFalourd/setup-rsync/actions/workflows/ubuntu_action_test.yml) [![Action test on MacOS](https://github.com/GuillaumeFalourd/setup-rsync/actions/workflows/macos_action_test.yml/badge.svg)](https://github.com/GuillaumeFalourd/setup-rsync/actions/workflows/macos_action_test.yml) [![Action test on Windows](https://github.com/GuillaumeFalourd/setup-rsync/actions/workflows/windows_action_test.yml/badge.svg)](https://github.com/GuillaumeFalourd/setup-rsync/actions/workflows/windows_action_test.yml)

![rsync](https://user-images.githubusercontent.com/22433243/157238945-fc0f23e3-f83b-480c-a324-9e9288e2ab19.png)

☞ Github actions to setup [Rsync](https://linux.die.net/man/1/rsync) 🔄

_**Note**: This action is supported on **all runners** operating systems (`ubuntu`, `macos`, `windows`)_

## 📚 Usage

### Ubuntu

```yaml
    runs-on: ubuntu-latest
    steps:
      - uses: GuillaumeFalourd/setup-rsync@v1
      - run: rsync --version
```

### MacOs

```yaml
    runs-on: macos-latest
    steps:
      - uses: GuillaumeFalourd/setup-rsync@v1.1
      - run: rsync --version
```

### Windows

```yaml
    runs-on: windows-latest
    steps:
      - uses: GuillaumeFalourd/setup-rsync@v1.1
      - run: rsync --version
```

## 🤝 Contributing

☞ If you're interested in contributing to this repository, please follow the [guidelines](https://github.com/GuillaumeFalourd/setup-rsync/blob/main/CONTRIBUTING.md)

## 🏅 Licensed

☞ This repository uses the [Apache License 2.0](https://github.com/GuillaumeFalourd/setup-rsync/blob/main/LICENSE)

<!-- ### Contribuidores

<a href="https://github.com/GuillaumeFalourd/setup-rsync/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=GuillaumeFalourd/setup-rsync" />
</a>

(Criado com [contributors-img](https://contrib.rocks)) -->
