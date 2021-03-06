# <span style="color:skyblue">**E Commerce Back End**</span>

## <span style="color:violet">Table of Contents</span>

1. [Description](#Description)
2. [Stack](#Stack)
3. [Video Tutorial](#Video-Tutorial)
4. [Usage](#Usage)
5. [Credits](#Credits)
6. [License](#License)

## <span style="color:violet">Description</span>

> Welcome to E Commerce Back End. This app uses Node JS, Sequelize, MySQL and Thunder Client to connect with a shop database in which you can SEE, CREATE, UPDATE and DELETE any item. Through requests in Thunder Client you can manipulate the following: Categories, Products and Tags.

## <span style="color:violet">Stack</span>

<span style="color:skyblue">**1 - JavaScript**</span>

<span style="color:skyblue">**2 - MySQL**</span> [(link)](https://www.mysql.com/)

<span style="color:skyblue">**3 - Node JS**</span> [(link)](https://nodejs.org/en/)

<span style="color:skyblue">**4 - Sequelize**</span> [(link)](https://sequelize.org/)

<span style="color:skyblue">**5 - Thunder Client**</span> [(link)](https://www.thunderclient.com/)

## <span style="color:violet">Video Tutorial</span>

Use this `link` to access a video tutorial: [Adrian Strozzi - E Commerce Back End](https://youtu.be/fAaJUzQ1g14)

## <span style="color:violet">Usage</span>

1 - You can `clone` or `download` this repo as a ZIP file:

```sh
git clone https://github.com/adrianstrozzi/Tec13ECommerceBackEnd.git
```

2 - Once you have downloaded the App use the following command in your terminal to `install the required dependencies`:

```sh
npm install
```

3 - Modify the `.env` file in the root folder of the project so that it includes the following:

```sh
DB_USER=root
DB_PW=yourSQLpassword
DB_NAME=ecommerce_db
```

4 - Open `MySQL` and use the following code to create the required database (this is included in the `schema.sql` file in the `db folder`):

```sh
-- DROP DATABASE
DROP DATABASE IF EXISTS ecommerce_db;

-- CREATE DATABASE
CREATE DATABASE ecommerce_db;
```

5 - Once you create the Database run the following command in your terminal to `seed` the data (script included in `package.json` file):

```sh
npm run seed
```

6 - Make sure you install [Thunder Client](https://www.thunderclient.com/) as an extension in VS Code as you will be using it to send the requests to manipulate your database.

7 - Visit the [Video Tutorial](https://youtu.be/fAaJUzQ1g14) for a detailed guide on how to use the App.

## <span style="color:violet">Credits</span>

**Adrian Strozzi:** [https://github.com/adrianstrozzi](https://github.com/adrianstrozzi)

## <span style="color:violet">License</span>

**?? 2022 Adrian Strozzi**:zap:
