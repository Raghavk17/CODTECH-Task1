**Name:** RAGHAV KUSHWAHA 
**Company:** CODTECH IT SOLUTIONS  
**ID:** CT04DS6323
**Domain:** Backend 
**Duration:** August to September 2024  
**Mentor:** Muzammil Ahmed

## *Overview of the Project*

### *Project*: *User Data REST API*

### *Objective*  
The objective of this project is to create a REST API using Express.js that serves user data from a `MOCK_DATA.json` file. The API allows for retrieving user data in both HTML and JSON formats, providing a simple interface for listing users and accessing individual user details by ID.

### *Key Activities*  
- **API Development**: *Creating endpoints to serve user data.*
- **Data Handling**: *Loading and serving data from a JSON file.*
- **Server Setup**: *Configuring and running the server using Express.js.*

### *Technologies Used*  
- **Node.js**: *JavaScript runtime for server-side development.*
- **Express.js**: *Web framework for building the API.*
- **MOCK_DATA.json**: *JSON file containing sample user data.*

## *Installation*

1. **Clone the Repository**:
   git clone https://github.com/your-username/your-repository-name.git
   cd your-repository-name
2. **Install Dependencies:**:
   npm install
3. **Start the Server:**:
   npm start
   The server will start on http://localhost:8000.

   ## *API Endpoints*

- **GET /users**
  - **Description**: Returns an HTML list of user first names.
  - **Response**: HTML formatted list.

- **GET /api/users**
  - **Description**: Returns a JSON array of all users.
  - **Response**:
    ```json
    [
      {
        "id": 1,
        "first_name": "John",
        "last_name": "Doe",
        ...
      },
      ...
    ]
    ```

- **GET /api/users/:id**
  - **Description**: Returns details of a user with the specified ID.
  - **Response**:
    ```json
    {
      "id": 1,
      "first_name": "John",
      "last_name": "Doe",
      ...
    }
    ```
## *Project Structure*

- **index.js**: *Main server file where routes and server configuration are defined.*
- **MOCK_DATA.json**: *JSON file containing user data.*
- **package.json**: *Project metadata and dependencies.*
- **package-lock.json**: *Dependency versions lock file.*



