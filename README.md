<p align="left">
   <img src="docs/logo.png" width="150"/>
</p>

# Go Commerce

> An API to control your commerce! :)

[![Author](https://img.shields.io/badge/author-jennifertakagi-ff9000?style=flat-square)](https://github.com/jennifertakagi)
[![Languages](https://img.shields.io/github/languages/count/jennifertakagi/go-commerce?color=%23ff9000&style=flat-square)](#)
[![Stars](https://img.shields.io/github/stars/jennifertakagi/go-commerce?color=ff9000&style=flat-square)](https://github.com/jennifertakagi/go-commerce/stargazers)
[![Forks](https://img.shields.io/github/forks/jennifertakagi/go-commerce?color=%23ff9000&style=flat-square)](https://github.com/jennifertakagi/go-commerce/network/members)
[![Contributors](https://img.shields.io/github/contributors/jennifertakagi/go-commerce?color=ff9000&style=flat-square)](https://github.com/jennifertakagi/go-commerce/graphs/contributors)

---

# :pushpin: Table of Contents

* [Features](#rocket-features)
* [Installation](#construction_worker-installation)
* [Getting Started](#runner-getting-started)
* [FAQ](#postbox-faq)
* [Found a bug? Missing a specific feature?](#bug-issues)
* [Contributing](#tada-contributing)
* [License](#closed_book-license)

<br />

# :rocket: Features

* Create a customer (name and email)
* Create a product (name, price, quantity)
* Create a order (customer_id and products)
* Show a order by id

<br />

# :construction_worker: Installation

**You need to install [YARN](https://yarnpkg.com/) and [DOCKER](https://www.docker.com/), then in order to clone the project via HTTPS, run this command:**

```git clone https://github.com/jennifertakagi/go-commerce.git```

SSH URLs provide access to a Git repository via SSH, a secure protocol. If you have a SSH key registered in your Github account, clone the project using this command:

```git clone git@github.com:jennifertakagi/go-commerce.git```

<br />

# :runner: Getting Started

Run the following command in **backend** folder start the application in a development environment:

```docker run --go-commerce foo -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres```

```yarn typeorm migration:run```

```yarn dev:server```

<br />

# :postbox: Faq

**Question:** What are the technologies used in this project?

**Answer:** The technologies used in this project are [Docker](https://www.docker.com/) and [Node JS](https://nodejs.org/en/).

<br />

# :bug: Issues

Feel free to **file a new issue** with a respective title and description on the [Go Commerce](https://github.com/jennifertakagi/go-commerce/issues) repository. If you already found a solution to your problem, **i would love to review your pull request**! Have a look at our [contribution guidelines](https://github.com/jennifertakagi/go-commerce/blob/master/CONTRIBUTING.md) to find out about the coding standards.

<br />

# :tada: Contributing

Check out the [contributing](https://github.com/jennifertakagi/go-commerce/blob/master/CONTRIBUTING.md) page to see the best places to file issues, start discussions and begin contributing.

<br />

# :closed_book: License

Released in 2020.
This project is under the [MIT license](https://github.com/jennifertakagi/go-commerce/master/LICENSE).

