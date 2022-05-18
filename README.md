
# HanaKoi Online Shop
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description
This is a backend for an e-commerce website, HanaKoi Online Shop. It can create database and store product information to manage them!<br/>
You can create, get, update, and remove items in Category, Product, and Tag tables.<br/>
Click [here](https://drive.google.com/file/d/1hiFyOT_O5SmVn3YN9VnJ74-W9TYZ-LR-/view) for the demonstration video.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Questions](#questions)

## Installation
1. Install node and MySQL
2. Install npm packages
   ```cd
   npm i
   ```

## Usage
1. Create `.env` file.
    - Rename `.env.EXAMPLE` file to `.env`.
    - Enter your MySQL username and password in the file.
2. Create the database in your local server in MySQL shell.
    ```
    source ./db/schema.sql
    ```
3. Seed the sample data and Start the application. (Replace sample data in the `seeds` folder to your data if necessary)
    ```cd
    npm run seed
    npm start
    ```
4. GET/POST/PUT/DELETE routes in Insomnia using following url:
    [Default Local Server] http://localhost:3001
      - Category<br/>
        [GET all/POST] /api/categories<br/>
        [GET one/PUT/DEL] /api/categories/:id<br/>
        ![alt text](./assets/images/Sample-01_GET-categories.png)
        ![alt text](./assets/images/Sample-02_POST-categories.png)
      - Tag<br/>
        [GET all/POST] /api/tags<br/>
        [GET one/PUT/DEL] /api/tags/:id<br/>
        ![alt text](./assets/images/Sample-03_GET-tags.png)
        ![alt text](./assets/images/Sample-04_POST-tags.png)
      - Product<br/>
        [GET all/POST] /api/products<br/>
        [GET one/PUT/DEL] /api/products/:id<br/>
        ![alt text](./assets/images/Sample-05_GET-products.png)
        ![alt text](./assets/images/Sample-06_POST-products.png)
5. Press 'Ctrl' + 'c' keys to quit.

## License
Licensed under the [MIT License](https://opensource.org/licenses/MIT).
      

## Questions
- GitHub Profile: https://github.com/YuriI92
- If you have any additional questions, please feel free to contact me by email.
  E-mail Address: <yurichikawa1992@gmail.com>
      
  