
# Zerodha

A fully functional clone of Zerodha, India's largest stock brokerage platform. This project replicates the core features of Zerodha's trading interface, offering an intuitive experience for users to simulate stock trading, view real-time market data, and manage their portfolio.


## Features

- **Market Data**: View simulated stock prices and market trends.
- **Simulated Trading**: Users can buy and sell stocks in a simulated environment.
- **Portfolio Management**: Track stock purchases, sales, and portfolio performance.
- **User Authentication**: Secure login and registration system to manage user sessions.
- **Responsive UI**: Seamless experience across desktop, tablet, and mobile devices, closely mirroring Zerodha’s design.
## Tech Stack

- **Frontend**: React, Bootstrap, CSS for responsive and dynamic user interfaces.
- **Backend**: Node.js, Express for robust server-side logic and API handling.
- **Database**: MongoDB for managing user data and trade history.
## API Endpoints

### 1. Get All Holdings
- **Endpoint**: `/allHoldings`
- **Method**: `GET`
- **Description**: Retrieves all holdings from the database.

### 2. Get All Positions
- **Endpoint**: `/allPositions`
- **Method**: `GET`
- **Description**: Retrieves all positions from the database.

### 3. Create New Order
- **Endpoint**: `/newOrder`
- **Method**: `POST`
- **Description**: Creates a new order and saves it to the database.
- **Request Body**:
  - `name` (String): Name of the stock.
  - `qty` (Number): Quantity of the stock.
  - `price` (Number): Price of the stock.
  - `mode` (String): Mode of the order (e.g., Buy/Sell).
## Run Locally

Clone the project

```bash
  git clone https://github.com/Geetansh431/Zerodha
```
Go to the backend directory

```bash
  cd backend
```

Install dependencies

```bash
  npm install
```

create **.env file** 

Start the server

```bash
  npm run start
```

Go to the frontend and dashboard directory using Other Terminal

```bash
  cd ../
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```
## Enviroment Variables

MONGO_URL = YOUR_MONGO_URL
## Contributing to Zerodha 🤝

We welcome and appreciate contributions from the community to enhance and improve the Zerodha project. Whether you're a developer, designer, tester, or someone with valuable feedback, your input is invaluable to us.

## Thank You! ❤️

Thank you for considering contributing to the Zerodha project. Your efforts help make this project better for everyone. If you have any questions or need assistance, feel free to reach out through the issue tracker or discussions. Happy coding! 🤩
