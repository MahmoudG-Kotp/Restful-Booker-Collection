# Restful-Booker Collection

## Description
This project is a Postman collection designed to interact with the Restful-Booker API, which provides a REST-based booking service. The collection includes multiple requests that allow users to perform essential operations, such as creating, retrieving, updating, and deleting bookings. The project simulates an end-to-end API testing suite, including token-based authentication, dynamic variables, and response validation using Postman scripts.

## Features
- **Create Token**: Generates a token for authentication, which is used for subsequent requests.
- **Get Booking IDs**: Retrieves a list of booking IDs.
- **Get Booking**: Fetches the details of a specific booking using its ID.
- **Create Booking**: Creates a new booking with provided details such as check-in and check-out dates.
- **Update Booking**: Updates an existing booking with new details using the PUT method.
- **Partial Update Booking**: Partially updates a booking's details using the PATCH method.
- **Delete Booking**: Deletes an existing booking by its ID.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/restful-booker-collection.git
2. Import the collection into Postman:
    1. Open Postman, click on `File -> Import`.
    2. Select the collection file from this repository.

## Usage
### Authentication:
- Start by running the **Create Token** request. This will generate an authentication token and save it in the environment as `loginToken`.

### Booking Operations:
- Use the **Create Booking** request to add new bookings.
- Use **Get Booking** or **Get Booking IDs** to fetch booking details.
- Modify bookings using **Update Booking** or **Partial Update Booking**.
- Delete bookings using **Delete Booking**.

## Testing
Each request contains Postman test scripts that validate the responses. For example:
- In the **Create Token** request, the test script checks that the status code is 200 and saves the token for use in future requests.
- In the **Update Booking** request, the test script checks that the booking's first name is updated as expected.

## Contributing
Contributions are welcome. Feel free to submit issues or pull requests.

## License
This project is licensed under the MIT License.
