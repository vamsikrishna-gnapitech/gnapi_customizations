### Gnapi Customizations

Gnapi Customizations

### Installation

You can install this app using the [bench](https://github.com/frappe/bench) CLI:

```bash
cd /home/frappe/frappe-bench
bench get-app https://github.com/vamsikrishna-gnapitech/gnapi_customizations.git --branch main 
### If the above repository is not found, it will be located at https://github.com/gnapi-tech/gnapi_customizations.git
bench install-app gnapi_customizations
```

### Contributing

This app uses `pre-commit` for code formatting and linting. Please [install pre-commit](https://pre-commit.com/#installation) and enable it for this repository:

```bash
cd apps/gnapi_customizations
pre-commit install
```

Pre-commit is configured to use the following tools for checking and formatting your code:

- ruff
- eslint
- prettier
- pyupgrade

### License

mit
