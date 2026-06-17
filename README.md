# Currency Converter App

A small PHP currency conversion application with a dedicated request client and conversion model.

## Learning Goal

Practice separating API communication from domain logic in a small command-line PHP application.

## Features

- Fetches exchange data through a client class.
- Encapsulates conversion behavior in a model.
- Keeps the CLI entry point separate from application classes.

## Tech Stack

- PHP
- Composer
- API client pattern

## Run

```bash
cd currency-converter
composer install
php main.php
```

## Project Structure

- `currency-converter/main.php` - entry point
- `currency-converter/App/ClientRequest.php` - external request client
- `currency-converter/App/App.php` - application flow
- `currency-converter/App/Models/Convert.php` - conversion model

## License

MIT License. See [LICENSE](./LICENSE).
