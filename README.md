# BookSearchEngine – RESTful API with Express Server

## Description

This Google Books API search engine built with a RESTful API, The app was built using the MERN stack, with a React front end, MongoDB database, and Node.js/Express.js server and API. It's set up to allow users to SignUp/Login and save book searches to the backend and also Delete the Book doent need anymore. 

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Badges](#badges)
- [Features](#features)
- [How to Contribute](#how-to-contribute)
- [Tests](#tests)

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/lunahoushmand16/BookSearchEngine---RESTful-API.git
   ```
2. Navigate to the project folder:
   ```sh
   cd BookSearchEngine---RESTful-API 
   ```
3. Install dependencies:
    ```sh
   npm install
   ```
4. Build the project:
   ```sh
   npm run build
   ```
5. Start the backend server:
   ```sh
   npm run watch
   ```
6. Start the frontend client:
   ```sh
   cd client
   npm run dev
   ```

## Usage

- Open your browser and navigate to: http://localhost:3000

- Sign up for a new account, or log in if you already have one.

- Search for books, save favorites, and delete saved books anytime.

### Screenshots:

![SignUp page](./Assets/Sign-in%20page.png)
![Login page](./Assets/login%20page.png)
![Look for the save books/Delete](./Assets/Search%20for%20Book.png)

## Credits

- Created by **[Luna Houshmans](https://github.com/lunahoushmand16)**
- Built with: 
  - **[Express.js](https://expressjs.com/)**
  - **[TypeScript](https://www.typescriptlang.org/)**
  - **[Mongoose](https://mongoosejs.com/)**
  - **[MongoDB Compass](https://www.mongodb.com/products/tools/compass)**
  - **[React.js](https://react.dev/)**
  - **[Vitejs](https://vite.dev/)**

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

## Badges

![GitHub repo size](https://img.shields.io/github/repo-size/lunahoushmand16/BookSearchEngine---RESTful-API)
![GitHub contributors](https://img.shields.io/github/contributors/lunahoushmand16/BookSearchEngine---RESTful-API)
![GitHub stars](https://img.shields.io/github/stars/lunahoushmand16/BookSearchEngine---RESTful-API?style=social)

## Features

- Full RESTful API for book searching

- Authentication with secure JWTs

- Create users with unique username and email

- Search for your favorite books using Google Books API

- Save and remove books from your profile

- Schema validation and clean error handling

- Modular TypeScript backend structure

- Timestamped saved data (createdAt)

## How to Contribute

1. Fork the repository
2. Create a new branch: `git checkout -b feature-name`
3. Make changes and commit: `git commit -m 'Add feature X'`
4. Push changes: `git push origin feature-name`
5. Open a pull request

## Tests
This project was manually tested through the following steps:

✅ User Signup with a new username, email, and password

✅ User Login with correct credentials

✅ Search books using the Google Books API

✅ Save books to the user’s account

✅ View and delete saved books from the account

✅ JWT authentication verified for secure routes

✅ API route error handling tested (invalid login, bad requests)


