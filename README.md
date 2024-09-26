# Book Management System

Book Management System is a full stack monolith web application build with Node.js, Express.js and MongoDB (and Bootstrap).

This app is build for practice purpose and available publicly, where user can view all books, popular books, recently added books, filter book by genres, and search book by title.

Some features requires user authentication to be available, such as accessing the book cart, borrowing book(s), view currently borrowed book(s), view their profile, and their borrow history.

User authenticated as admin can access the admin dashboard where admin can perform CRUD for books, view borrow history of all user, and view all user public information.


## Build With
- [Node.js](https://nodejs.org/en/)
- [Express.js](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Bootstrap 5](https://getbootstrap.com/)

# Getting Started

## Prerequisites
These are the requirements to run this project.
- [Node.js v16+](https://nodejs.org/en/)
- [npm v8+](https://www.npmjs.com/)




## Docs & Community

  * [Website and Documentation](http://expressjs.com/) - [[website repo](https://github.com/expressjs/expressjs.com)]
  * [#express](https://webchat.freenode.net/?channels=express) on freenode IRC
  * [GitHub Organization](https://github.com/expressjs) for Official Middleware & Modules
  * Visit the [Wiki](https://github.com/expressjs/express/wiki)
  * [Google Group](https://groups.google.com/group/express-js) for discussion
  * [Gitter](https://gitter.im/expressjs/express) for support and discussion

**PROTIP** Be sure to read [Migrating from 3.x to 4.x](https://github.com/expressjs/express/wiki/Migrating-from-3.x-to-4.x) as well as [New features in 4.x](https://github.com/expressjs/express/wiki/New-features-in-4.x).

### Security Issues

If you discover a security vulnerability in Express, please see [Security Policies and Procedures](Security.md).

## Quick Start

  The quickest way to get started with express is to utilize the executable [`express(1)`](https://github.com/expressjs/generator) to generate an application as shown below:

  Install the executable. The executable's major version will match Express's:

```bash
$ npm install -g express-generator@4
```

  Create the app:

```bash
$ express /tmp/foo && cd /tmp/foo
```

  Install dependencies:

```bash
$ npm install
```

  Start the server:

```bash
$ npm start
```

  View the website at: http://localhost:3000


## Examples

  To view the examples, clone the Express repo and install the dependencies:

```bash
$ git clone git://github.com/expressjs/express.git --depth 1
$ cd express
$ npm install
```

  Then run whichever example you want:

```bash
$ node examples/content-negotiation
```

## Tests

  To run the test suite, first install the dependencies, then run `npm test`:

```bash
$ npm install
$ npm test
```
