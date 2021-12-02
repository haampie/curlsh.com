@def title = "curl | sh"
@def hasmath = false
@def hascode = false


# curl | sh

A curated list of snippets on the web that encourage you to skip checksum validation.

## [codecov](https://docs.codecov.com/docs/codecov-uploader)

```console
curl -Os https://uploader.codecov.io/latest/linux/codecov

chmod +x codecov
./codecov -t ${CODECOV_TOKEN}
```

## [nix](https://nixos.org/download.html)

```console
$ curl -L https://nixos.org/nix/install | sh
```

## [rustup](https://www.rust-lang.org/tools/install)

```console
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
