# hello_worlder

This project follows command standards in [common-targets](https://github.com/flaviostutz/common-targets).

## Developer commands

```
make prepare
make build
make test
make lint
```

## Tools
- Makefile: scripts management
- pip: virtual environments management
- Mypy: code Type check
- RUFF: code formatting and linting
- pytest + coverage: test management
- pip-audit: dependencies vulnerability checks
- pip-tools: dependencies lock file generation (contrainsts.txt)

All the tools are working correctly with Makefile scripts to be used locally or in CI pipelines and also with VSCode plugins (check .vscode/extensions.json for details) to make the findings more visual.

## References

- https://github.com/pypa/sampleproject
- https://www.dataquest.io/blog/unit-tests-python/
- Test: https://medium.com/@keployio/mastering-python-test-coverage-tools-tips-and-best-practices-11daf699d79b
- https://requests-mock.readthedocs.io/en/latest/mocker.html
