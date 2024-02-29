# Omni Templates Repository

Welcome to the Omni templates repository. This repository serves as a central hub for various templates. Each submodule in this repository is a pointer to another template repository within the Omni org.

## Usage

### Updating Submodules

To update all submodules to the latest commit on their respective `main` branches, run:

```bash
git submodule update --remote
```

## Adding a New Template

To contribute a new template to this collection:

1. Fork the `templates` repository.
2. Clone your fork and create a new branch for your contribution.
3. Add your template as a submodule:

```bash
git submodule add -b main <URL to your template repository> <path to submodule>
```

4. Commit and push the changes to your fork.
5. Open a pull request against the original `templates` repository.

## License

Each template within this repository maintains its own licensing. Please check the individual repositories for their respective licenses.
