# Neatziti

A modern, geometric typeface. Influenced by other popular geometric, minimalist sans-serif typefaces of the new millenium. Designed for optimal readability at small point sizes while beautiful at large point sizes.

---

Build instructions
------------------

```
python3 -m venv venv
. venv/bin/activate  # Unixoids...
venv/Scripts/activate  # ...or on Windows cmd.exe or PowerShell

pip3 install meson ninja  # Unless already present on system.
pip3 install -r requirements.txt

meson build
ninja -C build install
```

### Where am I?

See [Documentation](./docs/Documentation.md).

## License

Licensed under Open Font License (OFL). See [LICENSE](./LICENSE).

### Attribution

neatziti is based upon the work done by @chrismsimpson on [Metropolis](https://github.com/chrismsimpson/Metropolis).
