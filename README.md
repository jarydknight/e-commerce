
  # E-commerce

  [![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/)

  ## Table of Contents

  * [Description](#description)
  * [Technologies](#technologies)
  * [Installation](#installation)
  * [Usage](#usage)
  * [License](#license)
  * [Contributing](#contributing)
  * [Demo](#demo)
  * [Tests](#tests)
  * [Credits](#credits)
  * [Questions](#questions)

  ---

  ## Description

  The purpose of this project is to use the ORM Sequalize (NPM package) to complete a back end for an e-commerce application and execute CRUD operations on a database.

  ---

  ## Technologies

  * Node.js
  * Sequalize (NPM package)
  * MySQL2 (NPM package)
  * dotenv (NPM package)
  * Express


  ---

  ## Installation

  1. Clone the repository.
  2. Open terminal window in the root directory and run `npm init`.
  3. Create a `.env` file in the root directory and configure using the example below. **Replace DB_USER and DB_PW with your MySQL credentials**:
      ```
      DB_NAME = 'ecommerce_db'
      DB_USER = 'YOUR USERNAME'
      DB_PW = 'YOUR PASSWORD'
      ```
  4. Open the MySQL command line tool, run `USE ecommerce_db;` then run `db/schema.sql`. Close the MySQL command line tool.
  5. In the root directory run `npm run seed` to seed the database.

  ---

  ## Usage

  1. In the command line in the root directory run `npm start` to start the server and connect to the database.
  2. Access the API endpoints using the following routes:
      * `localhost:3001\categories`
          * GET all categories.
          * POST new category.
              ```
              {category_name: ""}
              ```
      * `localhost:3001\categories\:id`
          * GET one category by ID.
          * PUT (update) category by ID.
              ```
              {category_name: ""}
              ```
          * DELETE category by ID.
      * `localhost:3001\products`
          * GET all products.
          * POST new products.
              ```
              {product_name: "", price: "", stock: "", category_id: ""}
              ```
      * `localhost:3001\products\:id`
          * GET one product by ID.
          * PUT (update) product by ID.
              ```
              {product_name: "", price: "", stock: "", category_id: ""}
              ```
          * Delete product by ID.
      * `localhost:3001\tags`
          * GET all tags.
          * POST new tag.
              ```
              {tag_name: ""}
              ```
      * `localhost:3001\tags\:id`
          * GET one tag by ID.
          * PUT (update) tag by ID.
              ```
              {tag_name: ""}
              ```
          * DELETE tag by ID.

  ---

  ## License

    This is free and unencumbered software released into the public domain.
  
      Anyone is free to copy, modify, publish, use, compile, sell, or distribute this software, either in source code form or as a compiled binary, for any purpose, commercial or non-commercial, and by any means.
      
      In jurisdictions that recognize copyright laws, the author or authors of this software dedicate any and all copyright interest in the software to the public domain. We make this dedication for the benefit of the public at large and to the detriment of our heirs and successors. We intend this dedication to be an overt act of relinquishment in perpetuity of all present and future rights to this software under copyright law.
      
      THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

  ---

  ## Contributing

  To contribute to this project fork the repository, make your changes, then submit a pull request.

  ---

  ## Demo

  ---

  ## Tests

  There are currently no tests for this application.

  ---

  ## Credits

  Jaryd Knight :heart_on_fire:

  ---

  ## Questions

  If you have any questions please check out my Github page and/ or send me an email.

  Github: [jarydknight](https://github.com/jarydknight)
  
  Email: placeholder@gmail.com
  