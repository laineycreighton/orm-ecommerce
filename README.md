# E-Commerce Application

## Table of Contents
- [Description](#description)
- [Learning Points](#learning-points)
- [Features](#features)
- [Technology Used](#technology-used)
- [Installation](#installation)
- [API Endpoints](#api-endpoints)
- [Deployment](#deployment)
- [Author](#author)
- [Contributing](#contributing)
- [License](#license)

## Description

This is the back end for an e-commerce website, built using Express.js and Sequelize to interact with a MySQL database. The project enables the management of products, categories, and tags through RESTful API endpoints. It allows users to perform CRUD operations (Create, Read, Update, Delete) on various resources, providing the foundational architecture for an e-commerce platform.

<br>

## Learning Points

- How to use flexbox.
- How to create a linked navigation menu.
- How to create forms.
- How to use HTML semantic elements.
- How to use class, id, element, and universal selectors in CSS.

<br>

## Features

- API routes for managing categories, products, and tags.
- Establishes relationships between products, categories, and tags using Sequelize associations.
- Utilizes environment variables to securely store database credentials.
- Sequelize ORM for database interactions and model definitions.

<br>

## Technology Used

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
<br>

![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
<br>

![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=Sequelize&logoColor=white)
<br>

![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
<br>

![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)
<br>

![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
<br>

![Heroku](https://img.shields.io/badge/heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white)
<br>

![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

<br>

## Installation

1. Clone the repository to your local machine.
2. Install dependencies using `npm install`.
3. Set up your database credentials in the `.env` file.
4. Run the database schema creation script in `db/schema.sql`.
5. Seed the database with sample data using `npm run seed`.
6. Start the server using `npm start`.

<br>

## API Endpoints

- **Categories:**
  - GET `/api/categories` - Retrieve all categories.
  - GET `/api/categories/:id` - Retrieve a single category by ID.
  - POST `/api/categories` - Create a new category.
  - PUT `/api/categories/:id` - Update a category by ID.
  - DELETE `/api/categories/:id` - Delete a category by ID.

- **Products:**
  - GET `/api/products` - Retrieve all products with associated category and tag data.
  - GET `/api/products/:id` - Retrieve a single product by ID with associated data.
  - POST `/api/products` - Create a new product with optional tags.
  - PUT `/api/products/:id` - Update a product by ID with optional tags.
  - DELETE `/api/products/:id` - Delete a product by ID.

- **Tags:**
  - GET `/api/tags` - Retrieve all tags with associated product data.
  - GET `/api/tags/:id` - Retrieve a single tag by ID with associated data.
  - POST `/api/tags` - Create a new tag.
  - PUT `/api/tags/:id` - Update a tag's name by ID.
  - DELETE `/api/tags/:id` - Delete a tag by ID.

  <br>

## Deployment

Website URL: [Lake Tahoe](https://laineycreighton.github.io/landing-page/)

[https://drive.google.com/file/d/11RDvqLfBvTYLvX-GZHfT0RUCq9jJ-ta7/view?usp=sharing](#) - A video demonstrating the functionality and usage of the e-commerce back end API.

<br>

## Author

### Lainey Creighton

_Currently a student in the UC Berkeley Full Stack Coding Bootcamp. Contact Below:_

<br>

![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)
<br>

[dev.lainey@gmail.com](dev.lainey@gmail.com)
<br>
<br>

![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)
<br>

[https://www.linkedin.com/in/lainey-creighton/](https://www.linkedin.com/in/lainey-creighton/)
<br>
<br>

![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
<br>

[https://github.com/laineycreighton](https://github.com/laineycreighton)

<br>

## Contributing

Thank you for your interest in contributing to the Lake Tahoe Landing Page project! While this project is primarily intended to showcase my HTML and CSS skills, contributions and suggestions are welcome.

<br>

### Reporting Issues

If you find any issues or have suggestions for improvements, please feel free to open an issue in the [issue tracker](link-to-issue-tracker). Provide as much detail as possible, including steps to reproduce the problem.

<br>

### Pull Requests

If you'd like to contribute code to this project, you can follow these general steps:

1. Fork the repository.
2. Create a new branch for your contribution: `git checkout -b feature/new-feature`.
3. Make your changes and commit them: `git commit -m 'Add new feature'`.
4. Push your changes to your fork: `git push origin feature/new-feature`.
5. Open a pull request against the `main` branch of this repository.

Please ensure that your code follows best practices and is well-documented. Also, make sure to keep your pull request focused and limited to a single feature or improvement.

<br>

### Code Style

While there are no strict guidelines for code style in this project, please try to maintain consistency with the existing codebase. Use meaningful variable names and add comments where necessary to explain complex logic.

<br>

### Code of Conduct

Please note that this project follows the [Contributor Covenant Code of Conduct](link-to-code-of-conduct). By participating, you are expected to uphold this code. Please report any unacceptable behavior.

Thank you for considering contributing to the Lake Tahoe Landing Page project! Your input is valued.

<br>

## License

N/A