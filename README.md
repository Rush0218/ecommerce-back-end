# Back-End eCommerce

<p>
    <img src="https://img.shields.io/github/repo-size/rush0218/ecommerce-back-end" />
    <img src="https://img.shields.io/github/languages/top/rush0218/ecommerce-back-end"  />
    <img src="https://img.shields.io/github/last-commit/rush0218/ecommerce-back-end" />
</p>


## Description

Built back-end of an ecommerce site, to organize and store product data. 

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)


## Installation 

- `git clone` this repository locally. 
- Run `npm init --y` to install necessary node dependencies. 
- Run `npm i mysql2` to install MySQL2 to connect to database. 
- Run `npm i express` 
- Run `npm i sequelize` to connect your Express.js API to your MySQL database.
- Run `npm i dotenv` to use environment variables to store sensitive data.

## Usage 

When the application is installed, open the MySQL shell and input `source db/schema.sql` then close shell. In the terminal input `npm run seed` (be sure to create a seed script in package.json) followed by `npm start` or `node server.js` to initiate application. Open Insomnia core to GET, POST, PUT, and DELETE data through different routes. 

## Demo

![Alt text](assets/demo/ecommerce-backend.gif)

## License

![Badge](https://img.shields.io/badge/license-MIT-green). 

## Contributing

Made with ❤️ by [Tre'](https://github.com/Rush0218) 
