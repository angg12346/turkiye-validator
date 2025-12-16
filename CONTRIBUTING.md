# Contributing to Turkiye Validator

First off, thanks for taking the time to contribute! 🎉

The following is a set of guidelines for contributing to `laravingo/turkiye-validator`. These are mostly guidelines, not rules. Use your best judgment and feel free to propose changes to this document in a pull request.

## Getting Started

1.  **Fork** the repository on GitHub.
2.  **Clone** your fork locally:
    ```bash
    git clone https://github.com/YOUR_USERNAME/turkiye-validator.git
    cd turkiye-validator
    ```
3.  **Install dependencies**:
    ```bash
    composer install
    ```

## Development

### Testing

We use [Pest PHP](https://pestphp.com) for our testing suite. Please make sure all tests pass before submitting a Pull Request.

```bash
composer test
```

### Code Style

We follow the **PSR-12** coding standard and use [Laravel Pint](https://laravel.com/docs/pint) to enforce it.

Check your code style:
```bash
./vendor/bin/pint --test
```

Fix code style automatically:
```bash
./vendor/bin/pint
```

## Pull Requests

1.  Ensure your code is well-tested (add new tests for new features).
2.  Ensure your code passes the style checks.
3.  Update the `README.md` if you are adding new features.
4.  Submit your PR!
