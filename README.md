# Python Ride-Sharing System

This is a Python ride-sharing system implementation that allows clients to book rides with drivers using cars.
## Requirements

- Python 3.11.1 or later
## Usage

- Clone the repository: git clone https://github.com/Geo-y20/Transportation-System.git
- Run the main script: python transportation.py


## Classes

### `Location`

- Represents a geographic location with longitude and latitude coordinates.
- Provides methods to get and set latitude and longitude values.
- Calculates the distance between two locations using the Euclidean formula.

### `Transaction`

- Represents a financial transaction with a type, amount, and timestamp.
- Provides methods to get and set transaction details.

### `Wallet`

- Represents a wallet for a user, maintaining a balance and a list of transactions.
- Provides methods for depositing, withdrawing, and transferring funds.
- Allows adding transactions and printing the transaction history.

### `Person`

- Base class representing a person with a name, address, social security number, rate, wallet, and location.

### `Client`

- Represents a client using the ride-sharing system.
- Inherits from the `Person` class and includes additional methods and attributes specific to clients.

### `Driver`

- Represents a driver available in the ride-sharing system.
- Inherits from the `Person` class and includes additional methods and attributes specific to drivers.

### `Car`

- Represents a car used for rides in the ride-sharing system.
- Holds information about the car's color, location, and driver.
- Provides methods to get and set car details and calculate the distance between the car and a client.

### `Ride`

- Represents a ride booking between a client and a car/driver.
- Stores information about the client, car, source and destination locations.
- Calculates the distance and fare for the ride.

## Usage

The code includes a simple command-line interface (CLI) for interacting with the ride-sharing system. The available options are:

1. List all clients
2. List all drivers
3. List all cars
4. List customer transactions
5. List driver transactions
6. Book a ride
7. Display all rides
0. Exit

Please note that this implementation is a basic demonstration and may require further enhancements for a real-world scenario.

---

