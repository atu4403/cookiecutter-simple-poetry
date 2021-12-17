# cookiecutter-simple-poetry

a template of cookiecutter

[Cookiecutter — cookiecutter 1.7.2 documentation](https://cookiecutter.readthedocs.io/en/1.7.2/README.html)

## useit

```bash
cookiecutter https://github.com/atu4403/cookiecutter-simple-poetry
```

Please make a file `~/.cookiecutterrc`

```bash
default_context:
  full_name: 'your name'
  email: 'yourmail@example.com'
  github_username: 'your github username'
abbreviations:
  poetry: https://github.com/atu4403/cookiecutter-simple-poetry
```

You can use abbreviation

```bash
cookiecutter poetry
```

Created Files

```bash
.
├── .github
│   └── workflows
│       ├── deploy_doc.yml
│       └── test.yml
├── src
│   └── python_boilerplate
│       └── __init__.py
├── tests
│   ├── __init__.py
│   └── test_python_boilerplate.py
├── .gitignore
├── LICENSE
├── README.md
├── pyproject.toml
└── pytest.ini
```
