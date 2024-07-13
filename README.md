<h1 align="center" id="title">Node.js API with MongoDB and Mongoose</h1>

<p id="description">This project is a Node.js API backend that implements CRUD operations for managing users and orders using MongoDB as the database and Mongoose for object modeling.</p>
  
  
<h2>🧐 Features</h2>

Here're some of the project's best features:

* Retrieve a list of users with `GET /users`.
* Create a new user with `POST /users`.
* Retrieve a list of orders with `GET /orders`.
* Create a new order with `POST /orders`.
* Uses MongoDB for data storage.
* Error handling and validation for API endpoints.


<h2>🛠️ Installation Steps:</h2>

<p>1. Clone the repo navigate to the directory and run</p>

```
npm install
node index.js
```

<p>2. visit http://localhost:3000 to see it in action!</p>

```
http://localhost:3000 
```

The server will start running on `http://localhost:3000`.

<h2>Endpoints:</h2>

### Users

- **GET /users**
  - Retrieves a list of all users.
  - Response: JSON array of user objects `{ _id, name, email }`.

- **POST /users**
  - Creates a new user.
  - Request body: `{ name, email }`.
  - Response: JSON object representing the created user `{ _id, name, email }`.

### Orders

- **GET /orders**
  - Retrieves a list of all orders.
  - Response: JSON array of order objects `{ _id, productId, quantity, status }`.

- **POST /orders**
  - Creates a new order.
  - Request body: `{ productId, quantity }`.
  - Response: JSON object representing the created order `{ _id, productId, quantity, status }`.

<h2>🛠️ Sample JSON object to post to /users:</h2>

```
{
  "name": "John Doe",
  "email": "john.doe@example.com"
}
```
<h2>🛠️ Sample JSON object to post to /orders:</h2>

```
{
  "productId": "product_id_here",
  "quantity": 2
}
```

<h2>Why I should get hired?:</h2>

```
*   Self Driven - I don't need continuous instructions or spoon feeding. I am self motivated and self critical, I know how to find and learn the things I need to complete any given task. 
*   Perfectionist - I don't settle for less, I always believe that no matter what I do there's always more room for improvement. 
*   Entrepreneurial Mindset - I have an entrepreneurial mindset which helps me see things from both technical and business perspective.
*   Determined - I am always determined to do the best I can in work and my personal life in general.
*   Team Player - My success and my team's success is OUR success, I'm all about the team spirit.
*   Quick Learner - I can learn any new topic in a short period of time, just give me the key words and I'll dig through Google and do my own research. 
*   Open to Criticism - I highly encourage criticism, it drives me to get better and improve.
```
  
  
<h2>💻 Built with</h2>

Technologies used in this project:

* [Node.js](https://nodejs.org/) - JavaScript runtime environment
* [Express](https://expressjs.com/) - Web framework for Node.js
* [MongoDB](https://www.mongodb.com/) - NoSQL database
* [Mongoose](https://mongoosejs.com/) - MongoDB object modeling for Node.js
* [dotenv](https://www.npmjs.com/package/dotenv) - Loads environment variables from a `.env` file


<h2>🍰 Contribution Guidelines:</h2>

Pull requests are welcome! Please open an issue first to discuss any changes or additions.

<h2>🛡️ License:</h2>

This project is licensed under the Distributed under the MIT license.
