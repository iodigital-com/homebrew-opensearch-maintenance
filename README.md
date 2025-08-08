# OpenSearch Maintenance Homebrew Tap

Homebrew tap for OpenSearch maintenance releases

## Installation

Tap the formula repository:

    brew tap iodigital-com/opensearch-maintenance

Install the `opensearch@2` formula:

    brew install opensearch@2

Note that this repository also contains the `opensearch@1` formula, which has been deprecated upstream as of 06-05-2025; see the [OpenSearch maintenance policy for details](https://opensearch.org/releases/#maintenance-policy).
Although this formula should be avoided, it can still be installed as follows:

    brew install opensearch@1 --force

The `--force` option is needed to force installation of the deprecated `gradle@6` package.

## Documentation

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).
