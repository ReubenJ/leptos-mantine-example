# Leptos + Mantine Example

Exploring the Leptos framework and attempting to use the [Mantine UI framework](https://mantine.dev/) in the process.

## Development

### Rust Environment
You'll need a (nightly) Rust toolchain installed to build and run the whole app.

I use `cocogitto` to keep pretty commits and changelogs and `cargo-leptos` for... well, Leptos.

```bash
cargo install cocogitto
cargo install --locked cargo-leptos
```

### Conda Environment
Conda or Mamba is needed to create an environment from the `environment.yml` file.
I recommend Mamba ([`Mambaforge` installation instructions](https://mamba.readthedocs.io/en/latest/installation.html)).
Once installed, run the following commands from the base directory of this project.

```bash
mamba env create && mamba activate leptos-mantine-example
```

### Pre-commit

Once the environmet is installed and activated, install the pre-commit hooks using

```bash
pre-commit install --install-hooks
```

You can now run the pre-commit checks at any time with

```bash
pre-commit run
```
