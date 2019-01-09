# Europeana Redirecter

*DEPRECATED:* this application is no longer maintained nor used.

A simple Rack application to redirect all HTTP requests to another location.

## License

Licensed under the EUPL V.1.1.

For full details, see [LICENSE.md](LICENSE.md).

## Requirements

* Ruby 2.2.2

## Installation

`bundle install`

## Usage

1. Set the redirect destination in the environment variable
  `REDIRECTER_LOCATION`.
2. Run Puma from the [Procfile](Procfile)

### Development environments

1. Set environment variables in `.env`
2. Run Puma with foreman: `foreman start`
