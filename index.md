@def title = "curl | sh"
@def hasmath = false
@def hascode = false


# curl | sh

A non-exhaustive list of snippets on the web that encourage you to run untrusted code.

## [codecov](https://docs.codecov.com/docs/codecov-uploader)

```console
curl -Os https://uploader.codecov.io/latest/linux/codecov

chmod +x codecov
./codecov -t ${CODECOV_TOKEN}
```

## [rustup](https://www.rust-lang.org/tools/install)

```console
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```