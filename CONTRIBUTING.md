# Contributing

Thank you for considering contributing to this FluffOS fork.

## Scope of this fork

This repository focuses on build reliability, compiler warning cleanup, and Windows/MSYS2 installation stability. If your change falls outside that scope, please consider contributing directly to the upstream project first.

## How to contribute

1. **Fork** the repository and create a feature branch.
2. **Keep changes focused** and avoid unrelated refactors.
3. **Add tests** where practical, especially for behavior changes.
4. **Update documentation** if the change affects build, usage, or public APIs.

## Build & test

```bash
rm -rf build && mkdir build && cd build
cmake ..
cmake --build . --target install
```

For tests, run available targets in your environment (for example, `ctest` or `make test` if configured), and review `docs/` for related guidance.

## Commit messages

Use clear, descriptive commit messages. Prefer this format:

```
<type>: <short summary>

- <bullet detail>
- <bullet detail>
```

Examples: `fix: stabilize Windows install`, `docs: rewrite README`.

## Code style

Follow the existing style in each file. Avoid unnecessary formatting changes.

## Code of Conduct

This project follows `CODE_OF_CONDUCT.md`. By participating, you agree to uphold it.

## License

By contributing, you agree that your contributions will be licensed under the terms in `LICENSE` and `NOTICE`.
