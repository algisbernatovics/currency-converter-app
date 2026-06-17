# Currency Converter App

A small PHP currency conversion application with a dedicated request client and conversion model.

## Overview

A small PHP currency conversion application with a dedicated request client and conversion model.

## Features

- Fetches exchange data through a client class.
- Encapsulates conversion behavior in a model.
- Keeps the CLI entry point separate from application classes.

## Tech Stack

- PHP
- Composer
- API client pattern

## Project Structure

- `currency-converter/main.php` - entry point
- `currency-converter/App/ClientRequest.php` - external request client
- `currency-converter/App/Models/Convert.php` - conversion model

## Getting Started

From the project folder, install dependencies and run:

```bash
cd currency-converter
composer install
php main.php
```

## Portfolio Notes

- Demonstrates a small API-backed PHP application structure.
- Good example of separating request and domain logic.

## Status

Portfolio-ready PHP exercise.
