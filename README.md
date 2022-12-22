# Nestor AI

*A grocery shopping list manager developped with help from chatGPT*

[![Maintainability](https://api.codeclimate.com/v1/badges/80826c88f964169af11f/maintainability)](https://codeclimate.com/github/Lionel-D/nestor-ai/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/80826c88f964169af11f/test_coverage)](https://codeclimate.com/github/Lionel-D/nestor-ai/test_coverage)

---

### Requirements

- **[PHP](https://www.php.net/)** `8.1`
- **[MySQL](https://www.mysql.com/)** `8.0`
- **[Composer](https://getcomposer.org/)** `2.3`
- **[Yarn](https://yarnpkg.com)** `3.3`
- **[Symfony client](https://symfony.com/download)** `5.4`

---

### Installation

- clone the repository `https://github.com/Lionel-D/nestor-ai.git`
- create your `.env.local` based on `.env` and set values for your local environment.
- `composer install` to get the framework dependencies.
- `php bin/console doctrine:database:create` to create database.
- `yarn install` to get the assets pipeline dependencies.

---

### Local environment

- `symfony server:start` to launch local server.

---

### Tests

- `php bin/phpunit` to execute tests.
