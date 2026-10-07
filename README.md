### FBR Digital Invoicing 

SowaanERP integration with FBR Digital Invoicing.

### Installation

You can install this app using the [bench](https://github.com/frappe/bench) CLI:

```bash
cd $PATH_TO_YOUR_BENCH
bench get-app $URL_OF_THIS_REPO --branch develop
bench install-app fbr_digital_invoicing
```

### Contributing

This app uses `pre-commit` for code formatting and linting. Please [install pre-commit](https://pre-commit.com/#installation) and enable it for this repository:

```bash
cd apps/fbr_digital_invoicing
pre-commit install
```

Pre-commit is configured to use the following tools for checking and formatting your code:

- ruff
- eslint
- prettier
- pyupgrade

### License

mit

### Provenance

Copied from upstream [https://github.com/sowaan/fbr_digital_invoicing](https://github.com/sowaan/fbr_digital_invoicing), branch `main`, at commit `3a11f33` (2026-07-27), on 2026-10-07.

One change on top of upstream: added `[tool.bench.frappe-dependencies]` (`frappe = ">=15.0.0,<16.0.0"`) to `pyproject.toml`, which Frappe Cloud requires.
