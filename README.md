# Table of contents
- [About](#-about)
- [Main libs and techs used](#-main-libs-and-techs-used)
- [Downloading and setting up the project](#-downloading-and-setting-up-the-project)
- [License & copyright](#license--copyright)

## 📄 About

This project was developed during Rocketseat's GoStack bootcamp challenge. It is a NodeJS server that uses a postgreSQL databank to store customer, products and orders simulating a small e-commerce.

---

## 👨‍💻 Main libs and techs used

The project was developed using the following techs:

- [NodeJS](https://nodejs.org/en/)
- [uuidv4](https://www.npmjs.com/package/uuidv4)
- [insomnia](https://insomnia.rest/)
- [Docker](https://www.docker.com/)
- [PostgreSQL](https://www.postgresql.org/)
- [DBeaver](https://dbeaver.io/)
- [TypeORM](https://typeorm.io/#/)

---

## 🔧 Downloading and setting up the project

Simply clone this template or download it to your device and run the command **yarn** on your terminal to install all required dependencies. <br/>
To make sure erything is running properly, run **yarn test**. <br/>
To run the server, run the command **yarn dev:server**. </br>
Make sure the postgreSQL databank is running. It was tested during development using a Docker container.</br>
Make sure a database named `gostack_desafio09_tests` is created before running the tests. The database can be created using DBeaver. </br>
TypeORM was used to manage the migration of the tables and settings of the databank. The `ormconfig.json` file configures many of the databank settings, such as connection and the directory where the migrations will be located.  </br>
DBeaver was also used to keep track of what was kept stored in the Databank. </br>
To test the routes used by the API, I recommend using the [insomnia](https://insomnia.rest/) app.

---

## License & copyright

Developed by Pedro Igor C. de Oliveira.

Licensed under the [MIT License](LICENSE).
