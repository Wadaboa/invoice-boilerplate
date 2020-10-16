# Invoice boilerplate

Simple automated LaTeX invoicing system for freelancers.

To see the standard `README`, default configurations and requirements/dependencies, visit the [`invoice-boilerplate` official repository](https://github.com/mrzool/invoice-boilerplate).

## Execution

To produce a `PDF` output, you need `pandoc` and `XeLaTeX` installed on your system. To edit the standard template, you need to create a `.details.yml` file, starting from the given `details.yml`.\
Then, when you are satisfied with the contents, you need to execute:

```bash
make clean
make
```

This will produce an `output.pdf` file in the root folder of the repository, which will not be committed for privacy/security purposes.

## My settings

- **`net-prices`**: Set to `true` when prices are represented as net prices. Comment it out to work with gross prices.
- **`invoice-nr`**: Represents the invoice number instead of the default invoice date.
- **`invoice-date`**: Represents the standard invoice date.
