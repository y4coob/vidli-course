
# Node.js Application

This project is a Node.js application connected to MongoDB using MongoDB Compass. It includes various routes that can be tested using Postman.

## Prerequisites

- [Node.js](https://nodejs.org/en/download/) installed on your machine.
- [MongoDB Compass](https://www.mongodb.com/try/download/compass) installed for database management.
- Postman for testing the API routes.

## Getting Started

1. **Clone the Repository**
   ```bash
   git clone https://github.com/y4coob/vidly-course.git
   cd vidly-course
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Run the Application**
   ```bash
   node index.js
   ```

4. **Make API Requests**
   - Use Postman to send requests to your API routes. Here are a few examples:
     - `GET http://localhost:3000/api/genres/:id`
     - `POST http://localhost:3000/api/users` with a JSON body.

## JWT Key

A JWT (JSON Web Token) key is used for signing and verifying tokens that contain user information. It is essential for ensuring secure communication between the client and server. Make sure to keep this key confidential.

## Course Acknowledgment

This project was part of my Node.js course from Mosh Hamedani, titled **"The Complete Node.js Course."**

## License

This project is licensed under the MIT License.

---
