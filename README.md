# Samu-K/homebrew-tap

Homebrew formulae for [macos-qemu-gl](https://github.com/Samu-K/macos-qemu-ql).

```sh
brew unlink qemu              # only if Homebrew's qemu is installed; the two conflict
brew install samu-k/tap/qemu-gl
```

| Formula | What it is |
|---|---|
| `qemu-gl` | QEMU for Apple Silicon with OpenGL acceleration for Linux guests (`-device virtio-gpu-gl-pci -display cocoa,gl=es`). A signed, notarized, self-contained build. |

`Formula/qemu-gl.rb` is generated and committed by the
[release workflow](https://github.com/Samu-K/macos-qemu-ql/blob/main/.github/workflows/homebrew-tap.yml)
of macos-qemu-ql; change it there, not here.
