# To-do List Application

## Overview
This To-do List application is a simple, yet effective tool for managing your daily tasks. It allows users to add, view, and delete to-do items. This project is built using Node.js for the backend, React for the frontend, and PostgreSQL for the database.

## Features
- Add new to-do items.
- View a list of all to-do items.
- Delete to-do items.

## Getting Started

### Prerequisites
- Node.js
- npm (Node Package Manager)
- PostgreSQL
- Postbird or any PostgreSQL GUI (optional, for database management)

### Installation

#### Clone the Repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

#### Set Up the Backend
# Navigate to the backend directory
cd path/to/backend

# Install dependencies
npm install

# Start the server
npm start

#### Set Up the Frontend
# Navigate to the frontend directory
cd path/to/frontend

# Install dependencies
npm install

# Start the React development server
npm start


#### Environment Configuration
# Create a.env file in the root directory with the following content:
DB_USER=yourPostgresUsername
DB_HOST=localhost
DB_DATABASE=todo
DB_PASSWORD=yourPostgresPassword
DB_PORT=5432


#### Database Setup
# Create a PostgreSQL database named `todo`
# Create a table in the `todo` database with the required schema.

#### Usage
# Once the servers are running, the applicaiton is accessed at http://localhost:3000 for the frontend, and the backend will be running on http://localhost:8000.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

MIT License