# TshirtandCo. - Custom T-shirt Design Platform

## Overview

TshirtandCo is a dynamic web application built on the MERN (MongoDB, Express.js, React.js, Node.js) stack. It allows users to design and customize their own T-shirts, offering both manual design options and AI-assisted creation through prompts.

## Features

1. **Custom Design Interface**: Intuitive UI for users to manually design their T-shirts, selecting colors.
2. **AI Design Assistance**: Innovative AI integration enables users to generate designs by providing prompts, making the process quick and creative.
3. **Design History**: Saved design history for users to revisit, edit, and reorder previous designs.

## Tech Stack

- **Frontend**: React.js for a responsive and interactive design interface.
- **Backend**: Node.js and Express.js for server-side logic.
- **Database**: MongoDB for efficient storage of user data and design history.
- **AI Integration**: Used GPT 3.5 Model API.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/TshirtandCo.git

   ```

2. Navigate to the project directory:

```bash
cd TshirtandCo
 ```

3. Install dependencies for both frontend and backend:
```bash
cd client && npm install
cd server && npm install
 ```

4. Set up MongoDB and configure the connection string in the server/.env file.

5. Start the backend:
```bash
cd server
node index.js
 ```

6. Start the frontend:
```bash
cd client
npm run dev
 ```

Access the application at http://localhost:3000.
Contributions are welcome!
