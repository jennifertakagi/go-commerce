<!-- Inspired by https://github.com/jennifertakagi/go-commerce -->

<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/jennifertakagi/go-commerce">
    <img src="docs/logo.png" alt="Logo" width="100">
  </a>

  <h3 align="center">Go Commerce</h3>

  <p align="center">
      An API to control your e-commerce!
    <br />
    <a href="https://github.com/jennifertakagi/go-commerce"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/jennifertakagi/go-commerce/issues">Report Bug</a>
    ·
    <a href="https://github.com/jennifertakagi/go-commerce/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

An API to control your e-commerce.

Features:
* Create a customer (name and email)
* Create a product (name, price, quantity)
* Create a order (customer_id and products)
* Show a order by id



### Built With

* [TypeScript](https://www.typescriptlang.org/)
* [Node JS](https://nodejs.org/en/)
* [Express JS](https://expressjs.com/)
* [Docker](https://www.docker.com/)
* [Postgres](https://node-postgres.com/)
* [Typeorm](https://typeorm.io/#/)
* [Tsyringe](https://www.npmjs.com/package/tsyringe)



<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

* npm
  ```sh
  npm install npm@latest -g
  ```

* yarn
  ```sh
  npm install --global yarn
  ```

* [docker](https://docs.docker.com/get-docker/) 


### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/jennifertakagi/go-commerce.git
   ```
2. Install packages on **backend** folder
   ```sh
   yarn | npm install
   ```
3. Create a Postgress docker image with the following command and options:
   ```sh
  docker run --go-commerce foo -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres
   ```
4. Run database migrations
  ```sh
  yarn typeorm migration:run | npm run typeorm migration:run
  ```
5. Run the local environment on **backend**
  ```sh
  yarn dev:server | npm run dev:server
  ```



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/jennifertakagi/go-commerce/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Jennifer Takagi - [@jennitakagi](https://twitter.com/jennitakagi)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [Cors](https://www.npmjs.com/package/cors)
* [Reflect Metadata](https://www.npmjs.com/package/reflect-metadata)
* [Jest](https://jestjs.io/)
* [ESLint](https://eslint.org/)
* [Prettier](https://prettier.io/)



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/jennifertakagi/go-commerce.svg?style=for-the-badge
[contributors-url]: https://github.com/jennifertakagi/go-commerce/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/jennifertakagi/go-commerce.svg?style=for-the-badge
[forks-url]: https://github.com/jennifertakagi/go-commerce/network/members
[stars-shield]: https://img.shields.io/github/stars/jennifertakagi/go-commerce.svg?style=for-the-badge
[stars-url]: https://github.com/jennifertakagi/go-commerce/stargazers
[issues-shield]: https://img.shields.io/github/issues/jennifertakagi/go-commerce.svg?style=for-the-badge
[issues-url]: https://github.com/jennifertakagi/go-commerce/issues
[license-shield]: https://img.shields.io/github/license/jennifertakagi/go-commerce.svg?style=for-the-badge
[license-url]: https://github.com/jennifertakagi/go-commerce/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/jennifertakagi

