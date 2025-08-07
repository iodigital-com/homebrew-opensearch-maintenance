# OpenSearch Maintenance Homebrew Tap

Homebrew tap for OpenSearch maintenance releases

## Installation

Tap the formula repository:

    brew tap iodigital-com/opensearch-maintenance

Install the `opensearch@1` formula:

    brew install opensearch@1 --force

The `--force` option is needed to force installation of the deprecated `gradle@6` package.

Note that the `opensearch@1` formula has been deprecated upsream as of 06-05-2025; see the [OpenSearch maintenance policy for details](https://opensearch.org/releases/#maintenance-policy).

## Documentation

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).
