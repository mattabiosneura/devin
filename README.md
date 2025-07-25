# TestDevin - Sample Mulesoft API

This is a Mulesoft API project that demonstrates the use of RAML with traits and libraries for better organization and reusability.

## Project Structure

```
├── src/main/
│   ├── mule/
│   │   └── sampleapi.xml          # Main Mule configuration
│   └── resources/
│       ├── api/
│       │   ├── sampleapi.raml     # Main API definition
│       │   └── libraries/
│       │       ├── data-types.raml # Data type definitions
│       │       └── traits.raml     # Reusable traits
│       └── log4j2.xml             # Logging configuration
├── pom.xml                        # Maven configuration
└── mule-artifact.json             # Mule runtime configuration
```

## API Endpoints

- **POST /sampleapi/createUser** - Create a new user

### Request Format
```json
{
  "First Name": "Matthew",
  "Last Name": "Tabios"
}
```

### Response Format
```json
{
  "code": 200,
  "response": "Successfull Create"
}
```

## Running the Application

1. Import the project into Anypoint Studio
2. Run the application
3. The API will be available at `http://localhost:8081/sampleapi`

## Features

- RAML-first design with traits and libraries
- Modular and reusable API structure
- Comprehensive error handling
- APIKit scaffolding

## Development

This project was created by Devin AI for @mattabiosneura.
Link to Devin run: https://app.devin.ai/sessions/85acc29bcdba46f29c03d1f1e27d4425
