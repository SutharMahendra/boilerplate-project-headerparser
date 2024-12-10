# Request Header Parser Microservice

This is a simple Node.js application that serves as a **Request Header Parser Microservice**. It provides details about the client's IP address, preferred language, and software (user-agent) by parsing the HTTP request headers.

## Features

- Parses the client's IP address, language, and software information from the request headers.
- Returns the data in a structured JSON format.

## API Endpoint

### **GET** `/api/whoami`

#### Response:
Returns a JSON object with the following structure:
```json
{
  "ipaddress": "<client-ip-address>",
  "language": "<preferred-language>",
  "software": "<user-agent-string>"
}
```


## How to Use
### Prerequisites

- Node.js (v14 or later)
- npm (Node Package Manager)
  
### Setup

#### Clone the repository:
```
git clone https://github.com/your-username/request-header-parser-microservice.git
```
#### Update nodemon
```
npm i nodemon
```

### Run the Application
Start the server:
```
nodemon start
```

Access the application at http://localhost:3000/api/whoami.

