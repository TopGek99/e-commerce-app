# E-Commerce App

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## Description

The purpose of this project was to modify the backend of a generic e-commerce application, to get it to interact with a mysql database using the sequelize and mysql2 npm packages. The main goal was to configure it so that the products in the database had a one to many relationship with the category table, and products and tags had a many to many relationship through the productTags table.
  
## Table of Contents
  
- [Installation](#Installation)
- [Usage](#Usage)
- [License](#License)
- [Contributing](#Contributing)
- [Tests](#Tests)
- [Questions](#Questions)
  
## Installation

The installation of this project is as simple as having the files in this repository, and ensuring all the dependencies are installed by running the command ```npm i``` after creating your package.json either manually or by running ```npm init -y```
  
## Usage

The program can be run by typing either ```node index.js``` or ```npm start``` in the command line. [Walkthrough Video](https://drive.google.com/file/d/1f_3KC-II0xyEhdw84WN14n2fedtQ6adY/view)
  
## License
  
This project is licensed under [MIT](https://opensource.org/licenses/MIT)
  
## Contributing

Any contribution is welcome.
  
## Tests

ensuring the 'ecommerce_db' database is created either by the mysql workbench or shell, then seeding it with the ```npm run seed``` command. After this it is as simple as starting the server and creating the various requests using Insomnia or a simlar API client.
  
## Questions
  
Any further questions can be directed to me via my [GitHub](https://github.com/TopGek99/), or [email](arowe890@gmail.com) if it is a more pressing matter.
