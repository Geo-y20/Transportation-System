# Transportation System

This is a transportation system project that allows clients to book rides using available cars and drivers.

## Requirements
- Python 3.11.1 or later

## Usage

1. Clone the repository: git clone https://github.com/Geo-y20/Transportation-System.git
2. Navigate to the project directory: cd Transportation-System
3. Run the main script:python main.py
4. Choose one of the following options:

- 1: List all clients
- 2: List all drivers
- 3: List all cars
- 4: List customer transactions
- 5: List driver transactions
- 6: Book a ride
- 7: Display all rides
- 0: Exit

## Classes

The project consists of the following classes:

- `Location`: Represents a location with longitude and latitude coordinates.
- `Transaction`: Represents a transaction with a type, amount, and timestamp.
- `Wallet`: Represents a wallet with a balance and a list of transactions.
- `Person`: Represents a person with a name, address, social security number, hourly rate, wallet, and location.
- `Client`: Inherits from `Person` and represents a client with additional methods and attributes.
- `Driver`: Represents a driver with a name, address, social security number, hourly rate, and wallet.
- `Car`: Represents a car with a color, location, and driver.
- `Ride`: Represents a ride with a client, car, destination, and source.

## Contributing

Contributions to the Transportation System project are welcome. If you find any issues or want to add new features, please feel free to open an issue or submit a pull request.







