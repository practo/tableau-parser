# Contributing

## Getting Started

Fork the repository to your own account.

Clone the repository to a suitable location on your local machine.

```bash
git clone https://github.com/practo/tableau-parser.git
```

**Note:** This will clone the entire contents of the repository at the HEAD revision.

To update the project from within the project's folder you can run the following command:

```bash
git pull --rebase
```

### Virtual Environment

It is better to keep a project specific virtual environment to not mix package versions between different projects.

To create and activate a virtual environment use:

```bash
virtualenv venv
. venv/bin/activate
```

### Building

Install the project's dependencies.

```bash
pip install -r requirements.txt
pip install -r requirements-dev.txt
```

Install [pre-commit](http://pre-commit.com) hooks.

```bash
pre-commit install
```

### Commit Guidelines

Before committing pre-commit hooks will run to check for source standards.
If you want to run a check manually before committing use:

```bash
pre-commit run
```

Read [pre-commit](http://pre-commit.com) documentation to learn more about it.

### Testing

Install the project's dependencies and then run the project's tests.

## Feature Requests

If you have a suggestion for improving an existing feature, or would like to suggest a completely new feature, please file an issue with [GitHub repository](https://github.com/practo/tableau-parser/issues).

## Bug Reports

A project isn't always perfect, but we strive to always improve on that work. You may file bug reports on the [GitHub repository](https://github.com/practo/tableau-parser/issues) site.

## Pull Requests

Along with our desire to hear your feedback and suggestions, we are also interested in accepting direct assistance in the form of new code or documentation.

Please feel free to file merge requests against [GitHub repository](https://github.com/practo/tableau-parser/pulls).
