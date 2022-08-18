# Feature Flags in PHP sample
A companion repo for "How to implement feature flagging in PHP"

## How it works

This sample PHP app which uses the Laravel framework and Vue.js on the frontend. It contains a book list component that is shown to users upon receiving an array of books returned from the backend. In this way, we can control this feature from our PHP code with the help feature flagging.

Here's what it looks like:

<!-- TODO: Add snapshot here -->

## Software requirements
- Composer version 2 - a tool for managing dependencies in PHP
- Node version 16+
- NPM version 8+ - a package manager for setting up and building the frontend
- PHP

## How to run this app

**1.** Clone the this repository.

**2.** Run the following command to install the PHP's dependencies.

```sh
composer install
```

**3.** Compile the frontend with NPM using the following command.

```sh
npm run dev
```

**4.** Start the PHP server with this command:

```sh
php artisan serve
```

You should now be able to see the app by visiting [http://127.0.0.1:8000/](http://127.0.0.1:8000/).

## References

In addition to PHP, Other frameworks and languages are also supported. Check out the full list of supported SDKs [here](https://configcat.com/docs/sdk-reference/overview/).

Stay tuned and in the loop with ConfigCat on [Twitter](https://twitter.com/configcat), [Facebook](https://www.facebook.com/configcat), [LinkedIn](https://www.linkedin.com/company/configcat/), and [GitHub](https://github.com/configcat).