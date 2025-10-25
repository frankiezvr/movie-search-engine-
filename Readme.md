Below is a sample README file structure that you can use for your project. This README includes instructions on setting up and running a Node.js API, an Angular website, setting up a PostgreSQL server, and restoring a database using DBeaver Community Edition. Remember to replace placeholder text with actual paths or values specific to your project as needed.

---

# Project Name

This project consists of three main parts: a Node.js API, an Angular website, and a PostgreSQL database. Follow the instructions below to set up and run each component.

## Prerequisites

- Node.js (https://nodejs.org/)
- Angular CLI (https://angular.io/cli)
- PostgreSQL (https://www.postgresql.org/download/)
- DBeaver Community Edition (https://dbeaver.io/download/)

## Setting Up the PostgreSQL Server

1. Install PostgreSQL on your machine following the instructions on the official website.
2. Open DBeaver and create a new PostgreSQL connection:
   - Host: `localhost`
   - Port: `5432` (default)
   - Username: `postgres` (default)
   - Password: Your chosen password during installation.
3. To restore the database, right-click on your PostgreSQL connection, select `Restore Database`.
4. Choose the `movies-movies-202402111534.sql` file located in the `database` folder of this project.
5. Follow the prompts to restore the database.

## Setting Up the Node API

1. Navigate to the `api` directory from the terminal.
2. Run `npm install` to install dependencies.
3. Start the API by running `npm start`.
4. The API will be available at `http://localhost:3000`.

## Setting Up the Angular Website

1. Navigate to the `website` directory from the terminal.
2. Run `npm install` to install dependencies.
3. Start the Angular development server by running `ng serve`.
4. Open a browser and navigate to `http://localhost:4200` to view the website.

## Additional Information

- For research purposes, all SQL scripts used in the project are available in the `database.sql` file located in the `database` folder.

- The datased that was used can be found at the url: https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset

## Troubleshooting

- Ensure all prerequisites are correctly installed before attempting to run the project components.
- Check the PostgreSQL server is running and accessible through DBeaver before attempting to restore the database.
- If you encounter any issues with the Node API or Angular website, ensure that the terminal is pointed to the correct directory (`API` or `website` respectively) and that all dependencies have been installed with `npm install`.

You can download the files from here:

https://drive.google.com/file/d/1oYzkCBWaltLhIT73rK0S_80nTvfI-eRR/view?usp=drive_link
