# Secret Whisperer

Secret Whisperer is a web application that allows users to share and manage their secrets. Users can log in using either traditional username and password or Google account authentication.

## Features

- Users can register and log in using either a username/password or Google account.
- The system supports basic user registration, login, logout, and secret submission functionalities.

## Tech Stack

- **Frontend**: Uses EJS templating engine to render dynamic content.
- **Backend**: Built with Node.js and Express.js to serve web requests.
- **Database**: PostgreSQL for storing user data and secrets.
- **Authentication**: Passport.js for local username/password authentication and Google OAuth2 authentication.
- **Security**: Uses bcrypt for password hashing to ensure user data security.

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Yunshan-CAI/Secret-Whisper.git
   cd Secret-Whisper
   
2. **Clone the Repository**
Ensure you have Node.js and npm installed. Then run the following command to install project dependencies:
   ```bash
   npm install

3. **Configure Environment Variables**
Create a .env file in the root directory of the project and add the following content:
   ```bash
   SESSION_SECRET=your_session_secret
   PG_USER=your_postgres_user
   PG_HOST=your_postgres_host
   PG_DATABASE=your_postgres_database
   PG_PASSWORD=your_postgres_password
   PG_PORT=your_postgres_port
   GOOGLE_CLIENT_ID=your_google_client_id
   GOOGLE_CLIENT_SECRET=your_google_client_secret

Note: Ensure the .env file is added to .gitignore to prevent sensitive information from being pushed to version control.

4. **Run the Project**
   ```bash
   npm start
   
By default, the project will run on http://localhost:3000.



   
