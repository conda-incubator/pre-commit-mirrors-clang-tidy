# clang-tidy pre-commit hook

pre-commit hook of clang-tidy with conda as a `language` / package manager.

For pre-commit: see [here](https://github.com/pre-commit/pre-commit)

For clang-tidy: see [here](https://clang.llvm.org/extra/clang-tidy/)

## Using clang-tidy with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/quantco/pre-commit-mirrors-clang-tidy
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: clang-tidy-conda
```
