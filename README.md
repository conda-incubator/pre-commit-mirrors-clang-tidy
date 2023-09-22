clang-tidy(-conda) mirror
===================

Mirror of clang-tidy for pre-commit with conda as a language.

* For pre-commit: see https://github.com/pre-commit/pre-commit
* For clang-tidy: see https://clang.llvm.org/extra/clang-tidy/

### Using clang-tidy with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/Quantco/pre-commit-mirrors-clang-tidy
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: clang-tidy-conda
```

