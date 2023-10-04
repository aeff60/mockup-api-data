# User Management API Mock Data

This repository contains mock data in JSON format for a User Management API. The data is designed to simulate user information for testing and development purposes.

## Data Structure

The main data file is `data.json`, and it contains an array of user objects. Each user object has the following properties:

- `id`: User ID (numeric)
- `username`: User's username (string)
- `email`: User's email address (string)
- `age`: User's age (numeric)
- `address`: User's address information, including:
  - `street`: Street address (string)
  - `city`: City (string)
  - `state`: State (string)
  - `zip`: Zip code (string)

## Example User

```json
{
  "id": 1,
  "username": "john_doe",
  "email": "john.doe@example.com",
  "age": 30,
  "address": {
    "street": "123 Main St",
    "city": "Cityville",
    "state": "CA",
    "zip": "12345"
  }
}
