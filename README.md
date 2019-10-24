# black-mirror

Mirror of black package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For black: see https://github.com/psf/black


### Using black with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: https://github.com/louisguitton/black-mirror
        rev: ''  # Use the sha / tag you want to point at
        hooks:
        -   id: black
