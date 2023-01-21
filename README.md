# mix-react-example
Example for Laravel-mix for React

[![GitHub license](https://img.shields.io/github/license/c0de4un/mix-react-example)](https://github.com/c0de4un/mix-react-example/blob/main/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/c0de4un/mix-react-example)](https://github.com/c0de4un/mix-react-example/stargazers)

## Requirements
### Hardware
* 2-Core CPU 2Ghz amd/x86
* 2 GB RAM
* 8 GB HDD
### Software
* PHP 8.1
* Node.js 16

## Installation
### API
1. Install `PHP` packages
```shell
    $php composer.phar install
```
2. Apply Migrations
```shell
    $php artisan migrate
```
3. Seed database
```shell
    $php artisan db:seed
```
### Web-Client
Install `npm` packages
```shell
    $npm install
```

## Development
### API
1. Disable `production` environment
2. Enable debug
3. Disable caching
### Web-CLient
Run development server
```shell
    $npm run dev
```

## Deployment
### API
1. Disable debug
2. Enable `production` environment
3. Cache configs
4. Cache routes
### Web-Client
Build for production
```shell
    $npm run prod
```

## Testing
### API
```shell
    $php artisan test
```