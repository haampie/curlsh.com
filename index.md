@def title = "curl | sh"
@def hasmath = false
@def hascode = false


# curl | sh

A curated list of questionable installation instructions

## [🔗 codecov](https://docs.codecov.com/docs/codecov-uploader)

```console
curl -Os https://uploader.codecov.io/latest/linux/codecov

chmod +x codecov
./codecov -t ${CODECOV_TOKEN}
```

## [🔗 homebrew](https://brew.sh/)

```console
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## [🔗 miniconda](https://docs.anaconda.com/anaconda/install/silent-mode/#linux-macos)

```console
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh -O ~/miniconda.sh
bash ~/miniconda.sh -b -p $HOME/miniconda
```

## [🔗 oh-my-zsh](https://ohmyz.sh/)

```console
$ sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## [🔗 nix](https://nixos.org/download.html)

```console
$ curl -L https://nixos.org/nix/install | sh
```

## [🔗 poetry](https://python-poetry.org/docs/master/#installation)

```console
curl -sSL https://install.python-poetry.org | python3 -
```

## [🔗 rustup](https://www.rust-lang.org/tools/install)

```console
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

## [🔗 zoxide](https://github.com/ajeetdsouza/zoxide#step-1-install-zoxide)

```console
curl -sS https://webinstall.dev/zoxide | bash
```
