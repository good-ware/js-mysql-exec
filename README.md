# @goodware/mysql: A mysql2-based connection helper

Better documentation is coming

# Links

- [npm](https://www.npmjs.com/package/@goodware/mysql)
- [git](https://github.com/good-ware/js-mysql)
- [API](https://good-ware.github.io/js-mysql/)

# Requirements

ES 2017

# Installation

`npm i --save @goodware/mysql`

# Features

- Creates database connections via mysql2-promise, optionally from a pool, with exponential backoff retry
- Handles AWS RDS passwordless IAM connections
- Manages database transactions by wrapping begin/end around a function invocation
