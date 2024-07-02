

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/Tejas-Dhurgude/Work_india_apiround
   ```

2. Install dependencies:
   ```
   npm i express jsonwebtoken
4. Set up the MySQL database:
   - Create a database named `inshorts`
   - Update name of database and password in .env

5. Start the server:
   ```bash
   node app
   ```

## Routes

- POST /api/signup: Create a new user account
- POST /api/login: User login
- POST /api/shorts/create: Create a new news short
- GET /api/shorts: Get all news shorts

Test:
